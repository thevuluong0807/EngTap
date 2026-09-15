# EngTap

> Game luyện gõ và phát âm tiếng Anh: các từ rơi xuống như giọt mưa, người chơi phải nhập đúng trước khi chúng chạm đáy.

## Chơi trực tiếp

[Mở EngTap trên GitHub Pages](https://thevuluong0807.github.io/EngTap/)

## Tính năng

- Từ rơi liên tục ở vị trí ngẫu nhiên với tốc độ ổn định.
- Ba chế độ:
  - **Nghe & gõ**: nghe phát âm và nhập từ.
  - **Gõ theo nghĩa**: xem nghĩa tiếng Việt rồi nhập từ.
  - **Gõ chính tả**: toàn bộ chữ cái hiển thị màu xám; đúng chuyển xanh, sai rung đỏ và phải nhập lại.
- Level B1, B2, C1, C2, Tăng dần và Hỗn loạn.
- Gợi ý ký tự sau mỗi lần sai.
- Tia bắn từ ống tre tới đúng ký tự đang nhập, kèm hiệu ứng và âm thanh bong bóng nước vỡ.
- Popup cài đặt: âm lượng phát âm, tạm dừng và kết thúc phiên chơi.
- Responsive cho màn hình desktop, tablet và điện thoại.
- Kho từ vựng trong `words-db.js`.

## Chạy local

Mở trực tiếp `index.html` bằng trình duyệt. Không cần cài dependency hoặc chạy server.

## Cấu trúc

```text
index.html   giao diện, CSS và logic game
words-db.js   database từ vựng và nghĩa tiếng Việt
```

## Công nghệ

HTML, CSS và JavaScript thuần. Phát âm Cambridge được lấy qua proxy khi có thể; trình duyệt sẽ fallback sang Web Speech API.

## License

> Dự án cá nhân dùng cho mục đích học tập.
