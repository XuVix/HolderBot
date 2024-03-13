

```
{
  "tag": "Holderbot",
  "listen": "0.0.0.0",
  "port": 2222,
  "protocol": "shadowsocks",
  "settings": {
    "clients": [],
    "network": "tcp,udp"
  }
}
```

```
cd && cd .. && rm -f holderbot.sh* || true && sudo apt install && sudo apt-get install libjpeg-dev && wget https://raw.githubusercontent.com/Elecx-ir/holderbot/main/holderbot.sh && chmod +x holderbot.sh && ./holderbot.sh
```

وارد فایل qr.py داخل پوشه‌ی Functions بشید ، سپس به سطر 9 فایل بروید :
```
qr_img = qr.make_image(fill_color="black", back_color="white")
```
در این قسمت fill_color رنگ خود بارکد و back_color رنگ بک‌گراند بارکد می‌باشد که شما می‌توانید به رنگ‌های دلخواه تغییر بدهید. مثل :
```
qr_img = qr.make_image(fill_color="pink", back_color="white")
```
```
qr_img = qr.make_image(fill_color="red", back_color="white") 
```
```
qr_img = qr.make_image(fill_color="white", back_color="blue")
```
