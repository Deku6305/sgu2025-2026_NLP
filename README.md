# Đồ án Xử lý Ngôn ngữ Tự nhiên (NLP) - HK1 2025-2026 🎓

## 📖 Đề tài: Dịch máy Anh-Pháp / Anh-Đức (Machine Translation)
**Mô hình:** Sequence-to-Sequence (Seq2Seq) sử dụng Encoder-Decoder LSTM.

---

## 👥 Thành viên thực hiện

| STT | Họ và tên | MSSV |
|:---:|:---|:---:|
| 1 | **Mai Thanh Duy** | 3123410055 | 
| 2 | **Nguyễn Tuấn Đạt** | 3123410070 |

---

## 📝 Giới thiệu (Introduction)

[cite_start]Dự án này triển khai một mô hình **Sequence-to-Sequence (Seq2Seq)** sử dụng kiến trúc **LSTM (Long Short-Term Memory)** để giải quyết bài toán dịch máy từ tiếng Anh sang tiếng Pháp[cite: 11].

### Yêu cầu kỹ thuật bắt buộc:
* [cite_start]**Kiến trúc:** Encoder-Decoder với context vector cố định[cite: 12].
* **Ràng buộc:** Không sử dụng cơ chế Attention. [cite_start]Không sử dụng các thư viện seq2seq có sẵn (như `torchtext.legacy` hay `transformers`), mô hình được xây dựng "from scratch" bằng PyTorch[cite: 12, 19].
* [cite_start]**Mục tiêu:** Hiểu rõ cách xử lý dữ liệu chuỗi, packing/padding và luồng hoạt động của RNN/LSTM[cite: 21, 22].
---

## 📂 Cấu trúc thư mục

```bash
├── data/                   # Chứa dữ liệu train/test
├── checkpoints/            # Chứa best_model 
├── notebooks/              # Jupyter Notebooks 
├── README.md               # Thông tin thành viên, dự án
