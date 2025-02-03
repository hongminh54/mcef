<p align="center">
  <img src="https://github.com/CinemaMod/mcef/assets/30220598/938896d7-2589-49df-8f82-29266c64dfb7" alt="MCEF Logo" style="width:66px;height:66px;">
</p>

# MCEF (Minecraft Chromium Embedded Framework)
MCEF (Minecraft Chromium Embedded Framework): Một bản fork của mod và thư viện MCEF cho phép thêm trình duyệt web Chromium vào Minecraft.

MCEF dựa trên java-cef (Java Chromium Embedded Framework), bản thân java-cef lại dựa trên CEF (Chromium Embedded Framework), và CEF dựa trên Chromium. MCEF ban đầu được tạo bởi montoyo. Sau đó được viết lại bởi CinemaMod Group.

MCEF có hệ thống tải xuống để tải xuống các tệp nhị phân java-cef & CEF cần thiết cho trình duyệt Chromium. Việc này yêu cầu kết nối với https://mcef-download.cinemamod.com.

Phiên bản Chromium hiện tại:: `116.0.5845.190`

## Các nền tảng được hỗ trợ
- Windows 10/11 (x86_64, arm64)*
- macOS 11 or greater (Intel, Apple Silicon)
- GNU Linux glibc 2.31 or greater (x86_64, arm64)**

*Một số phần mềm diệt virus có thể ngăn chặn MCEF khởi tạo. Bạn có thể cần phải vô hiệu hóa phần mềm diệt virus hoặc thêm danh sách trắng cho các tệp mod của MCEF để MCEF hoạt động chính xác.

*Không hoạt động đối với Android.

### Sử dụng MCEF trong dự án của bạn
```
repositories {
    maven { url 'https://jitpack.io' }
}
```
```
dependencies {
    modImplementation 'com.github.CCBlueX:mcef:1.1.5-1.21.1'
}
```

### Dependencies Khác
```
dependencies {
    modImplementation 'com.github.hongminh54:mcef:1.21.4-SNAPSHOT'
}
```

### Xây dựng & Sửa đổi MCEF
Sau khi sao chép kho lưu trữ này, bạn cần sao chép git submodule java-cef. Có một tác vụ gradle cho việc này: `./gradlew cloneJcef`.

## Phân cấp Fork
- [CCBlueX/mcef](https://github.com/CCBlueX/mcef)
- [CinemaMod/mcef](https://github.com/CinemaMod/mcef)
- [montoyo/mcef](https://github.com/montoyo/mcef)

## Credit Source: 
- CCBlueX
