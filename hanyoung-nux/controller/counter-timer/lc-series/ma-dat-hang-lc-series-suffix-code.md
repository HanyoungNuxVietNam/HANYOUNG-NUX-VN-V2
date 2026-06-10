---
title: "Mã Đặt Hàng LC Series Hanyoung Nux | Giải Thích Suffix Code Chi Tiết"
slug: ma-dat-hang-lc-series-suffix-code
date: 2026-06-10
updated: 2026-06-10
category: tu-van-mua-hang
tags: [HanyoungNux, LCSeries, SuffixCode, DatHang, MaSanPham, LC1, LC3, LC6, LC7]
description: "Hướng dẫn đọc và đặt hàng đúng mã LC Series Hanyoung Nux. Giải thích chi tiết suffix code: kích thước, số ngõ ra, RS485, nguồn điện AC/DC."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/ma-dat-hang-lc-series-suffix-code/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# Mã Đặt Hàng LC Series Hanyoung Nux | Giải Thích Suffix Code

Khi đặt hàng LC Series, cần chỉ định đúng mã model đầy đủ. Mã sai → nhận thiết bị không phù hợp với hệ thống.

---

## Cấu trúc mã model

```
LC  [Kích thước] - P [Chữ số] [Ngõ ra] [Sub] [Nguồn]

Ví dụ: LC3 - P 6 2 C A
         │    │ │ │ │ └── Nguồn: A = AC, D = DC
         │    │ │ │ └──── Sub: N = không RS485, C = có RS485
         │    │ │ └────── Ngõ ra: 1 = 1 tầng, 2 = 2 tầng
         │    │ └──────── Chữ số: 4 = 4 số, 6 = 6 số
         │    └────────── P = Preset Counter/Timer
         └─────────────── Kích thước (1/3/4/6/7)
```

---

## Bảng suffix code chi tiết

| Ký hiệu | Vị trí | Ý nghĩa |
|---|---|---|
| LC | Đầu | Dòng LCD Counter/Timer |
| 1 | Kích thước | 48×24mm |
| 3 | Kích thước | 96×48mm |
| 4 | Kích thước | 48×48mm |
| 6 | Kích thước | 72×36mm |
| 7 | Kích thước | 72×72mm |
| P | Settings | Preset Counter/Timer |
| 4 | Chữ số | 4 chữ số (chỉ LC1/LC4) |
| 6 | Chữ số | 6 chữ số |
| 1 | Ngõ ra | 1 ngõ ra |
| 2 | Ngõ ra | 2 ngõ ra (trừ LC1) |
| N | Sub output | Không có RS485 |
| C | Sub output | Có RS485 Modbus RTU |
| A | Nguồn | AC 100–240V |
| D | Nguồn | DC 24–48V (trừ LC1) |

---

## Ví dụ mã thường gặp

| Mã model | Ý nghĩa |
|---|---|
| LC3-P62CA | LC3, 6 số, 2 ngõ ra, có RS485, AC |
| LC3-P62CD | LC3, 6 số, 2 ngõ ra, có RS485, DC |
| LC3-P62NA | LC3, 6 số, 2 ngõ ra, không RS485, AC |
| LC6-P62CA | LC6, 6 số, 2 ngõ ra, có RS485, AC |
| LC7-P62CA | LC7, 6 số, 2 ngõ ra, có RS485, AC |
| LC1-P41NA | LC1, 4 số, 1 ngõ ra, không RS485, AC |
| LC4-P61CA | LC4, 6 số, 1 ngõ ra, có RS485, AC |

---

## Checklist trước khi đặt hàng

- [ ] Cần AC hay DC? (điện áp tủ điện hiện có)
- [ ] Cần 1 hay 2 ngõ ra điều khiển?
- [ ] Cần RS485 Modbus không? (có PLC/SCADA giám sát?)
- [ ] Kích thước lỗ khoét tủ điện hiện có?
- [ ] 4 hay 6 chữ số? (phạm vi đếm tối đa)

---

## Câu hỏi thường gặp

**LC3-P62CA và LC3-P62NA khác nhau gì?**
Chỉ khác ở chức năng RS485: CA có Modbus RTU, NA không có. Giá CA cao hơn một chút.

**Tôi có thể thêm RS485 sau khi mua model không có C không?**
Không. RS485 là phần cứng tích hợp sẵn, không thể nâng cấp sau khi mua.

**LC1 có model DC không?**
Không — LC1 chỉ có nguồn AC. Nếu cần DC, dùng LC3, LC4, LC6 hoặc LC7.

---

## Liên hệ đặt hàng

📞 **Hotline:** 0909193674
🌐 **Website:** [www.hanyoungnux.com](https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002)
📧 **Email:** hoangphuc@hynux.com

---

*Xem thêm: [LC3 vs LC7 vs LC1 — So sánh model](lc3-vs-lc7-vs-lc1-hanyoung-nux-so-sanh/) · [Giá & Hướng dẫn chọn model](gia-lc-series-hanyoung-nux-huong-dan-chon-model/)*
