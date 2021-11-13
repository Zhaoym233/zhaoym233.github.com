# 游戏设置

## 进入谱面时颜文字下方的红色按钮进入

---

`#1`<span id="gameSetting-1"></span>

1. **Performing Mode [表演模式；演奏模式]**: 启用后即使不点击音符亦可发音。

1. **Use System Stopwatch [使用系统秒表；使用系統时鐘]**: 通过使用系统时钟(硬件时钟)来提高精度，如果游戏内音频时而提前时而延后可以启用，可能会造成更高的电池耗损

---

`#2`<span id="gameSetting-2"></span>

1. **Randomize Block Color [随机颜色；隨機音符顏色]**: 随机设置音符与光效的颜色

1. **Sync Color Across Block Type [使所有类型的音符颜色一致；統一音符顏色]**: 使short、instant和long的颜色统一，使三种音符不会同时有着不同的颜色，同时也会统一光柱特效的颜色，但打开此项会导致音符颜色停止随机

1. **Instant Block Color [instant颜色；更改滑塊顏色]**: 更改instant及其光柱特效的颜色(需要输入RGB颜色编码)

1. **Short Block Color [short颜色；更改短塊顏色]**: 更改short及其光柱特效的颜色(需要输入RGB颜色编码)

1. **Long Block Color [long颜色；更改長條顏色]**: 更改long及其光柱特效的颜色(需要输入RGB颜色编码)

- - 关于RGB颜色

