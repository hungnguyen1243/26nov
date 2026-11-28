---
tags: [moc, people, crm]
---
# People — bảng điều khiển

Quy tắc lưu và bảo mật: [[QUY-UOC-DU-LIEU-NGUOI]]. Hồ sơ có dữ liệu cá nhân được loại khỏi Git.

## Hẹn đến hạn trong 7 ngày

```dataview
TABLE trang_thai, lan_cuoi_gap, hen_tiep, khu_quan_tam
FROM "04. Resources/People"
WHERE loai = "nguoi" AND hen_tiep AND hen_tiep <= date(today) + dur(7 days)
SORT hen_tiep ASC
```

## Đang treo / chưa có lịch hẹn

```dataview
TABLE trang_thai, lan_cuoi_gap, khu_quan_tam
FROM "04. Resources/People"
WHERE loai = "nguoi" AND trang_thai = "treo"
SORT lan_cuoi_gap ASC
```

## Nguội quá 21 ngày

```dataview
TABLE trang_thai, lan_cuoi_gap, khu_quan_tam
FROM "04. Resources/People"
WHERE loai = "nguoi" AND lan_cuoi_gap AND lan_cuoi_gap <= date(today) - dur(21 days) AND trang_thai != "mat"
SORT lan_cuoi_gap ASC
```

## Theo giai đoạn

```dataview
TABLE length(rows) AS "Số người"
FROM "04. Resources/People"
WHERE loai = "nguoi"
GROUP BY trang_thai
```

## Còn thiếu thông tin

```dataview
TABLE trang_thai, chua_biet_gi
FROM "04. Resources/People"
WHERE loai = "nguoi" AND length(chua_biet_gi) > 0
```
