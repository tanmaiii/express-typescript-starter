# Hướng dẫn chạy chương trình

## Yêu cầu

- Node.js phiên bản >= 14.x
- npm hoặc yarn

## Cách chạy

1. **Clone repository**:

```bash
git clone https://github.com/tanmaiii/express-typescript-starter
cd express-ts-starter
```

2. **Cài đặt dependencies**:

```bash
npm install
```

hoặc nếu sử dụng yarn:

```bash
yarn install
```

3. **Cài đặt các biến môi trường**:
   Tạo file `.env.development.local` ở môi trường dev trong thư mục gốc của dự án và cấu hình các biến môi trường cần thiết.

   ```
    # PORT
    PORT = 3000

    # DATABASE

    DB_USER = root
    DB_PASSWORD = password
    DB_HOST = localhost
    DB_PORT = 3306
    DB_DATABASE = dev

    # TOKEN

    SECRET_KEY = secretKey

    # LOG

    LOG_FORMAT = dev
    LOG_DIR = ../logs

    # CORS

    ORIGIN = \*
    CREDENTIALS = true
   ```

4. **Chạy chương trình**:

```bash
npm run dev
```

hoặc với yarn:

```bash
yarn dev
```

5. **Truy cập ứng dụng**:
   Mở trình duyệt và truy cập [http://localhost:3000](http://localhost:3000).

## Scripts khác

- **Build dự án**:

  ```bash
  npm run build
  ```

  hoặc:

  ```bash
  yarn build
  ```

- **Chạy kiểm tra lint**:

  ```bash
  npm run lint
  ```

  hoặc:

  ```bash
  yarn lint
  ```

- **Chạy test**:
  ```bash
  npm test
  ```
  hoặc:
  ```bash
  yarn test
  ```
