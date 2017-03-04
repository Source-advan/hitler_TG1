# [SCORPIONTGBOT](http://telegram.me/SCORPIONTGBOT)

# برای نصب کد زیر را در ترمینال وارد کنید
```
git clone https://github.com/Source-advan/hitler_TG1.git && cd hitler_TG1 && chmod +x launch.sh && ./launch.sh install && ./launch.sh
```
# سپس شماره خود را با کد کشور مورد نظر وارد کنید

# >> آموزش فعال سازی اتولانچ
# کدهای زیر را بترتیب وارد کنید
```
cd hitler_TG1 && sed -i "s/root/$(whoami)/g" etc/pika.conf; sed -i "s_telegrambotpath_$(pwd)_g" etc/pika.conf && sudo cp etc/pika.conf /etc/init/ && chmod 777 pika && nohup ./pika &>/dev/null &
```
```
sudo start pika
```
```
screen ./pika
```
# در صورت خاموش شدن ربات برای لانچ
```
cd hitler_TG1

screen ./pika
```

# >> آموزش زدن لانچر
# بترتیب
```
cd hitler_TG1

tmux new-session -s script "bash steady.sh -t"
```
# درصورت خاموش شدن برای لانچ
```
cd hitler_TG1

killall tmux

tmux new-session -s script "bash steady.sh -t"
```
# برای یوزرغیر روت لانچر توصیه میشه 

# آموزش های بیشتر در کانال ما

# برای ورود به کانال کلیک کن

# [ورود به کانال](http://telegram.me/SCORPIONTGBOT)
# نوشته شده توسط:@Wow_heh
# [@Wow_heh](http://telegram.me/Wow_heh) 
