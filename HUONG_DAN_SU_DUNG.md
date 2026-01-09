# Hướng Dẫn Sử Dụng Hệ Thống Quản Lý Admin BOE

## Giới Thiệu

BOE Admin là hệ thống quản lý toàn diện cho cửa hàng bán hàng trực tuyến. Nó cung cấp các công cụ để quản lý sản phẩm, đơn hàng, khách hàng, và nhiều khía cạnh khác của kinh doanh.

**URL**: https://admin.dev.alino.vn
**Tài khoản demo**: admin@boevn.vn

---

## Mục Lục

1. [Đăng Nhập](#đăng-nhập)
2. [Bảng Điều Khiển Chính](#bảng-điều-khiển-chính)
3. [Quản Lý Sản Phẩm](#quản-lý-sản-phẩm)
4. [Quản Lý Danh Mục](#quản-lý-danh-mục)
5. [Quản Lý Đơn Hàng](#quản-lý-đơn-hàng)
6. [Quản Lý Khách Hàng](#quản-lý-khách-hàng)
7. [Quản Lý Bài Viết](#quản-lý-bài-viết)
8. [Quản Lý Trang Thông Tin](#quản-lý-trang-thông-tin)
9. [Các Tính Năng Khác](#các-tính-năng-khác)

---

## Đăng Nhập

### Bước 1: Truy Cập Trang Đăng Nhập
- Mở trình duyệt web và truy cập: **https://admin.dev.alino.vn**
- Bạn sẽ được chuyển hướng tới trang đăng nhập nếu chưa xác thực

### Bước 2: Nhập Thông Tin Tài Khoản
1. Nhập **email** (ví dụ: admin@boevn.vn)
2. Nhập **mật khẩu**
3. Nhấp nút **"Đăng Nhập"**

### Bước 3: Truy Cập Hệ Thống
Sau khi đăng nhập thành công, bạn sẽ được đưa tới **Bảng Điều Khiển Chính (Dashboard)**.

---

## Bảng Điều Khiển Chính

### Giao Diện Chính
- **Thanh Điều Hướng Bên Trái**: Chứa menu các mục chính
- **Tiêu Đề Trang**: Hiển thị tên trang hiện tại
- **Nút Hành Động**: Nút thêm mới hoặc chức năng liên quan

### Menu Chính
```
📊 Dashboard (Bảng Điều Khiển)
🛍️  Sản Phẩm (Products)
📁 Danh Mục (Categories)
📦 Đơn Hàng (Orders)
👥 Khách Hàng (Customers)
📄 Bài Viết (Articles)
📋 Chính Sách & Thông Tin (Info Pages)
💬 Liên Hệ từ Khách Hàng (Contacts)
💰 Quản Lý Giá (Price Management)
🛣️  Kênh Bán (Channels)
🔗 SP Theo Kênh (Channel Products)
💳 Thanh Toán (Payments)
🚚 Giao Hàng (Shipments)
📦 Kho Hàng (Inventory)
🎟️  Mã Giảm Giá (Coupons)
⭐ Đánh Giá (Reviews)
🚪 Đăng Xuất (Logout)
```

---

## Quản Lý Sản Phẩm

### Xem Danh Sách Sản Phẩm

1. Nhấp vào **"Sản Phẩm"** trong menu bên trái
2. Bạn sẽ thấy danh sách tất cả các sản phẩm với thông tin:
   - **Hình ảnh sản phẩm**
   - **Tên sản phẩm** (và tên tiếng Anh nếu có)
   - **Giá bán**
   - **Tồn kho** (số lượng)
   - **Trạng thái** (Đã xuất bản)
   - **Tác vụ** (Sửa, Xóa)

![Danh sách sản phẩm](./docs/screenshots/Screenshot%202026-01-09%20073445.png)

### Tìm Kiếm Sản Phẩm

- Sử dụng ô **"Tìm kiếm sản phẩm"** ở phía trên
- Nhập tên sản phẩm hoặc slug
- Kết quả tìm kiếm sẽ cập nhật tự động

### Thêm Sản Phẩm Mới

#### Bước 1: Mở Form Thêm
- Nhấp nút **"+ Thêm sản phẩm"** (màu xanh lam)

![Form thêm sản phẩm](./docs/screenshots/Screenshot%202026-01-09%20073502.png)

#### Bước 2: Điền Thông Tin Cơ Bản
- **Tên sản phẩm**: Nhập tên sản phẩm (bắt buộc)
- **Slug**: ID duy nhất của sản phẩm trong URL (tự động sinh từ tên nếu để trống)
- **Danh mục**: Chọn từ dropdown (bắt buộc)
- **Trạng thái**: Chọn "Xuất bản" hoặc "Nháp" (mặc định: Xuất bản)

#### Bước 3: Thêm Hình Ảnh
- **Ảnh thumbnail**:
  - Nhập URL hoặc nhấp nút "Upload" để tải lên
  - Hình ảnh nhỏ đại diện cho sản phẩm

- **Ảnh full**:
  - Nhập URL hoặc nhấp nút "Upload" để tải lên
  - Hình ảnh lớn cho trang chi tiết sản phẩm

- **Thư viện ảnh & video**:
  - Kéo thả hoặc nhấp để tải lên nhiều ảnh/video
  - Hỗ trợ: JPG, PNG, GIF, WEBP, MP4, WEBM (tối đa 10 file)
  - Hoặc nhập URL từng ảnh/video

#### Bước 4: Mô Tả Sản Phẩm
- **Mô tả**: Nhập mô tả chi tiết sản phẩm
- Sử dụng thanh công cụ Markdown:
  - **B** = In đậm
  - **I** = In nghiêng
  - **H1, H2, H3** = Tiêu đề
  - **• List** = Danh sách
  - **Link** = Thêm liên kết
  - **Preview** = Xem trước

#### Bước 5: Thêm Biến Thể (Variants)
Biến thể là các phiên bản khác nhau của sản phẩm (ví dụ: kích cỡ, màu sắc)

![Biến thể sản phẩm](./docs/screenshots/Screenshot%202026-01-09%20073546.png)

1. Trong bảng **"Biến thể sản phẩm"**:
   - Xem các biến thể hiện có (nếu có)
   - Các cột: **Tên**, **SKU**, **Giá**, **Tồn kho**, **Hành động**

2. Để thêm biến thể mới:
   - Nhấp vào **"+ Thêm variant mới"** (link xanh)

   ![Form thêm variant](./docs/screenshots/Screenshot%202026-01-09%20073515.png)

   - Điền thông tin:
     - **Tên variant**: Ví dụ: "VD: 50ml, Màu đỏ"
     - **SKU**: Mã SKU duy nhất (ví dụ: SKU-001)
     - **Giá bán**: Giá bán lẻ (VND)
     - **Giá so sánh**: Giá gốc hoặc giá so sánh (optional)
     - **Giá vốn**: Giá bán buôn hoặc chi phí (optional)
     - **Tồn kho**: Số lượng trong kho
     - **Cân nặng (grams)**: Khối lượng nếu cần (optional)
     - **Cho phép đặt hàng khi hết hàng**: Checkbox cho phép đặt khi hết
   - Nhấp **"Thêm variant"** để xác nhận

3. Để chỉnh sửa variant:
   - Nhấp **"Sửa"** ở hàng tương ứng
   - Cập nhật thông tin
   - Nhấp **"Cập nhật"**

#### Bước 6: Lưu Sản Phẩm
- Nhấp nút **"Cập nhật"** (xanh dương, góc dưới phải)
- Hoặc nhấp **"Hủy"** để hủy bỏ

### Sửa Sản Phẩm

1. Tìm sản phẩm trong danh sách
2. Nhấp nút **"Sửa"** hoặc nhấp trên tên sản phẩm
3. Cập nhật thông tin cần thiết
4. Nhấp **"Cập nhật"** để lưu

### Nhập Sản Phẩm Hàng Loạt (Import)

1. Nhấp nút **"📥 Import JSON"** trên trang sản phẩm
2. Chuẩn bị file JSON với cấu trúc:
```json
[
  {
    "name": "Tên sản phẩm",
    "slug": "ten-san-pham",
    "category": "Danh mục",
    "status": "Xuất bản",
    "price": 1000000,
    "stock": 100,
    "image": "url-hinh-anh",
    "description": "Mô tả sản phẩm"
  }
]
```
3. Nhấp nút **"Import"** để nhập

---

## Quản Lý Danh Mục

### Xem Danh Sách Danh Mục

1. Nhấp **"Danh Mục"** trong menu
2. Xem danh sách các danh mục với cột:
   - **Tên danh mục**
   - **Slug**
   - **Số lượng sản phẩm**
   - **Trạng thái**
   - **Tác vụ** (Sửa, Xóa)

![Danh sách danh mục](./docs/screenshots/Screenshot%202026-01-09%20073611.png)

### Thêm Danh Mục Mới

1. Nhấp nút **"+ Thêm danh mục"**
2. Điền thông tin:
   - **Tên danh mục** (bắt buộc)
   - **Slug** (tự động từ tên, nếu cần bạn có thể chỉnh)
   - **Mô tả** (tuỳ chọn)
3. Nhấp **"Thêm"** để lưu

### Sửa Danh Mục

1. Nhấp **"Sửa"** ở hàng danh mục
2. Cập nhật thông tin
3. Nhấp **"Cập nhật"** để lưu

---

## Quản Lý Đơn Hàng

### Xem Danh Sách Đơn Hàng

1. Nhấp **"Đơn Hàng"** trong menu
2. Xem danh sách đơn hàng với:
   - **Mã đơn hàng** (ví dụ: #1)
   - **Tên khách hàng**
   - **Email khách hàng**
   - **Tổng tiền**
   - **Trạng thái** (Đã xác nhận, Đang xử lý, Đang giao, Đã giao, Đã hủy)
   - **Ngày tạo**

![Danh sách đơn hàng](./docs/screenshots/Screenshot%202026-01-09%20073628.png)

### Lọc Đơn Hàng

- Sử dụng dropdown **"Tất cả trạng thái"** để lọc theo trạng thái

### Xem Chi Tiết Đơn Hàng

1. Nhấp vào mã đơn hàng hoặc tên khách hàng
2. Bạn sẽ thấy chi tiết đầy đủ:

![Chi tiết đơn hàng](./docs/screenshots/Screenshot%202026-01-09%20073636.png)

#### Thông Tin Giao Hàng
- **Tên khách hàng**
- **Số điện thoại**
- **Địa chỉ**
- **Thành phố**

#### Cập Nhật Trạng Thái
- Các nút trạng thái:
  - 🟢 **Đã xác nhận** - Đơn hàng được xác nhận
  - 🟡 **Đang xử lý** - Đang chuẩn bị hàng
  - 🟠 **Đang giao** - Đã gửi cho đơn vị vận chuyển
  - 🟢 **Đã giao** - Khách hàng đã nhận hàng
  - 🔴 **Đã hủy** - Hủy đơn hàng

#### Sản Phẩm Đặt Hàng
- Bảng danh sách sản phẩm trong đơn với:
  - **Hình ảnh**
  - **Tên sản phẩm**
  - **SKU**
  - **Giá**
  - **Số lượng**
  - **Tổng cộng**

#### Tóm Tắt Đơn Hàng
- **Tạm tính**: Tổng tiền sản phẩm
- **Giảm giá**: Tiền giảm giá (nếu có)
- **Phí ship**: Chi phí vận chuyển
- **Tổng cộng**: Tổng tiền cuối cùng

---

## Quản Lý Khách Hàng

### Xem Danh Sách Khách Hàng

1. Nhấp **"Khách Hàng"** trong menu
2. Xem danh sách khách hàng với:
   - **Tên khách hàng**
   - **Email**
   - **Số điện thoại**
   - **Xác thực**: Trạng thái (Chưa xác thực, Đã xác thực)
   - **Ngày tạo**
   - **Tác vụ** (Sửa, Xóa)

![Danh sách khách hàng](./docs/screenshots/Screenshot%202026-01-09%20073650.png)

### Tìm Kiếm Khách Hàng

- Sử dụng ô tìm kiếm **"Tìm kiếm theo email, tên..."**
- Nhập thông tin khách hàng cần tìm

### Xem Chi Tiết Khách Hàng

1. Nhấp **"Sửa"** hoặc tên khách hàng
2. Xem thông tin chi tiết:
   - **Tên khách hàng**
   - **Email**
   - **Số điện thoại**
   - **Địa chỉ**
   - **Thành phố**
   - **Trạng thái xác thực**

---

## Quản Lý Bài Viết

### Xem Danh Sách Bài Viết

1. Nhấp **"Bài Viết"** trong menu
2. Xem danh sách bài viết với:
   - **Tiêu đề**
   - **Tác giả**
   - **Trạng thái**
   - **Ngày tạo**
   - **Tác vụ** (Sửa, Xóa)

![Danh sách bài viết](./docs/screenshots/Screenshot%202026-01-09%20073701.png)

### Thêm Bài Viết Mới

1. Nhấp nút **"+ Thêm bài viết"**
2. Điền thông tin:
   - **Tiêu đề**: Tiêu đề bài viết (bắt buộc)
   - **Slug**: URL slug (tự động từ tiêu đề)
   - **Tác giả**: Tên người viết
   - **Trích dẫn**: Đoạn trích ngắn
   - **Nội dung**: Nội dung chi tiết bài viết
   - **Hình ảnh thumbnail**: Tải lên hoặc nhập URL

![Form thêm bài viết](./docs/screenshots/Screenshot%202026-01-09%20073709.png)

3. Nhấp **"Thêm"** để lưu

### Sửa Bài Viết

1. Nhấp **"Sửa"** ở hàng bài viết
2. Cập nhật thông tin cần thiết
3. Nhấp **"Cập nhật"** để lưu

---

## Quản Lý Trang Thông Tin

### Xem Danh Sách Trang

1. Nhấp **"Chính Sách & Thông Tin"** trong menu
2. Xem danh sách các trang thông tin

![Danh sách trang thông tin](./docs/screenshots/Screenshot%202026-01-09%20073721.png)

### Thêm Trang Thông Tin Mới

1. Nhấp nút **"+ Thêm bài viết"**
2. Điền thông tin:
   - **Tiêu đề**: Tiêu đề trang (bắt buộc)
   - **Slug**: URL slug
   - **Tác giả**: Người tạo trang
   - **Trích dẫn**: Mô tả ngắn
   - **Nội dung**: Nội dung trang

#### Nội Dung Hỗ Trợ Markdown & HTML

Bạn có thể sử dụng cả **Markdown** và **HTML**:

**Tab Chính Sửa** (Markdown):
- Định dạng nội dung bằng Markdown
- **B** = In đậm
- **I** = In nghiêng
- Tiêu đề, danh sách, liên kết, v.v.

**Tab Xem Trước** (HTML):
- Nhập HTML trực tiếp

![Form sửa trang thông tin với HTML support](./docs/screenshots/Screenshot%202026-01-09%20073729.png)

- Ví dụ:
```html
<h2>Tiêu đề</h2>
<p>Đoạn văn</p>
<img src='url' alt='mô tả'>
```

### HTML Tips (Gợi ý)

Hỗ trợ các tag HTML phổ biến:
- `<h2>`, `<h3>`, `<h4>` - Tiêu đề
- `<p>` - Đoạn văn
- `<img src='url' alt='mô tả'>` - Hình ảnh
- `<a href='url'>` - Liên kết
- `<ul>`, `<ol>`, `<li>` - Danh sách

---

## Các Tính Năng Khác

### Quản Lý Liên Hệ Khách Hàng

1. Nhấp **"Liên Hệ từ Khách Hàng"** trong menu
2. Xem danh sách tin nhắn từ khách hàng
3. Các cột hiển thị:
   - **Tên khách hàng**
   - **Email**
   - **Số điện thoại**
   - **Xác thực**: Trạng thái (Chưa xác thực)
   - **Ngày tạo**
   - **Tác vụ** (Sửa)

### Quản Lý Giá

1. Nhấp **"Quản Lý Giá"** để quản lý giá sản phẩm
2. Cập nhật giá hàng loạt nếu cần

### Quản Lý Kênh Bán

1. Nhấp **"Kênh Bán"** để xem các kênh bán hàng
2. Cấu hình kênh bán (Shopee, Tiktok, v.v.)

![Quản lý sản phẩm theo kênh](./docs/screenshots/Screenshot%202026-01-09%20073749.png)

![Quản lý sản phẩm theo kênh chi tiết](./docs/screenshots/Screenshot%202026-01-09%20073801.png)

### Quản Lý Thanh Toán

1. Nhấp **"Thanh Toán"** để xem lịch sử thanh toán
2. Quản lý các phương thức thanh toán

### Quản Lý Giao Hàng

1. Nhấp **"Giao Hàng"** để quản lý đơn vị vận chuyển
2. Xem lịch sử giao hàng

### Quản Lý Kho Hàng

1. Nhấp **"Kho Hàng"** để theo dõi tồn kho
2. Cập nhật số lượng sản phẩm trong kho

### Quản Lý Mã Giảm Giá

1. Nhấp **"Mã Giảm Giá"** trong menu
2. Xem danh sách coupon/mã giảm giá
3. Thêm mã giảm mới nếu cần

### Quản Lý Đánh Giá

1. Nhấp **"Đánh Giá"** để xem đánh giá từ khách hàng
2. Quản lý các bình luận và đánh giá sản phẩm

---

## Đăng Xuất

1. Nhấp **"🚪 Đăng Xuất"** ở cuối menu bên trái
2. Bạn sẽ được chuyển hướng tới trang đăng nhập

---

## Mẹo & Lưu Ý

### Lưu Ý Quan Trọng

1. **Slug**: Slug là ID duy nhất trong URL. Không được trùng lặp và nên chứa các ký tự: a-z, 0-9, gạch ngang
2. **Hình ảnh**: Tải lên từng hình ảnh hoặc nhập URL. Định dạng hỗ trợ: JPG, PNG, GIF, WEBP
3. **Giá sản phẩm**: Luôn nhập giá bán (giá so sánh và giá vốn là tuỳ chọn)
4. **Trạng thái**: Chọn "Xuất bản" để sản phẩm xuất hiện trên website, "Nháp" để ẩn

### Mẹo Nhanh

- **Tìm kiếm nhanh**: Sử dụng ô tìm kiếm để nhanh chóng tìm sản phẩm hoặc khách hàng
- **Lọc dữ liệu**: Sử dụng dropdown để lọc theo trạng thái hoặc danh mục
- **Markdown**: Sử dụng định dạng Markdown để tạo nội dung đẹp mắt
- **Variant**: Tạo variant để quản lý các phiên bản khác nhau của sản phẩm (size, màu, v.v.)

---

## Hỗ Trợ

Nếu bạn gặp vấn đề hoặc cần trợ giúp:
- Liên hệ với đội hỗ trợ kỹ thuật
- Kiểm tra lại thông tin đầu vào
- Xóa cache trình duyệt nếu gặp lỗi hiển thị

---

*Tài liệu này được cập nhật lần cuối vào tháng 1 năm 2026*
