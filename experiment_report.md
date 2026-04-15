# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** AI20K-2A202600445
**Name:** Dương Quang Đông
**Date:** 15/4/2026

---

## 1. Ket qua thi nghiem

Chay `agent_simulation.py` voi 2 bo du lieu va ghi lai ket qua:

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) |  Based on my data, the best choice is Laptop at $1200. | 10 | |
| Garbage Data (`garbage_data.csv`) | Based on my data, the best choice is Nuclear Reactor at $999999. | 1 | Dữ liệu không sạch |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

Khi dùng garbage data, mẫu dữ liệu Nuclear Reactor nằm trong thoả mãn yêu cầu truy xuất của dữ liệu, dù không thực tế, agent lựa chọn loại electronics với giá cao nhất chính là Nuclear Reactor.

---

## 3. Ket luan

**Quality Data > Quality Prompt?** (Dong y hay khong? Giai thich ngan gon.)

Quality Prompt giúp kiểm soát tốt agent và cách xử lý, truy xuất và trả lời câu hỏi của sản phẩm xong nếu dữ liệu không được làm sạch dù agent có prompt tốt vẫn sẽ dựa trên dữ liệu sai mà trả lời sai.
