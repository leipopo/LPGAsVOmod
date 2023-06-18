# LPGAsVOmod

Translated by ChatGPT3.5, manually checked. Errors are welcome to be pointed out.

# 在线CAD链接(Online CAD link)：

## https://a360.co/43akzyH
## 以在线CAD文件为准，stl不保证为最新版本。(The online CAD file is the authoritative version, and the stl file is not guaranteed to be the latest version.)
PTC heater CAD: https://grabcad.com/library/ptc-heater-12v-50w-1


# 此方案在使用因大流量火山热端而加长的喷头时效果更佳。(This solution works better when using a nozzle that has been extended due to high flow and hot end temperatures.)

原版标准长度喷头需要抬高PTC处风道来减少出风口正对热床的面积，但是由于原版喷嘴高度问题抬高后也无法完全避免在前十多层里侧吹吹到热床的问题，同时会极大减小出风口宽度，降低空气流量，对比图如下。(The original standard length nozzle needs to raise the air duct at the PTC to reduce the area of the air outlet facing the heated bed. However, due to the height issue of the original nozzle, it is still unable to completely avoid the problem of blowing air onto the heated bed in the first ten layers. At the same time, it greatly reduces the width of the air outlet and reduces the air flow. The comparison chart is shown below.)

![加长喷头](/img/火山加长长度侧吹高度.jpg "加长喷头")
    
上图为加长喷头，此时z高度为零，由于机器构建时间较早，我使用的是3DPMAMSIH基于v0的xcarriage设计的 https://github.com/Mamsih/VOV0-toolhead-voron-Zero喷头和基于mellow配件改装的火山龙热端。
(The above picture shows the extended nozzle, with a Z height of zero. Since the machine was built earlier, I used the hot end with xcarriage design based on v0 by 3DPMAMSIH, and the nozzle was modified using Mellow accessories and a volcano hot end. The design can be found at https://github.com/Mamsih/VOV0-toolhead-voron-Zero.)

![标准喷头](/img/原版标准长度侧吹高度.jpg "标准喷头")
    
上图为标准长度的原版喷头，可以看到如果要完全避免吹到热床，需要删除风道主体出风口的收束设计和抬高ptc位置的风道但是也只能留出不到5mm（风道壁厚 1mm，距离xyjoint 0.5mm）的出风口高度（图示侧吹版本是13mm高度的出风口，带风道收束，可以按需减少出风口高度增加流速，但仓库内版本为了对标准长度进行兼容设计了较高的高度）。
(The above picture shows the original standard length nozzle, and it can be seen that in order to completely avoid blowing onto the heated bed, it is necessary to remove the convergence design of the air outlet of the main air duct and raise the air duct at the PTC position. However, this can only leave a height of less than 5mm (air duct wall thickness 1mm, distance from xyjoint 0.5mm) for the air outlet (the version shown in the figure has an air outlet height of 13mm with air duct convergence, which can be reduced as needed to increase the flow rate, but the version in the repository is designed with a higher height to be compatible with the standard length).)

# 安装PTC效果如下：(The installation of the PTC has the following effect:)

![安装PTC](/img/PTC.jpg "安装PTC")

# 不安装PTC效果如下：（The effect without installing the PTC is as follows:）

![不安装PTC](/img/NO_PTC.jpg "不安装PTC")

# 安装PTC和热敏方式如下：（The installation of the PTC and the thermistor is as follows:）

使用扎带穿过在PTC风道板预留的孔绑住PTC上的隔栅以及热敏，热敏从PTC风道板预留的孔位穿出。
(Use zip ties to pass through the hole reserved in the PTC air duct board and tie the grille and thermistor on the PTC. The thermistor passes through the hole reserved in the PTC air duct board.)

![安装PTC和热敏](/img/IMG_20230513_214400.jpg "安装PTC和热敏")

![安装PTC和热敏1](/img/IMG_20230513_214424.jpg "安装PTC和热敏1")

# 过滤盒打印方式和磁铁安装：(The printing method for the filter box and the installation of the magnet are as follows:)

使用适配火山热端的加长喷头时过滤侧的框架连接件需要使用加高打印件加高。(When using the extended nozzle that is compatible with the volcano hot end, the frame connectors on the filter side need to be printed with an increased height using the appropriate print settings.)
![连接件加高](/img/框架连接件加高.jpg "连接件加高")

滤盒盖正反打印都可以
![滤盒盖打印](/img/IMG_20230513_212849.jpg "滤盒盖打印")

## 安装磁铁：(The installation of the magnet is as follows:)

![安装磁铁](/img/IMG_20230513_213003.jpg "安装磁铁")

# 安装门卡扣：(The installation of the door latch is as follows:)

![安装门卡扣](/img/IMG_20230617_192143.jpg "安装门卡扣")

# 安装斜撑：(The installation of the diagonal brace is as follows:)

![安装斜撑](/img/斜撑安装.jpg "安装斜撑")

# 安装灯条：(The installation of the LED strip is as follows:)

![安装灯条](/img/灯条安装.jpg "安装灯条")

