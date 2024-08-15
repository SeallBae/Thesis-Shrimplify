============= THESIS SETUP =============
by TRAN-NGUYEN-HOANG-HAI

1. Front-end
	- Open fe folder in Code folder
	- Run command "npm start"

2. Back-end
	- Open be folder in Code folder
	- Run command "npm start"

3. MySQL
	- Open Code/MySQL queries folder
	- Execute "Query"

4. Arduino
	- Open Code/shrimp-app/Arduino/ds18b20/ds18b20.ino then upload (IoT connecting is needed)
	- Open Code/shrimp-app/Arduino/esp8266/esp8266.ino
	- Change "init_ssid" and "init_password" to connected wifi name and password
	- Select File/Preferences
	- Fill in "Additional boards manager URLs" with "https://arduino.esp8266.com/stable/package_esp8266com_index.json"
	- Select Tools/Boards/esp8266/NodeMCU 0.9(ESP-12 Module)
	- Upload (IoT connecting is needed)