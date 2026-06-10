---
title: "LC Series Hanyoung Nux | Chức Năng Offset Bộ Đếm và Định Thời"
slug: lc-series-chuc-nang-offset-bo-dem-dinh-thoi
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, Offset, BoDem, DinhThoi, CauHinh]
description: "Hướng dẫn sử dụng chức năng Offset trên LC Series Hanyoung Nux. Offset cho phép bù giá trị đếm hoặc thời gian — hữu ích khi cần hiển thị giá trị thực tế thay vì số xung."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-chuc-nang-offset-bo-dem-dinh-thoi/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# LC Series Hanyoung Nux | Chức Năng Offset Bộ Đếm và Định Thời

**Offset** là tính năng mới trong LC Series cho phép cộng hoặc trừ một giá trị cố định vào kết quả hiển thị. Tính năng này rất hữu ích khi cần hiệu chỉnh giá trị đo mà không cần thay đổi cơ học.

---

## Offset là gì?

```
Giá trị hiển thị = Giá trị đếm thực × Pre-scale + Offset
```

**Ví dụ thực tế:**
- Băng chuyền bắt đầu đếm từ vị trí 500mm (không phải 0mm)
- Không muốn reset encoder về 0
- Cài Offset = 500 → màn hình hiển thị đúng vị trí thực tế từ đầu

---

## Ứng dụng Offset phổ biến

### 1. Hiệu chỉnh chiều dài đo
Cảm biến đặt cách đầu vật liệu 200mm → Offset = -200 → màn hình hiển thị chiều dài thực của vật liệu (không tính đoạn trống ban đầu).

### 2. Bù sai số hệ thống
Con lăn bị mòn → mỗi vòng không còn đúng chu vi thiết kế → thay vì thay con lăn, điều chỉnh Offset để bù sai số.

### 3. Định nghĩa điểm 0 tùy ý
Trong hệ thống đo vị trí, cài Offset để điểm 0 màn hình trùng với điểm tham chiếu thực tế của máy.

---

## Phân biệt Offset và Pre-scale

| Tính năng | Công thức | Dùng khi nào |
|---|---|---|
| Pre-scale | Nhân mỗi xung | Quy đổi đơn vị (xung → mm, m, kg) |
| Offset | Cộng vào kết quả | Bù sai số, dịch chuyển điểm 0 |

---

## Câu hỏi thường gặp

**Offset có thể là số âm không?**
Có. Offset âm dùng để trừ bớt giá trị hiển thị.

**Offset và Pre-scale có dùng đồng thời không?**
Có — LC Series áp dụng Pre-scale trước, rồi cộng Offset sau.

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com](https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002) | 📧 hoangphuc@hynux.com
