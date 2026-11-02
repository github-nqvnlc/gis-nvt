# Ranh Giới Khuôn Viên Nghĩa Trang Nguyễn Văn Tộc

**Địa chỉ:** Giáng Đông, Hòa Xuân, Cẩm Lệ, Đà Nẵng  
**Hệ quy chiếu:** WGS 84 (EPSG:4326)

Hệ thống WebGIS hiển thị ranh giới 7 đỉnh mốc khuôn viên nghĩa trang Nguyễn Văn Tộc, tích hợp trực tiếp trên nền ảnh vệ tinh Google Maps và Esri World Imagery với độ chính xác cao.

---

## 📌 Thông Số Ranh Giới
- **Diện tích khuôn viên:** `378.9 m²` (~ 0,76 sào Trung Bộ / 0,038 ha)
- **Chu vi khuôn viên:** `95.9 m` (7 cạnh khép kín)
- **Thứ tự chu vi:** `1 → 2 → 3 → 4 → 5 → 6 → 7 → 1`
- **Điểm gốc đo đạc (Điểm 1):** `15°58'14.9"N 108°11'26.9"E` (`15.970804, 108.190811`)

---

## 📍 Bảng 7 Điểm Mốc Tọa Độ (WGS84)

| STT | Tên Điểm | Vĩ độ (Lat) | Kinh độ (Lon) | Tọa độ DMS | Chiều Dài Cạnh |
|:---:|:---|:---:|:---:|:---|:---|
| **1** | **Điểm 1 (Gốc)** | `15.970804` | `108.190811` | 15°58'14.9"N 108°11'26.9"E | Điểm gốc đo đạc |
| **2** | **Điểm 2** | `15.970851` | `108.190742` | 15°58'15.1"N 108°11'26.7"E | Cạnh 1 → 2: 9.00 m |
| **3** | **Điểm 3** | `15.970976` | `108.190833` | 15°58'15.5"N 108°11'27.0"E | Cạnh 2 → 3: 17.00 m |
| **4** | **Điểm 4** | `15.970973` | `108.190870` | 15°58'15.5"N 108°11'27.1"E | Cạnh 3 → 4: 4.00 m |
| **5** | **Điểm 5** | `15.970785` | `108.190912` | 15°58'14.8"N 108°11'27.3"E | Cạnh 4 → 5: 21.25 m |
| **6** | **Điểm 6** | `15.970686` | `108.190839` | 15°58'14.5"N 108°11'27.0"E | Cạnh 5 → 6: 13.50 m |
| **7** | **Điểm 7** | `15.970672` | `108.190716` | 15°58'14.4"N 108°11'26.6"E | Cạnh 6 → 7: 13.32 m; 7 → 1: 17.80 m |

---

## 🚀 Cấu Trúc Dự Án
- `index.html`: Bản đồ WebGIS tương tác trực tiếp chạy bằng Leaflet.
- `coordinates.md`: Tài liệu kỹ thuật chi tiết kèm định dạng WKT (Well-Known Text).
- `coordinates.csv`: Bảng dữ liệu tọa độ định dạng CSV.
- `coordinates.geojson`: Dữ liệu không gian định dạng GeoJSON chuẩn GIS.
- `so-do.pdf`: File sơ đồ trích lục đo đạc gốc.
- `wrangler.jsonc`: Cấu hình deploy tự động lên Cloudflare Workers (Static Assets).

