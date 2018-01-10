# 首页

















# 安装前准备

在安装配置设备前，请准备如下硬件设备：

| 序号   | 物料名称              | 数量   |
| ---- | ----------------- | ---- |
| 1    | 网关设备              | 至少一个 |
| 2    | 控制类和/或传感类设备       | 若干   |
| 3    | 安卓或苹果智能手机         | 一台   |
| 4    | 能上网的无线路由器（2.4GHz） | 一台   |



# 安装与登录Aqara APP

Aqara APP是智能家庭应用，Aqara产品均通过Aqara APP进行操控，实现ZigBee设备之间的场景联动、远程控制等功能。

具体操作步骤如下：

1. 在手机应用商店或AppleStore中搜索“Aqara”，或者扫描以下二维码，下载安装APP至手机。

   ![app二维码](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_app.png) 

2. 打开Aqara APP，单击“新用户注册”按钮，输入手机号或邮箱，获取验证码后，单击“下一步”。

3. 设置登录密码，单击“下一步”。

4. 在弹出的“注册成功”窗口，输入“家”的名称，单击“确定”，完成注册。

# 安装配置设备

Aqara产品包括网关、控制器、传感器三大类。网关类设备是用于连接与管理多个智能传感器和控制器的中心枢纽。控制类设备是根据指令产生各种操作控制信号，来协调和指挥整个系统的操作。传感类设备是通过温度、湿度、光敏、位移等感知功能，来实现自动检测和自动控制。

在成功使用设备前，需根据实际环境，合理的安装或放置所有设备，以实现各设备间的智能联动。

## 网关类设备

网关类设备有多功能网关、空调伴侣和智能摄像机。

除网关功能外，空调伴侣还可快速实现传统空调的智能化改造，智能摄像机还具有安防摄像头功能。因此，对于这两个设备，安装位置分两种：一种为“网关功能优先”，另一种为“空调控制优先”或“摄像头优先”。用户可以根据实际需求选择安装位置。

1. **网关功能优先**

   请将网关类设备（多功能网关、空调伴侣或智能摄像机）尽量安装在家庭的中央位置，且与无线路由器保持2~6米的距离，以保证无线信号覆盖、设备稳定工作。

   > 注意：超过70平方米的住宅户型，根据实际情况分区域增加网关数量。

   ![网关位置](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_gateway.png)

2. **空调控制优先**

   请将“空调伴侣”插入空调专用插座（16A），再将空调电源插头插入空调伴侣的插座，且与无线路由器保持2~6米的距离，以保证无线信号覆盖、设备稳定工作。

   > 注意：空调伴侣通过红外控制空调，因此，空调伴侣与空调红外面板之间不能有阻挡物。

   ![安装空调伴侣](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_condition.png)

3. **摄像头优先**

   智能摄像头底座自带磁铁，可平放在桌上、吸附在墙上或顶上。请将“智能摄像头”放置在需要监控的区域。

## 控制类设备

> 安装前注意事项：
>
> - 除智能插座外的控制类设备应由具有正式资格的**专业人员**按照电工规范和产品说明书的要求进行安装、调试。
> - 墙壁开关仅限室内使用，不适用于可独立关断的智能灯泡和双控电路，使用前请务必在总闸关闭情况下安装，安装完成后开启总闸。

### 墙壁插座

建议由具有正式资格的专业人员按照电工规范和产品说明书的要求进行安装、调试。使用前请务必在总闸关闭情况下安装，完成后再开启总闸。墙壁插座安装指导，请参考以下链接：<https://www.aqara.com/cn/videointroduce.html> 

 

### **智能插座**

请将智能插座接入网关范围内的插座上。



### **墙壁开关（单火版）**

以”双键版“为例说明，墙壁开关（单火双键版）每个按键对应控制一路灯光，具体安装方法如下： 

![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_ctrl_neutral1.png)

1. 关闭电源总闸，拧松背面螺丝，将墙壁盒里的火线（颜色红色）接到输入端L孔，将墙壁盒里的负载导线（颜色绿色或黄色）接到L1孔和L2孔（注：L1和L2所接电灯分别由开关左键和右键控制），拧紧螺丝，接线图如下所示。

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_ctrl_neutral3.png)

   > 注意：火线一般是红色的，灯具负载线一般为绿色或黄色，建议由专业电工使用电笔等专业工具测试后再安装。墙壁开关（单火双键版） 有3个接线孔，L、L1、L2；L接入的是火线，L1和L2分别接入灯具的负载线。

