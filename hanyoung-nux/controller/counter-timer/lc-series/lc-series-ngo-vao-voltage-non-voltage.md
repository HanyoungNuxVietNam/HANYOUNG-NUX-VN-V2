---
title: "LC Series | Ngõ Vào Voltage Input và Non-Voltage Input — Khác Nhau Thế Nào?"
slug: lc-series-ngo-vao-voltage-non-voltage
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, NgoVao, VoltageInput, NonVoltage, TinHieu, KetNoi]
description: "Giải thích 2 loại ngõ vào trên LC Series Hanyoung Nux: Voltage Input (5-30V DC) và Non-Voltage Input (contact khô). Hướng dẫn chọn đúng loại theo cảm biến."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-ngo-vao-voltage-non-voltage/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# LC Series | Ngõ Vào Voltage Input và Non-Voltage Input

LC Series hỗ trợ 2 kiểu ngõ vào, chọn bằng **external switch** trên thiết bị.

---

## So sánh 2 loại ngõ vào

| Tiêu chí | Voltage Input | Non-Voltage Input |
|---|---|---|
| Tín hiệu | Điện áp DC | Contact khô (relay, micro switch) |
| Mức HIGH | 5–30V DC | N/A (short circuit) |
| Mức LOW | 0–2V DC | N/A (open circuit) |
| Trở kháng vào | ~4.5 kΩ | Trở kháng khi đóng: max 1 kΩ |
| Dùng với | Cảm biến (NPN/PNP), encoder | Relay, micro switch, limit switch, nút bấm |

---

## Cách chọn đúng loại ngõ vào

**Dùng Voltage Input khi:**
- Kết nối cảm biến quang, cảm biến tiệm cận (NPN/PNP)
- Kết nối encoder incremental
- Tín hiệu đầu ra từ PLC (transistor output)

**Dùng Non-Voltage Input khi:**
- Kết nối relay contact
- Kết nối micro switch, limit switch cơ học
- Kết nối nút bấm, công tắc hành trình

---

## Cài đặt loại ngõ vào

Trên thiết bị LC Series có **external switch** nhỏ ở cạnh — gạt sang vị trí phù hợp:
- **V** = Voltage Input
- **NV** = Non-Voltage Input

---

## Câu hỏi thường gặp

**Cảm biến quang NPN dùng loại ngõ vào nào?**
Voltage Input — cảm biến NPN kéo tín hiệu xuống GND (LOW = vật có mặt).

**Relay contact 220V có vào Non-Voltage Input được không?**
Không — Non-Voltage Input chỉ nhận contact khô (dry contact), không có điện áp riêng.

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com]($PURL) | 📧 hoangphuc@hynux.com
