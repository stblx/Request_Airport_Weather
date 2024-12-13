# Request_Airport_Weather 查询机场天气
使用NOAA的数据，或自行输入数据，解析内容。

Github Pages: 前两个自动阅读，后两个手动阅读

<https://stblx.github.io/Request_Airport_Weather/ZBAAWeatherRequest.html>

<https://stblx.github.io/Request_Airport_Weather/ZBADWeatherRequest.html>

<https://stblx.github.io/Request_Airport_Weather/ZBAAWeatherRequestNonAutoReading.html>

<https://stblx.github.io/Request_Airport_Weather/ZBADWeatherRequestNonAutoReading.html>

<https://stblx.github.io/Request_Airport_Weather/MetarApi.html>

更多讯息，请关注**B站** **三条波浪线**

<https://space.bilibili.com/452359038>

Use NOAA data,  analyze content, shortcut commands for iPhone or Siri to read aloud in Chinese.

For more information, please follow **Bilibili** **三条波浪线**

<https://space.bilibili.com/452359038>

## 使用方法（Usage）
### 直接在输入框中输入
按照提示，可以直接输入机场的四字 **ICAO** 码，或者 **METAR** 、 **TAF** 数据。

**METAR** 和 **TAF** 可以一起输入

注意，一次只能输入**一**条数据。

### 添加网址参数 （Add Website Param）
.\ZBAAAirportWeatherMetar.html?{0}={1}

其中，**{0}** 为任意，程序未设置变量名称；
**{1}** 为机场的 **ICAO** 码，直接加入。

例如：ZBAAAirportWeatherMetar.html?param=ZBAA

**{0}** is any, the program does not set the variable name;
**{1}** is the airport's **ICAO** code, directly join.

For example: ZBAAAirportWeatherMetar.html?param=ZBAA

### 修改文件名称 （Rename File Name）
{0}{1}.html

其中，**{0}** 为机场 **ICAO** 码，直接加入；
**{1}** 为自定义名称，随意添加。

例如：ZBAAAirportWeatherMetar.html

ZBADWeather.html

**{0}** is the airport's **ICAO** code, directly join;
**{1}** is any.

For example: ZBAAAirportWeatherMetar.html

ZBADWeather.html

## 功能（Function）
解析 Metar 报 和 TAF 报的内容，并用**中文**朗读。

注意，**不是**通播，解析方法是作者stblx自己写的代码。

Analyze the contents of Metar and TAF newspapers and read them aloud in Chinese.

Note that **is not** ATIS, the parsing method is the code written by the author called stblx.

## 快捷指令（Apple Shortcuts）
网址（WebSite）：
https://www.icloud.com/shortcuts/a56927e57d2548d9acdac1d1219da9ae
