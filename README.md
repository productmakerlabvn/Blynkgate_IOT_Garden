
# BlynkGate IoT Garden

**BlynkGate IoT Garden** là một dự án sử dụng **BlynkGate** để quản lý và điều khiển các cảm biến, thiết bị trong hệ thống vườn IoT. Dự án tập trung vào việc giám sát nhiệt độ, độ ẩm không khí, độ ẩm đất, ánh sáng và tự động tưới nước cho cây trồng. Dữ liệu từ các cảm biến được gửi lên **Blynk Cloud** để theo dõi từ xa và điều khiển các thiết bị như máy bơm nước qua ứng dụng **Blynk**.

## Tính năng chính:
- **Giám sát nhiệt độ và độ ẩm không khí**: Sử dụng cảm biến để theo dõi điều kiện nhiệt độ và độ ẩm không khí trong vườn.
- **Giám sát độ ẩm đất**: Sử dụng cảm biến độ ẩm đất để đo độ ẩm trong đất, giúp điều chỉnh việc tưới tiêu phù hợp.
- **Cảm biến ánh sáng**: Đo cường độ ánh sáng để bảo vệ cây trồng khỏi điều kiện ánh sáng quá mức hoặc thiếu ánh sáng.
- **Tự động tưới nước**: Điều khiển máy bơm tự động dựa trên độ ẩm đất, giúp tiết kiệm nước và đảm bảo cây trồng luôn đủ độ ẩm.
- **Điều khiển từ xa qua ứng dụng Blynk**: Người dùng có thể theo dõi và điều khiển hệ thống qua điện thoại từ bất kỳ đâu thông qua ứng dụng Blynk.

## Các bài học

### Bài 1: Sử dụng cảm biến nhiệt độ và độ ẩm
- Dự án bắt đầu với việc đo nhiệt độ và độ ẩm không khí bằng cảm biến DHT11. Dữ liệu này được gửi lên Blynk để người dùng có thể theo dõi từ xa qua ứng dụng.

### Bài 2: Thêm cảm biến ánh sáng và độ ẩm đất
- Sau khi có dữ liệu từ nhiệt độ và độ ẩm không khí, dự án được mở rộng bằng cách thêm cảm biến ánh sáng và cảm biến độ ẩm đất để theo dõi điều kiện ánh sáng và độ ẩm trong đất. Điều này giúp tối ưu hóa việc chăm sóc cây trồng trong các điều kiện môi trường khác nhau.

### Bài 3: Thêm máy bơm và màn hình LCD
- Ở bài này, chúng ta bổ sung máy bơm để tưới nước tự động dựa trên độ ẩm đất. Ngoài ra, một màn hình LCD được thêm vào để hiển thị thông tin trực tiếp như nhiệt độ, độ ẩm không khí và đất ngay tại chỗ, giúp theo dõi dễ dàng hơn mà không cần phải mở ứng dụng Blynk.

## Phần cứng yêu cầu:
- **Module BlynkGate**
- **Arduino Uno**
- **Cảm biến nhiệt độ và độ ẩm không khí**
- **Cảm biến độ ẩm đất**
- **Cảm biến ánh sáng**
- **Máy bơm nước và relay**
- **Màn hình LCD1602**

Dự án này thích hợp cho các hệ thống nông nghiệp thông minh, giúp tự động hóa và giám sát môi trường vườn từ xa dễ dàng hơn, đặc biệt cho việc duy trì nhiệt độ, độ ẩm không khí, độ ẩm đất và điều kiện ánh sáng lý tưởng cho cây trồng.