2. 用一字螺丝刀掀起开关面壳。

3. 用螺丝钉将开关固定到墙壁接线盒里。

4. 扣上开关面壳即可。

5. 开启总闸，蓝色状态指示灯闪烁一下，表示正常通电。按下外壳按键，红色状态指示灯会持续慢闪，表示开关正常但还没有入网，具体入网方法请参见”设备入网“章节。

> 注意：
>
> - 墙壁开关（单火版）取电方式为单火取电，负载需要稳定，所以无法支持带调光功能或自带关断功能的智能灯。如有需求，可选择墙壁开关（零火版）。
>
> - 墙壁开关（单火版）较难支持灯带类负载，可能出现闪烁现象。如有需求，可选择墙壁开关（零火版）。
>
> - 墙壁开关（单火版）各类负载最低功率要求：3W节能灯/5WLED灯/16W荧光灯。
>
>   **特别注意**：如果是老式的带启辉器的灯管灯，请更换电子启辉器。目前墙壁开关（ZigBee版）对主流品牌的灯具支持力度较好，但对于小众品牌或者山寨厂商，由于其灯具内部的电路设计和用料问题，可能造成灯具闪烁、开关死机等异常现象，请用户谨慎选择。
>
> - 墙壁开关（单火版）有双路和单路，每路负载不超过800W。如有需求，可选择墙壁开关（零火版）其负载范围为：最大2500W（总路数）且负载类型无要求。

### **墙壁开关（零火版）**

以”双键版“为例说明，墙壁开关（零火双键版）每个按键对应控制一路灯光，具体安装方法如下： 

![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_ctrl_neutral1.png)

1. 关闭电源总闸，拧松背面螺丝，将墙壁盒里的零线和火线分别接到N孔和L孔，将墙壁盒里的电灯导线接到L1孔和L2孔（L1和L2所接电灯分别由对应的左、右键控制），拧紧螺丝，接线图如下所示。 

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_ctrl_neutral2.png)

   > 注意：
   >
   > - 火线一般是红色的，灯具负载线一般为绿色或黄色，建议由专业电工使用电笔等专业工具测试后再安装。墙壁开关（零火双键版） 有4个接线孔，N、L、L1、L2；N接入的是零线，L接入的是火线，L1和L2分别接入灯具的负载线。
   > - 墙壁开关（零火版）其负载范围为：最大2500W（总路数）。


2. 用一字螺丝刀掀起开关面壳。

3. 用螺丝钉将开关固定到墙壁接线盒里。
4. 扣上开关面壳即可。
5. 开启总闸，蓝色状态指示灯闪烁一下，表示正常通电。按下外壳按键，红色状态指示灯会持续慢闪，表示开关正常但还没有入网，具体入网方法请参见”设备入网“章节。

### **智能窗帘电机**

建议由专业窗帘工程商安装。使用前请务必在总闸关闭情况下安装，完成后再开启总闸。轨道与电机安装指导，请参考以下链接：<https://www.aqara.com/cn/videointroduce.html> 

 

### **智能门锁**

智能门锁安装教程，请参考以下链接：<https://www.aqara.com/cn/videointroduce.html> 

 

### **空调温控器**

 

### **双路控制器**

 

### **调光控制器**



## 传感类设备

安装前注意事项：

1. 粘贴表面须保持清洁干燥，请避免安装在金属表面，否则将影响无线通讯距离。
2. 为了保障粘胶的牢固性以及调整方便，首次安装时请不要压实，先轻轻的粘在预定位置处（确保不会掉落即可），测试安装无误后，再压实粘紧。
3. 需要调整传感器位置时，请向左、右两侧掰下；请勿垂直拉扯，费力且损伤粘胶粘度。
4. 安装时请避免摔落，易损坏传感器主体。

### 门窗传感器

安装方法如下：

1、撕下胶贴保护膜。

2、安装时尽量对齐主体与磁铁侧边的安装标记。

3、分别粘贴在所需的开合区域，确认不会阻碍门窗正常开闭（建议主体安装在开合区域固定面，磁铁安装在活动面，安装间隙在门窗关闭状态下小于**22毫米**）。

![门窗传感器安装步骤](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_magnet.png)

### 人体传感器

人体传感器有三种安装方式：

- 无需粘贴，直接放置在所需区域即可。
- 撕下胶贴保护膜（配有圆形背胶贴），粘贴在所需区域即可。
- 将传感器粘贴在安装底座上，再将底座粘贴在所需区域即可。

