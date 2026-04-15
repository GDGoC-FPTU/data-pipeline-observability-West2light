[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23574928&assignment_repo_type=AssignmentRepo)
# Day 10 Lab: Data Pipeline & Data Observability

**Student Email:** quangdong010203@gmail.com
**Name:** Dương Quang Đông

---

## Mo ta

Bài lab mô phỏng agent trả lời câu hỏi dựa trên 2 kiểu dữ liệu chưa được và đã được làm sạch, chuẩn hoá 

---

## Cach chay (How to Run)

### Prerequisites
```bash
pip install pandas
```

### Chay ETL Pipeline
```bash
python solution.py
```

### Chay Agent Simulation (Stress Test)
```bash
Mô phỏng input người dùng với câu hỏi What is the best electronic product?, agent mô phỏng sẽ trả lời với sản phẩm electronic có giá lớn nhất.
```

---

## Cau truc thu muc

```
├── solution.py              # ETL Pipeline script
├── processed_data.csv       # Output cua pipeline
├── experiment_report.md     # Bao cao thi nghiem
└── README.md                # File nay
```

---

## Ket qua

Dữ liệu garbage có tổng cộng 5 mẫu dữ liệu, sau làm sạch loại bỏ 2 mẫu dữ liệu bị lặp id và thiếu trường được 3 mẫu dữ liệu sạch.
