# Request_Airport_Weather 查询机场天气
使用NOAA的数据，解析内容，适用于 iPhone 的快捷指令或 Siri 的中文朗读。

更多讯息，请关注**B站** **三条波浪线**

https://space.bilibili.com/452359038

Use NOAA data,  analyze content, shortcut commands for iPhone or Siri to read aloud in Chinese.

For more information, please follow **Bilibili** **三条波浪线**

https://space.bilibili.com/452359038

## 使用方法（Usage）
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

在 iPhone/iPad 上，在 文件应用（Files）里，进入 **Html Viewer** 文件夹，长摁文件，点击“修改名称”，将前四位改成想要查询机场的 **ICAO** 码，点击确定保存即可。

例如：ZBAAAirportWeatherMetar.html

ZBADWeather.html

**{0}** is the airport's **ICAO** code, directly join;
**{1}** is any.

On iPhone/iPad, in Files App, go to the **Html Viewer** folder, long press the file, click "Rename File", change the first four letters to the **ICAO** code of the airport you want to query, click OK to save.

For example: ZBAAAirportWeatherMetar.html

ZBADWeather.html

## 功能（Function）
解析 Metar 报 和 TAF 报的内容，并用**中文**朗读。

注意，**不是**通播，解析方法是作者stblx自己写的代码。

Analyze the contents of Metar and TAF newspapers and read them aloud in Chinese.

Note that **is not** ATIS, the parsing method is the code written by the author called stblx.

## 快捷指令（Apple Shortcuts）
网址（WebSite）：
https://www.icloud.com/shortcuts/9da83b0e82174154bb07c6d81895011d

用法（Usage）：
使用Github下载HTML文件，使用App Store中可以下载的**HTML Viewer App**，在App中选择HTML文件，然后使用这个Apple快捷方式使用。

记得在Apple快捷方式中**改变屏幕尺寸**。

或者可以直接用苹果的阅读模块来听文本，只需要将网页中的文本复制到Apple快捷方式中。

Use Github to download the HTML file, and use **HTML Viewer App** which can download in App Store, and select the HTML file in the app, then use this Apple Shortcut to use it. 

Remember to change **the phone screen size** to adapt in the Apple Shortcut.

Or you can listen text directly with the Reading Module in Apple link. It just need you to copy the text in webpage to the Apple Shortcut.