> 注意：
>
> 1. 建议安装高度未1.2~2。1米，小于1.2米探测范围变小，但不影响使用；大于2.1米传感器底部会出现盲区，部分区域无法探测。
> 2. 安装时请注意透镜要对准需要探测的区域，放置或粘贴时传感器尽量靠近桌面或柜体边缘。

​                                    ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_motion1.png)          ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_motion2.png)

### 温湿度传感器

温湿度传感器有两种安装方式：

- 无需粘贴，直接放置在所需区域即可。
- 撕下胶贴保护膜（配有圆形背胶贴），粘贴在所需区域即可。

### 水浸传感器

水浸传感器有两种安装方式：

- 直接放置在所需检测的平面上。
- 用内六角螺丝刀将感应探头拧松，接上导线后，可应用于更多场景。

> 说明：传感器天线的位置在”水滴“图标的上方。

### 天然气报警器

> 安装前注意事项：
>
> - 天然气报警器可通过有线的方式直接联动燃气电磁阀或排气扇，务必请**专业人员**进行安装。
>
>
> - 报警器应安装在有可燃气体（天然气等含甲烷的可燃气体）设备的房间中，例如：厨房。
> - 报警器电源线长为1.5m，请确保安装位置半径1.5m内有220V~电源插座。
> - 仅能安装在室内使用。
> - 报警器与用气设备间不能有阻隔物，否则将影响探测。
> - 不能安装在房间进气口、换气扇、窗户、房间等空气流动性大的位置，否则将影响探测。

**安装位置与限制**

- **壁挂安装**：天然气报警器与燃具或燃气阀门的水平距离为L（1m<L<4m），且与天花板的距离为D（D<0.3m），不得安装在燃具正上方。

  ![壁挂安装](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_natgas1.png)

- **吸顶安装**：天然气报警器与燃具或燃气阀门的水平距离为L（1m<L<4m），且不得安装在燃具正上方。

  ![吸顶安装](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_natgas2.png)

**安装方式与步骤**

> 注意：为了确保天然气报警器安装的牢固性，我们推荐使用螺钉安装方式。请谨慎采用粘贴安装方式，若因此导致意外和损失，需用户自行承担相关责任。

- **螺钉安装**

1. 用拇指压住下图中的圆圈位置，然后按照箭头所示方向逆时针旋转，将底板取下。 

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_natgas3.png)

2. 选取合适的安装位置，使用铅笔标识打孔位置。

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_natgas4.png)

3. 使用冲击钻（6mm直径钻头）在标识位置打洞，然后将膨胀胶塞嵌入洞中。

4. 使用自攻螺丝固定底板，并将报警器主体压到底板上，然后顺时针旋转，卡入底板。

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_natgas5.png)

5. 使用自带适配器为报警器提供电源输入。

- **粘贴安装**

1. 将包装内的双面3M背胶贴在产品背面的底板上（底板无需取下）。
2. 清洁安装位置表面，撕下背胶保护膜，粘贴在安装位置处。
3. 使用自带适配器为报警器提供电源输入。

**验证安装**

- 短按按键1次，网关发出提示音“连接正常”，说明报警器安装成功。
- 长按报警器按键，持续3s以上，报警器开始模拟报警（发出高分贝报警声音）。

### 烟雾报警器

> 安装前注意事项：
>
> 1. 仅限室内天花板安装使用。
> 2. 不能安装在浴室内、易沾水或附有水滴的位置。
> 3. 不能安装在易产生水蒸气等其他非火灾烟雾的位置。
> 4. 报警器应和照明设备保持50cm以上距离；
> 5. 报警器应与换气扇、空调、通风口保持150cm以上距离；
> 6. 当橱柜靠近天花板时，报警器应与橱柜保持60cm以上距离。

**安装方式与步骤**

> 注意：为了确保烟雾报警器安装的牢固性，我们推荐使用螺钉安装方式。请谨慎采用粘贴安装方式，若因此导致意外和损失，需用户自行承担相关责任。

- **螺钉安装**

1. 选取合适的安装位置，使用铅笔标识打孔位置；

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_smoke1.png)

2. 使用冲击钻（6mm直径钻头）在标识位置打洞，然后将膨胀胶塞嵌入洞中，然后使用自攻螺丝固定底板；

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_smoke2.png)

