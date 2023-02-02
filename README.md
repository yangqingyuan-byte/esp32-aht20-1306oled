#该作品修改自https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-web-server-arduino-ide/

与它不同的是，我把dht传感器更换为aht20传感器，精度更高。

注意，aht传感器没有用ahtX0库，而是使用DFRobot的库文件，因为后者的获取温湿度函数我能看懂，AHTX0的函数我不知道怎么改进来。

DFRobot的库文件：https://github.com/DFRobot/DFRobot_AHT20
//接线方式：D16,D17分别对应oled屏幕的SCL和SDA
//D22对应bmp280的SCL，D21对应BMP280的SDA
