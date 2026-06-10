---
title: "Reset Bộ Đếm LC Series | Hướng Dẫn Reset Tay, Reset Tự Động, Reset Từ PLC"
slug: lc-series-reset-bo-dem-cac-phuong-phap
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, Reset, BoDem, PLC, TuDong, HuongDan]
description: "Hướng dẫn các phương pháp reset bộ đếm LC Series: reset tay bằng nút bấm, reset tự động khi đạt preset, reset từ xa qua PLC, reset qua Modbus RS485."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-reset-bo-dem-cac-phuong-phap/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# Reset Bộ Đếm LC Series | 4 Phương Pháp

LC Series hỗ trợ nhiều cách reset bộ đếm về 0, tùy theo yêu cầu của hệ thống.

---

## 4 phương pháp reset

### 1. Reset tay — nút RST trên thiết bị
Nhấn nút **RST** trên mặt LC Series → bộ đếm về 0 ngay lập tức. Phù hợp khi vận hành thủ công.

### 2. Reset tự động sau khi đạt preset (Auto Reset)
Cài chế độ **Auto Reset**: khi đếm đạt giá trị preset → tự động reset về 0 và bắt đầu đếm lại. Phù hợp đếm theo lô liên tục.

### 3. Reset từ PLC qua tín hiệu RESET input
Chân **RESET** trên LC Series nhận tín hiệu từ ngõ ra PLC → reset khi PLC ra lệnh. Dùng trong hệ thống tự động hóa có PLC điều phối.

**Thông số RESET input:**
- Minimum pulse width: 1ms
- Voltage: 5–30V DC (Voltage Input mode)

### 4. Reset từ xa qua Modbus RS485
PLC/SCADA ghi lệnh reset vào Modbus register của LC Series → reset mà không cần dây tín hiệu riêng. Chỉ dùng với model có RS485 (hậu tố C).

### 5. BATCH RESET — reset tất cả cùng lúc
Chân **BATCH-RESET** reset đồng thời cả bộ đếm lẫn bộ định thời — tiện cho hệ thống cần đồng bộ.

---

## Câu hỏi thường gặp

**Reset có làm mất cài đặt Pre-scale và Preset không?**
Không. Reset chỉ đưa giá trị đếm về 0, không thay đổi cài đặt.

**PLC reset LC Series bao lâu thì có hiệu lực?**
Xung RESET tối thiểu 1ms là đủ — hầu hết PLC xuất xung dài hơn nên không vấn đề gì.

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com]($PURL) | 📧 hoangphuc@hynux.com