3. 将报警器主体压到底板上，然后顺时针旋转，卡入底板。

   > 注意：若报警器未安装电池，则无法将报警器主体卡入底板。

   ![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_sensor_smoke3.png)

- **粘贴安装**

1. 将包装内的双面3M背胶贴在产品背面的底板上。

2. 清洁安装位置表面，撕下背胶保护膜，粘贴在安装位置处。

3. 将报警器主体压到底板上，然后顺时针旋转，卡入底板。

   > 注意：若报警器未安装电池，则无法将报警器主体卡入底板。

**验证安装**

- 短按按键1次，网关发出提示音“连接正常”，说明报警器安装成功。
- 长按报警器按键，持续3s以上，报警器开始模拟报警（发出高分贝报警声音）。

### 魔方控制器

请将魔方控制器放在平整的平面上进行操作，在沙发、枕头等柔软的物体表面上操作，动作可能无法操作成功。

![](http://cdn.cnbj2.fds.api.mi-img.com/cdn/aiot/doc-images/zh/implementation/installation-and-configuration/install_cube.png)

### 无线开关

无线开关有三种安装方式：

- 无需粘贴，直接放置在桌面即可。
- 撕下胶贴保护膜，粘贴在所需区域即可。
- 墙面钻孔，用螺钉固定即可。（仅贴墙式无线开关支持此方式）



# 设备入网

设备入网阶段，可将Aqara产品分为两类：网关设备和子设备。网关设备即为具有网关功能的设备，用于连接与管理多个智能传感器和控制器的中心枢纽。子设备包括传感器和控制器。所有子设备必须搭配网关设备使用，因此，在APP上配置子设备前，必须先配置网关设备，确保WiFi与ZigBee之间无线传输通讯正常。

## 网关设备入网

APP添加网关设备的具体操作如下：

**步骤1：添加设备**

打开Aqara APP，单击“设备列表”界面右上角的“+”，在网关下选择对应的网关设备，根据页面提示开始添加设备。

**步骤2：连接WiFi**

- 安卓版手机

请点击已发现的“空调伴侣xxxx”，然后选择待连接的Wi-Fi，并输入密码；若未能发现新设备，请点击下方“扫描设备”按钮，等待设备识别。

> - 若连接失败，请长按5秒空调伴侣按键，直到红色灯光闪烁，并重新点击“扫描设备”
> - 若仍然连接失败，请点击“手动添加”，依照提示进行设备添加
> - 若多次尝试仍然连接未成功，请更换Wi-Fi（不识别有特殊字符的Wi-Fi）

- IOS版手机

选择待连接的Wi-Fi，并输入密码；然后按手机提示点击“去设置Wi-Fi”，并选择“lumi-acpartner-XXX” 开头的Wi-Fi连接后，点击左上角”返回Aqara App“。

> - 若连接失败，请长按5秒空调伴侣按键，直到红色灯光闪烁，重新点击“+”并选择设备“空调伴侣”
> - 若多次尝试仍然连接未成功，请更换Wi-Fi（不识别有特殊字符的Wi-Fi）

**步骤3：设置设备信息**

根据提示选择设备安装位置，设置设备名称，完成配置。

 

**步骤4：命名设备信息**

为便于查看和操作设备，长按对应的设备，重命名设备名称，完成设备配置。建议根据位置命名，例如客厅-多功能网关，卧室-空调伴侣。

> 注意：设备数量较多时，请勿重命名设备，以防设备名称重复造成困扰。



**步骤5：匹配空调（仅空调伴侣需操作）**





## 子设备入网

网关设备添加完成后，请按照以下步骤添加子设备：

**步骤1：添加子设备**

打开Aqara APP，单击“设备列表”界面右上角的“+”，在传感器或控制器下选择对应的网关设备，根据页面提示开始添加设备。

**步骤2：设置设备信息**

根据提示选择设备安装位置，设置设备名称，完成配置。

 

**步骤3：命名设备信息**

为便于查看和操作设备，长按对应的设备，重命名设备名称，完成设备配置。建议根据位置命名，例如客厅-无线开关，卧室-人体感应器。

> 注意：设备数量较多时，请勿重命名设备，以防设备名称重复造成困扰。

**步骤4：测试连接状态**

子设备添加完成后，在预定安装位置，按一下传感器或控制器的重置键或使用复位针短按复位孔1次，网关将发出提示音“连接正常”，表明子设备与网关之间可以有效通讯。

# 场景和自动化配置



## 配置场景





## 配置自动化





## 样例





# 附录

## 术语
