# Website San khau Kich 5B - ban mau 1.0

React + Vite, deploy qua GitHub -> Netlify.

## Chay tren may

1. Cai Node.js LTS.
2. Mo terminal tai thu muc du an.
3. Chay `npm install`.
4. Chay `npm run dev` va mo dia chi duoc hien thi.
5. Kiem tra build bang `npm run build`.

## Dua len GitHub

1. Vao https://github.com/new va tao repository `kich5b-website`.
2. Tai GitHub chon `uploading an existing file`, tai len TOAN BO NOI DUNG cua thu muc du an (khong tai len node_modules).
3. Commit cac file vao nhanh main.

## Dua len Netlify

1. Vao https://app.netlify.com/ -> Add new project -> Import an existing project.
2. Chon GitHub va repository `kich5b-website`.
3. Build command: `npm run build`; Publish directory: `dist`.
4. Chon Deploy. Moi lan push len main, Netlify se tu build lai.

## Gioi han quan trong

- Cac vo dien, ngay, gia, hinh anh dang la DU LIEU MAU, khong phai thong tin chinh thuc cua 5B.
- Anh tu Unsplash la anh minh hoa; can thay bang anh duoc cap phep truoc khi cong bo.
- Trang / Quan tri hien tai la demo giao dien, KHONG co dang nhap, khong co co so du lieu, khong duoc su dung de quan ly that.
- Form dat ve chi hien thi xac nhan mau, KHONG gui du lieu va KHONG thu tien.
- De van hanh that can them backend, xac thuc va phan quyen, luu don dat ve, quan ly ghe va thanh toan an toan.
