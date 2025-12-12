# Đồ án Xử lý Ngôn ngữ Tự nhiên HK1 2025-2026  
**Đề tài**: Dịch máy Anh-Pháp / Anh-Đức với mô hình Encoder-Decoder LSTM (không attention)

Nhóm thực hiện:  
- [Phạm Minh Dương - MSSV: 3123410065]  
- [Phạm Tấn Đạt - MSSV: 3123410072]  


### Mô tả ngắn gọn
Đồ án tái hiện lại mô hình Seq2Seq cổ điển bằng PyTorch (LSTM 2 tầng, không attention, teacher forcing 0.5, greedy decoding).  
Dataset: Multi30K (English → French).  
Kết quả đạt được:  
- BLEU-4 ≈ 7.38  
- Perplexity ≈ 90.99  
(tập test 1.071 câu)
