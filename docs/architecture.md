\# Kiến trúc đề xuất

\~\~\~mermaid

flowchart LR

Sensor\[Sensor] --> Gateway\[Gateway]

Gateway --> Cloud\[Cloud / Server]

Cloud --> App\[Web or Mobile App]

\~\~\~

Luồng dữ liệu: Sensor thu thập dữ liệu, Gateway chuyển tiếp, Cloud lưu trữ/xử lý,

App hiển thị và điều khiển.

