# smartcarC3supermini
Làm xe tự chạy tránh vật chống rơi bằng mạch esp32C3supermini + mạch drv8833 + cảm biến Laser VL53L0X +  Cảm biến hồng ngoại TCRT5000 + motor
có code cùng bẳng sơ đồ hàn chân các linh kiện, nếu k chỉnh sửa được code thì có file .bin để các bạn nạp trực tiếp online trên web: https://web.esphome.io/.
Phải hàn J1: Trên mạch DRV8833 có chỗ J1, bạn phải lấy thiếc hàn chập nó lại thì board mới chạy ở chế độ 3.3V. Quên là motor không quay đâu.
TCRT5000 - Chống rơi: Phải để cách mặt bàn 3-5mm thôi. Cao quá là nó tưởng đang rơi nên cứ lùi mãi.
VL53L0X - Tránh vật: Mặt cảm biến phải chĩa ra phía trước 100%, đừng để nó chĩa xuống đất hay lên trời. Dán cao hơn mặt bàn 1 chút, đừng để sát đất bụi nó che mắt.
Về Motor: OUT1/2 -> Motor Trái, OUT3/4 -> Motor Phải: khi chạy nếu thấy 1 bánh quay ngược thì chỉ cần đảo 2 dây của motor đó trên DRV8833 là xong.
