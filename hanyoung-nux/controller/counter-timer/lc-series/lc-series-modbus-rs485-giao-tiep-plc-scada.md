---
title: "LC Series Hanyoung Nux | Giao Tiếp Modbus RS485 Với PLC và SCADA"
slug: lc-series-modbus-rs485-giao-tiep-plc-scada
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, Modbus, RS485, PLC, SCADA, KetNoi]
description: "Hướng dẫn kết nối LC Series Hanyoung Nux qua Modbus RTU RS485 với PLC và SCADA. Tốc độ baud 2400–38400 bps, kết nối tối đa 31 thiết bị, khoảng cách 800m."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-modbus-rs485-giao-tiep-plc-scada/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# LC Series Hanyoung Nux | Giao Tiếp Modbus RS485 Với PLC và SCADA

LC Series Hanyoung Nux hỗ trợ **giao tiếp Modbus RTU qua RS485** — cho phép PLC hoặc hệ thống SCADA đọc giá trị đếm, cài đặt preset và điều khiển từ xa mà không cần thao tác tay trên thiết bị.

---

## Thông số giao tiếp Modbus RS485

| Thông số | Giá trị |
|---|---|
| Giao thức | Modbus RTU |
| Phương thức | RS485 (2 dây, half-duplex) |
| Tốc độ baud | 2,400 / 4,800 / 9,600 / 19,200 / 38,400 bps |
| Khoảng cách tối đa | 800 m |
| Số thiết bị kết nối | Tối đa 31 (địa chỉ 1–127) |
| Data bit | 8 bit |
| Stop bit | 1 bit |
| Parity | None / Odd / Even |
| Thời gian phản hồi | 5–99 ms (cài đặt được) |

> **Lưu ý model:** Chỉ các model có hậu tố **C** (ví dụ LC3-P62CA, LC6-P62CA) mới có RS485. Model không có **C** không hỗ trợ Modbus.

---

## Sơ đồ đấu dây RS485

```
LC Series (RS485)        PLC / SCADA Converter
    A (+) ────────────── A (+)
    B (-) ────────────── B (-)
    GND  ────────────── GND (tùy converter)
```

Nếu kết nối nhiều thiết bị LC Series trên 1 đường RS485, đấu dây theo kiểu **daisy chain** (nối tiếp, không rẽ nhánh). Thêm điện trở kết thúc (termination resistor) 120Ω ở 2 đầu đường bus.

---

## Ứng dụng Modbus thực tế

### 1. Đọc giá trị đếm từ SCADA
Hệ thống SCADA (WinCC, Ignition, FactoryTalk...) poll Modbus register của LC Series mỗi 500ms → hiển thị số lượng sản phẩm real-time trên màn hình vận hành.

### 2. Reset bộ đếm từ PLC
PLC tự động ghi lệnh reset vào LC Series sau mỗi ca sản xuất — không cần công nhân thao tác tay trên bộ đếm.

### 3. Thay đổi preset từ xa
HMI trên văn phòng thay đổi giá trị preset (số lượng mỗi lô) mà không cần vào nhà xưởng.

### 4. Kết nối nhiều dây chuyền
1 PC giám sát có thể kết nối tối đa 31 bộ đếm LC Series qua 1 đường RS485 — tiết kiệm chi phí cáp và converter.

---

## Phần mềm TCS — Giám sát miễn phí

Phần mềm **TCS** đi kèm miễn phí hỗ trợ kết nối RS485, cho phép:
- Xem giá trị đếm real-time của nhiều LC Series cùng lúc
- Lưu lịch sử đếm theo thời gian
- Cài đặt cấu hình từ xa

---

## Câu hỏi thường gặp

**LC Series model nào hỗ trợ Modbus RS485?**
Các model có hậu tố **C**: LC3-P62CA, LC3-P62CD, LC6-P62CA, LC7-P62CA... Kiểm tra suffix code khi đặt hàng.

**Kết nối RS485 xa 200m có cần thiết bị gì thêm không?**
Không cần thêm gì nếu dùng cáp twisted pair có shield và đầu nối đúng. Đối với khoảng cách trên 400m, kiểm tra chất lượng cáp và bổ sung điện trở kết thúc.

**Tốc độ baud nào phù hợp nhất?**
9,600 bps là lựa chọn phổ biến nhất — cân bằng giữa tốc độ và độ ổn định. Chỉ tăng lên 19,200 hoặc 38,400 khi cần poll nhiều thiết bị với chu kỳ ngắn.

---

## Liên hệ tư vấn

📞 **Hotline:** 0909193674
🌐 **Website:** [www.hanyoungnux.com](https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002)
📧 **Email:** hoangphuc@hynux.com

---

*Xem thêm: [LC Series — Tổng quan](lc-series-hanyoung-nux-bo-dem-dinh-thoi-lcd/) · [Hướng dẫn kết nối với PLC](huong-dan-ket-noi-lc-series-voi-plc/)*
