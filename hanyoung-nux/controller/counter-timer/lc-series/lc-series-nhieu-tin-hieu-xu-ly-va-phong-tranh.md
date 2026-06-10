---
title: "LC Series | Xử Lý Nhiễu Tín Hiệu — Nguyên Nhân và Cách Phòng Tránh"
slug: lc-series-nhieu-tin-hieu-xu-ly-va-phong-tranh
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, NhieuTinHieu, Noise, Shield, GrundDat, KyThuat]
description: "Nguyên nhân và cách xử lý nhiễu tín hiệu trên LC Series Hanyoung Nux: đếm nhảy số, đếm sai. Hướng dẫn dùng cáp shield, nối đất, bộ lọc nhiễu."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-nhieu-tin-hieu-xu-ly-va-phong-tranh/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# LC Series | Xử Lý Nhiễu Tín Hiệu — Đếm Nhảy Số

Triệu chứng phổ biến nhất khi lắp LC Series là **đếm nhảy số** hoặc **đếm nhiều hơn thực tế**. Nguyên nhân gần như luôn là nhiễu tín hiệu.

---

## Nguyên nhân nhiễu thường gặp

| Nguyên nhân | Biểu hiện |
|---|---|
| Cáp tín hiệu chạy gần cáp động lực | Đếm tăng đột biến khi motor khởi động |
| Không nối đất tủ điện | Đếm không ổn định liên tục |
| Cáp dài không có shield | Đếm sai khi cáp > 5m |
| Tiếp điểm cơ học rung (contact bounce) | Đếm 2–3 lần cho 1 lần đóng |
| Inverter/biến tần gần LC Series | Nhiễu cao tần, đếm liên tục |

---

## Giải pháp xử lý nhiễu

### 1. Dùng cáp có shield
- Cáp tín hiệu từ cảm biến/encoder đến LC Series phải có lớp shield
- Nối đầu shield vào **đất tủ điện** tại 1 đầu (không nối cả 2 đầu)

### 2. Tách cáp tín hiệu khỏi cáp điện
- Khoảng cách tối thiểu: 30cm
- Đi đường khác nhau trong tủ điện

### 3. Thêm RC filter tại đầu vào
Với contact cơ học bị bounce: thêm tụ 0.1µF + điện trở 1kΩ song song với tiếp điểm → lọc xung ngắn.

### 4. Chọn đúng tốc độ đếm
LC Series có 4 mức: 1 cps / 30 cps / 1 Kcps / **10 Kcps**. Không cần thiết dùng 10 Kcps nếu tín hiệu chậm — chọn tốc độ thấp hơn để tránh đếm nhiễu.

---

## LC Series có khả năng chống nhiễu nội tại

- Chịu nhiễu xung vuông ±2000V (pulse width 1μs) theo tiêu chuẩn
- Cách điện 100 MΩ tại 500V DC
- Chịu điện áp 2000V AC trong 1 phút

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com]($PURL) | 📧 hoangphuc@hynux.com
