# OpenKey Memory

## Business/Features
- Cập nhật hỗ trợ phiên bản hệ điều hành macOS (minimum deployment target).

## Technical/Architecture
- `MACOSX_DEPLOYMENT_TARGET` đã được cập nhật từ `10.10` lên `10.13` trong cả hai cấu hình (Debug và Release) của `OpenKey.xcodeproj`. Việc này khắc phục lỗi biên dịch `missing required architecture arm64 in file... libarclite_macosx.a` và cảnh báo phiên bản deployment target không được hỗ trợ. 