- - - [什么是RGB](https://baike.baidu.com/item/RGB/342517)

- - - [查询RGB颜色编码](https://encycolorpedia.com/)

---

`#3`<span id="gameSetting-3"></span>

1. **Custom Block Skin Texture Filter Mode [自制皮肤纹理过滤器模式；音符紋理過濾模式]**: 更改音符皮肤的渲染方式

- - 选择Nearest会禁用颜色过渡，使音符皮肤看着棱角分明，建议像素皮肤和高清皮肤使用

- - 选择Bilinear会启用颜色模糊过渡，建议低清的高清皮肤使用(?)

1. **Block Skin Preset [音符皮肤名称；音符外觀設定]**: 直接选择已导入的或内置的音符皮肤的名称即可更换，旧版需要自行输入皮肤名称

---

`#4`<span id="gameSetting-4"></span>

1. **Lane Count [下落音符的轨道数；下落軌道數量]**: 设置音符的下落轨道数，数值过高会提升音符重叠的概率。轨道数更改后，生成的谱面可能会和之前的完全不同，所以此设置项可能会影响读谱难度

1. **Block Size [音符大小；音符尺寸大小]**: 调整音符的显示宽度

1. **Block Judging Width [音符判定区域；音符判定寬度]**: 调整音符判定范围的宽度

1. **[；最小橫向音符間距]**: 音符之间的最小间距，在特定版本内可能导致音符残缺/音符位于画面之外

1. **[；帆布水平填充]**: 设置画面内左右无法放置音轨的区域，用于解决音符残缺/音符位于画面之外的问题的设置

---

`#5`<span id="gameSetting-5"></span>

1. **Judge Line Position [判定线位置；判定線高度]**: 调整判定线与屏幕底部的距离

1. **Judge Line Thickness [判定线粗细；判定線粗細]**: 调整判定线厚度，不影响判定

---

`#6`<span id="gameSetting-6"></span>

1. **Playback Speed Scaling [曲速设定；播放速度設定]**: 调整音乐的播放倍率，数值越大速度越快，速度低于1时，游戏分数将不会上传

1. **Cache Time [音符下落速度；音符下落速度]**: 调整音符经过判定线前的下落速度，数值越大速度越快，默认为2(建议调整范围:0.5～3)

1. **Cache Easing Type [音符下落模式；音符下落模式]**: 设置音符经过判定线前的下落方式

1. **Grace Time [音符过判定线后下落速度；音符過判定線后的下落速度]**: 调整音符经过判定线后的下落速度，数值越大速度越快，默认为2

1. **Grace Easing Type [音符过判定线后下落方式；音符過判定線后的下落模式]**: 设置音符经过判定线后的下落方式

- - 下落方式有：

|左侧选项|效果|右侧选项|效果|
|---|---|---|---|
|None|无任何下落效果|None|不改变左侧选择的下落方式的下落效果|
|Linear|匀速下落|In|默认设置，会使左边选择的下落方式与其描述相同|
|Quad|正常的加速下落|Out|使左边选择的下落方式表现效果相反。如左边选择Bounce，右边选择Out，则音符会在屏幕顶端弹跳几次再下落|
|Cubic|稍快的加速下落|InOut|使左侧选择的下落方式产生In和Out的效果，例如减速下落会使音符在从顶部出现和接近判定线时加速，落到中间时稍微减速一下|
|Quart|较快的加速下落|
|Quint|极快的加速下落|
|Sine|减速下落|
|Expo|极快的减速下落|
|Circ|较快的减速下落|
|Back|音符落到判定线时会折返一段距离|
|Elastic|极快的速度+达到判定线折返|
|Bounce|音符会在判定线上弹跳数次后下落|

- - 这些

---

`#7`<span id="gameSetting-7"></span>

1. **Instant Block Max Time [生成instant上限时间；生成滑塊最大時間]**: 控制instant的生成时间，使长度低于此时间的short变成instant，调为0则不会生成instant，但受其他设置影响仍可能会有instant生成

1. **Short Block Max Time [生成短块上限时间；生成短塊最大時間]**: 使低于此时间，高于instant生成时间的音符变为short，高于此时间的将变为long

1. **Max Simultaneous Blocks [最大并排音符数；最大並排下落音符]**: 控制同时下落的音符的最大数量，使并排下落的音符的数量不会超过此值，但当音符没有对齐时，仍可能遇见多个音符同时下落

1. **Min Tap Interval [最小连点间隔时间；連點最小時間間隔]**: 使一个short后跟着的低于此时间的short变成instant，若该short变成的instant与后方的short间的时间差仍低于该时间，则继续变成instant，它们需在同一下落轨道

1. **Min Touch Cooldown Time [您手指松放的最短时间；最小點擊冷卻時間]**: 最小点击冷却时间，在一段纵连之中，如果上下相邻的音符之间的间隔时间超过最小点击冷却时间，则后面的音符变为instant(仅是推测，需证实)

1. **Max Touch Move Speed [您手指的最快移动速度；手指最大移動速度]**: 使各个相邻的音符(无需同一轨道)之间的水平距离在设置的数值所推算出来的距离之间。例如设置成100，然后两个离得近的音符之间的时间差是0.1s，那么它们的水平距离不会超过10像素(0.1s × 100pixels/s)(仅是推测，需证实)

- - 该设置项貌似只对一连串的下落音符有效，所以此设置项能够让楼梯变纵连。在某些时候可能不会生效

1. **Max Block Coalesce Time [每个音符批次生成的最大时间；每個批次最大時間]**: 控制每组下落的音符的时间间隔

---

`#8`<span id="gameSetting-8"></span>

1. **Generate Short Connect [是否生成同排音符连线；是否連接所有並排的點塊]**: 选择是否生成连接线，连接并排下落的音符

1. **Generate Instant Connect [是否生成上下音符连线；是否連接上下相鄰的滑塊]**: 选择是否生成连接线，连接同一下落轨道内的时间差在设定范围内的数的音符

1. **Instant Max Time [instant连线上限时间；被連接音符的最大時間差]**: 设置同一轨道内的音符连接线连接的音符之间的时间间隔，低于此数值的同轨音符就会被连接，前提是有打开[游戏设置-第8栏-第2项](#gameSetting-8)

---

`#9`<span id="gameSetting-9"></span>

1. **Judge Time Offset [延迟判定时间；按鍵延遲調整]**: 调整音频延迟

1. **Perfect Time [完美(perfect)判定范围；Perfect判定范围]**: 控制perfect评分的判定时间范围，此数值无法更改，

1. **Great Time [很棒(Great)判定范围；Great判定范围]**: 控制great评分的判定时间范围，此数值无法更改

1. **Good Time [良好(Good)判定范围；Good判定范围]**: 控制good评分的判定时间范围，此数值无法更改

1. **Bad Time [断连(Bad)判定范围；Bad判定范围]**: 控制bad评分的判定时间范围，此数值无法更改

---

`#10`<span id="gameSetting-10"></span>

1. **Flash Alpha [Flash Alpha；光柱不透明度]**: 修改光柱的不透明度，有效数值为0～1，修改为0即可完全隐藏光柱特效

1. **Perfect Spark Preset [完美(perfect)特效文件位置；Perfect特效設定]**: 更改按键特效，选项不明

1. **Perfect Spark Scaling [完美(perfect)特效大小；Perfect特效大小]**: 调整按键特效的半径，调成0即可隐藏特效

1. **Great Spark Preset [很棒(Great)特效文件位置；Great特效設定]**： 同Perfect Spark Preset

1. **Great Spark Scaling [很棒(Great)特效大小；Great特效大小]**: 同Perfech Spark Scaling

1. **Good Spark Preset [良好(Good)特效文件位置；Good特效设定]**: 同Perfect Spark Preset

1. **Good Spark Scaling [良好(Good)特效大小；Good特效大小]**: 同Perfech Spark Scaling

1. **Bad Spark Preset [断连(Bad)特效文件位置；Bad特效设定]**: 同Perfect Spark Preset

1. **Bad Spark Scaling [断连(Bad)特效大小；Bad特效大小]**: 同Perfech Spark Scaling

---

`#11`<span id="gameSetting-11"></span>

1. **Keyboard Mode [键盘模式；鍵盤模式]**: 用键盘来玩TouhouMix，打开了键盘模式后仍可用手打，且判定线上会显示设置的键盘的按键

1. **Keyboard Mode Keys [键盘模式键位；鍵盤鍵位設置]**: 设置使用键盘游玩时的按键，会影响下落轨道数量

- - 输入重复字母会使排在左边的重复字母失效，输入无效的按键会直接被忽略，不同按键间请用半角逗号分离，除字母按键外请使用Unity按键代码

- - 轨道是从屏幕两侧开始排列的