# MCU Datalogger with Built-in 512k EEPROM & RTC Clock

## 📝 Giới thiệu dự án
Dự án thiết kế phần cứng **MCU Datalogger** được thực hiện trên nền tảng **KiCad**. Hệ thống được tối ưu hóa cho các ứng dụng thu thập, giám sát và lưu trữ dữ liệu từ cảm biến hoặc các thiết bị công nghiệp theo thời gian thực (Real-time Data Logging). 

Bo mạch được thiết kế nhỏ gọn, độ nhiễu thấp, sẵn sàng cho các ứng dụng thực tế đòi hỏi độ tin cậy cao trong việc lưu trữ dữ liệu dài hạn.

---

## 🚀 Tính năng nổi bật
* **Bộ nhớ lưu trữ dung lượng lớn:** Tích hợp chip nhớ ngoại vi **EEPROM 512k**, cho phép lưu trữ hàng ngàn bản ghi dữ liệu một cách an toàn. Dữ liệu không bị mất khi hệ thống mất nguồn điện đột ngột (Non-volatile memory).
* **Thời gian thực chính xác:** Tích hợp mạch đồng hồ thời gian thực (**RTC Clock**), tự động gắn nhãn thời gian (Timestamp: Ngày/Tháng/Năm/Giờ/Phút/Giây) chính xác cho từng gói dữ liệu thu thập được.
* **Thiết kế phần cứng chuyên nghiệp:** Sơ đồ nguyên lý (Schematic) và thiết kế mạch in (PCB Layout) được tối ưu hóa hoàn toàn trên phần mềm **KiCad**.

---

## 🛠️ Thành phần linh kiện chính
* **MCU:** ATmega328P-AU
* **Storage:** EEPROM 512k (Giao tiếp I2C)
* **Clock:** RTC Module DS1337S+
* **Nguồn cấp:** Tích hợp mạch bảo vệ và hạ áp ổn định.

---

## 📂 Cấu trúc thư mục dự án
```text
├── Hardware/          # Chứa file thiết kế KiCad (Schematic, PCB, 3D Model)
├── Firmware/          # Mã nguồn chương trình cho MCU (nếu có)
├── Docs/              # Tài liệu kỹ thuật, Datasheet linh kiện
└── README.md          # File giới thiệu dự án