# Hướng Dẫn Cài Đặt và Chạy Dự Án 📌

## 1. Cài Đặt Dự Án

Trước tiên, hãy đảm bảo bạn đã cài đặt **Node.js** và **MongoDB** trên máy tính của mình.

### Bước 1: Clone dự án

```sh
git clone https://github.com/BuiHao0305/BookDex.git
```

### Bước 2: Cài đặt các package cần thiết

```sh
cd BOOKDEX
```

### Bước 3: Cấu Hình Môi Trường

Tạo file `.env` trong thư mục ngang với packgae.json và thêm thông tin sau:

`MONGO_URI=mongodb://localhost:27017/BookWalkerDB`

### Bước 3: Chạy Dự Án

Chạy Cả Backend & Frontend

```sh
npm run dev
```

hoặc chạy riêng frontend

```sh
cd frontend
```

```sh
npm run frontend
```

hoặc chạy riêng backend

```sh
cd backend
```

```sh
npm run backend
```

## 2. Yêu Cầu

phải có
`nodejs` và `mongodb`
`mongodb` đang được active
