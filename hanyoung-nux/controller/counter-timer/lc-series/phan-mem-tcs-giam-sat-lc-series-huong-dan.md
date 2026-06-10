---
title: "Phần Mềm TCS Hanyoung Nux | Giám Sát LC Series Từ Máy Tính Miễn Phí"
slug: phan-mem-tcs-giam-sat-lc-series-huong-dan
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, TCS, PhanMem, GiamSat, RS485, Modbus]
description: "Hướng dẫn sử dụng phần mềm TCS miễn phí của Hanyoung Nux để giám sát và cấu hình LC Series từ máy tính qua RS485. Tải TCS, kết nối, đọc dữ liệu real-time."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/phan-mem-tcs-giam-sat-lc-series-huong-dan/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# Phần Mềm TCS Hanyoung Nux | Giám Sát LC Series Từ Máy Tính

**TCS (Total Control System)** là phần mềm miễn phí của Hanyoung Nux, cho phép kết nối và giám sát LC Series từ máy tính qua cổng RS485.

---

## TCS làm được gì?

- Đọc giá trị đếm real-time từ nhiều LC Series cùng lúc
- Cài đặt Pre-scale, Preset, Offset từ xa
- Lưu lịch sử dữ liệu đếm theo thời gian
- Xuất báo cáo sản lượng

---

## Yêu cầu hệ thống

| Yêu cầu | Thông số |
|---|---|
| Hệ điều hành | Windows 7 / 10 / 11 |
| Giao tiếp | USB-to-RS485 converter |
| LC Series | Phải là model có hậu tố **C** (RS485) |

---

## Các bước kết nối TCS

1. Tải TCS tại: [www.hanyoungnux.com](https://www.hanyoungnux.com/data/main.php?type=3) → Software
2. Cắm USB-to-RS485 converter vào máy tính
3. Đấu dây RS485: A(+) → A(+) LC Series, B(-) → B(-) LC Series
4. Mở TCS → chọn COM port → tốc độ baud phải khớp với cài đặt trên LC Series
5. Nhập địa chỉ Modbus của LC Series (mặc định: 1)
6. Nhấn Connect → dữ liệu hiện real-time

---

## Câu hỏi thường gặp

**TCS có phí không?**
Hoàn toàn miễn phí — tải trực tiếp từ trang chính hãng Hanyoung Nux.

**Kết nối bao nhiêu LC Series cùng lúc?**
Tối đa 31 thiết bị trên 1 đường RS485, mỗi thiết bị một địa chỉ Modbus khác nhau (1–127).

**Không có RS485 trên LC Series, có dùng TCS được không?**
Không — TCS chỉ hoạt động với model có hậu tố C (RS485 Modbus RTU).

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com](https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002) | 📧 hoangphuc@hynux.com
