注册和风天气并获取API

https://id.qweather.com/#/register

配置内容如下
```
sensor:
  - platform: HeWeather
    city: auto_ip 或者 填写城市名称 eg（北京，beijing）
    appkey: 你的密钥
    options:
      - fl
      - tmp
      - cond_txt
      - wind_spd
      - hum
      - pcpn
      - pres
      - vis
      - wind_sc
      - aqi
      - main
      - qlty
      - pm10
      - pm25
      - comf
      - cw
      - drsg
      - flu
      - sport
      - trav
      - uv
      - wind_dir
      - tmp_max
      - tmp_min
      - pop
```
