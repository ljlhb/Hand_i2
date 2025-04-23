## 手i2

从图库下载 STL 文件：i2RightHand i2LeftHand。

在打印所有部件之前，您应该打印一份校准器 (CALIBRATOR)，以检查部件是否能够拼合。如果您在拼合这些部件时遇到困难，可以调整切片软件的水平扩展设置来解决这个问题。此设置可能因切片机和打印机而异，但用户报告称，将其设置为 -0.15 是一个不错的起点。

以下是一只右手所需的零件清单和打印数量：

1个i2_CoverFingerV3
1x i2_FingersMoldX5V3
1个 i2_FingersTipX5V2
1个i2_FingersX5V1
1x i2_HandCoverV1
1个i2_PalmCoverV2
1x i2_PulleyX5V1
1x i2_WristGearV1
1个 i2_WristLargeV2
打印腕部大件、手指模具、手指、腕带、滑轮，最大分辨率 0.25，填充率为 30%，壁厚为 2 毫米，无支撑，无筏。

打印 CoverFinger、FingersTip、HandCover、PalmCover，最大分辨率 0.25，填充率为 30%，壁厚为 2 毫米，需要支撑，如果打印机需要，则需要筏。

物料清单：

25个沉头螺钉M3 x 16mm
5 个 M3 x 4mm 沉头螺钉
1 个 M3 x 12mm 沉头螺钉
5 个平头螺钉 M1.5 x 4mm
5个膨胀弹簧3/16英寸x1-3/4或4.8毫米x44.5毫米
6x舵机 JX-6225MG 300度
1x 带状线 16 根 3 米
1 条编织鱼线 0.8 毫米 200 磅，3 米
5个霍尔传感器AH3503
5x 圆盘磁铁直径 2.5mmx1mm
1x 特氟龙管 ID1.5MM X OD2.5MM，3米
 

<h2>步骤1</h2>

![image](https://github.com/user-attachments/assets/c018f92b-3d1b-4db8-a168-fc1a4714e1e6)

将腕部伺服支架粘到 RobCableFront 上

![image](https://github.com/user-attachments/assets/24646728-586f-45b1-93ea-72bc1acdee80)

用 4 个螺钉安装伺服电机

![image](https://github.com/user-attachments/assets/0988a7fb-2e62-4ce3-b1b3-561f9b4a6bf7)

如果需要，用 M3 钻头重新钻孔

![image](https://github.com/user-attachments/assets/10634749-f620-46c9-ac43-c27bdce2b570)

重新钻孔，以便 M3 PTFE 管穿过它们

![image](https://github.com/user-attachments/assets/e9547d9d-cc76-4854-a622-5bc475dbc53c)

使用 M3 钻头重新钻孔

![image](https://github.com/user-attachments/assets/e8c89a9b-9f00-46bc-a212-898764dde333)

将两个轴打印部件粘合在一起

![image](https://github.com/user-attachments/assets/09ca90a5-9492-4841-9a5d-ea52dba306f8)

检查以确保轴正确安装在两个印刷齿轮中

![image](https://github.com/user-attachments/assets/cca0395d-58e9-4a4f-81b9-02ba8be29c2c)

将 RobCableFront 和伺服支架安装到伺服床上

![image](https://github.com/user-attachments/assets/35a1fbe5-d1c9-4ca1-87bf-c83678cbc13f)

此视图向您展示了 WristGear 的组装以及各个部件如何组合在一起

![image](https://github.com/user-attachments/assets/af77ce47-e08e-4ed8-8e98-854b8f06a792)

将舵机角度设置为大约 90 度（HK15298B）或 150 度（JX-6225MG）。（即舵机总角度的中间值）。您可以使用此脚本(见脚本.txt)进行设置。用 3 毫米螺钉将组件末端安装到舵机轴上。

![image](https://github.com/user-attachments/assets/bb58fcd5-32aa-4cc6-b68b-bf86c0305213)

用 4 颗螺丝将组件拧到手腕上

![image](https://github.com/user-attachments/assets/e5fe72d8-c5eb-4bfa-a852-83720d1d1706)

按图示组装主齿轮

![image](https://github.com/user-attachments/assets/f04f7249-b853-45fc-8936-09083430160d)

注意小齿轮的头部必须适合 RotaWrist2 的预留孔

![image](https://github.com/user-attachments/assets/34e7a8a4-7128-4a53-917d-a8fa1990535a)

使用 M3 螺丝刀将主齿轮与 RotaWrist3 对齐，然后添加 M3 x 12 毫米螺钉将它们固定在一起

![image](https://github.com/user-attachments/assets/95588f92-307a-4ea8-a1e7-2912ed18a28d)

删除那块打印的预支撑，你不再需要它了

![image](https://github.com/user-attachments/assets/1c8196e6-c1e1-4d8a-abc6-f636b4e78ae8)

用锋利的刀片，必要时清理边缘

![image](https://github.com/user-attachments/assets/846de710-f465-48f3-bc80-990bf8d2ed86)

![image](https://github.com/user-attachments/assets/9b4ed84e-22ce-4f91-a754-55d40e665682)

使用 M8 钻头重新钻孔 WristLarge

![image](https://github.com/user-attachments/assets/aca1b28a-611e-4685-b643-3ebe3cd222dc)

使用 M3 丝锥，在将要固定手盖的地方准备一些 M3 x 16 毫米螺丝孔

![image](https://github.com/user-attachments/assets/ad9da142-8c09-445a-a084-7b4a54b086a7)

使用 M3 丝锥，为安装弹簧的 M3 x 16 毫米螺钉准备孔

![image](https://github.com/user-attachments/assets/5f0ca785-3272-4bc7-a5f0-1561a600b2b7)

使用 M3 钻头，清理连接每个手指的所有孔

![image](https://github.com/user-attachments/assets/b3928661-df97-4458-b1de-86e5543af6af)

用M3钻头，将所有手指每3节的孔全部清理干净

![image](https://github.com/user-attachments/assets/02ab3897-c9d3-4df3-a398-59738dd5b2fc)

用锋利的刀片清理霍尔传感器的出口

![image](https://github.com/user-attachments/assets/c254f702-4f78-4cf4-bfe6-64492c55f67a)

使用 M1.5 钻头，清理弹簧末端连接的孔

![image](https://github.com/user-attachments/assets/6481343c-bd2e-48b7-b7b7-1712741ccaa8)

用填充物时，确保每个手指的三个部分都贴合，并且移动起来非常顺畅。这对于手指的良好功能至关重要。

![image](https://github.com/user-attachments/assets/d9feb969-62f9-4f87-8f7f-431897590377)

![image](https://github.com/user-attachments/assets/abc9d14f-aa79-4ad5-afb6-61077b4febb8)

使用 M5.5 钻头清理手指部分，让弹簧正常穿过

![image](https://github.com/user-attachments/assets/14407396-c0b4-4ca9-a3af-ffb26a38e585)

使用 M5.5 钻头清理手指部分，让弹簧正常穿过

![image](https://github.com/user-attachments/assets/00605e4a-14ad-4fbe-b6f8-1317a8171658)

这是为了向您展示如何将弹簧和三根传感器线安装在每个手指部分

![image](https://github.com/user-attachments/assets/820977b6-e6f9-40be-9f5f-78c419a26d9d)

确保针头可以穿过每个手指部分，如图所示，否则清理孔

![image](https://github.com/user-attachments/assets/976cfb0e-4ef5-45a2-b75d-e84df780df7d)

使用 M3 x 16 毫米螺钉和螺栓将手指部分添加并安装在一起

![image](https://github.com/user-attachments/assets/5209d50e-e023-4752-9e8c-a3d8871cb378)

确保编织鱼线的入口也清理干净

![image](https://github.com/user-attachments/assets/2d5dcb93-d667-4e95-9436-3d47818aaba3)

准备 5 条长度为 50 厘米的编织鱼线（0.8 毫米 200 磅）如果您在谷歌搜索中输入这些关键词，就可以找到该产品：编织鱼线 0.8 毫米 200 磅

![image](https://github.com/user-attachments/assets/ff230843-da5d-4fc7-80f8-f861520e9835)

准备一条40厘米长的带状电缆。你可以在谷歌搜索关键词：带状电缆 16 针（尽量选择最柔软、最细的）。

![image](https://github.com/user-attachments/assets/17537dc0-cf3b-46e1-b4d3-6e54770f43be)

将丝带分成两部分，一部分长 40 厘米，有 6 根电线，另一部分长 10 根电线

![image](https://github.com/user-attachments/assets/e72e9700-fdaa-4116-859f-3aa131f0b600)

从10根电线中完全移除1根电线。将9根电线分成三段，每段3根电线，长度均为15厘米。

![image](https://github.com/user-attachments/assets/bb9b6559-ab14-4b5e-9af1-0b06549c3ba1)

用红色记号笔，给每个部分的一根电线涂上颜色。我们假设这些是正极 (+) 线

![image](https://github.com/user-attachments/assets/b801502d-d047-4d08-93b4-481b7410ae02)

在丝带的两端都涂上这些颜色，这对于避免在进行最后的焊接时混合电线非常有用。

![image](https://github.com/user-attachments/assets/19ab6096-f285-4d89-a377-f4240c976fa6)

穿过腕部大号每 5 个丝带部分

![image](https://github.com/user-attachments/assets/9011334e-dd1c-429f-8ded-50470f833708)

将丝带穿过每个手指，注意不要倒着穿。另外要注意，每个手指的形状都差不多，只有拇指的形状不同。

![image](https://github.com/user-attachments/assets/a2092b91-57bb-472b-9ab8-b77d5803879e)

现在把编织好的鱼线穿过每个手指。为了让鱼线末端更硬，可以加一些强力胶。

![image](https://github.com/user-attachments/assets/a379985f-00b1-4730-8189-d2c1e245d9ca)

在 1 厘米长的编织钓鱼线上涂上强力胶。

![image](https://github.com/user-attachments/assets/9bb1d475-299e-4bd7-9098-1fa2028035a0)

等到它完全干燥后，从中间切开粘合部分，这样可以确保尖端坚固而纤薄。

![image](https://github.com/user-attachments/assets/b9ddb11e-30ca-44aa-995f-f1a82cb0d29c)

通过将钓鱼线拉入指尖的 V 形凹槽，即可将其固定

![image](https://github.com/user-attachments/assets/bd30142f-74d3-4adf-95c1-f2f538ddb241)

现在将鱼线的另一端插入手腕大孔中

![image](https://github.com/user-attachments/assets/5c9c760e-b3e5-4526-919c-8af4e4e8ca5e)

这是给你展示一下它应该是什么样子。我的照片上还没做拇指，不过你可以做。五个手指可以同时做。

![image](https://github.com/user-attachments/assets/02a2ce54-ee28-438e-bc7e-377429b7747a)

如果你还没有这样做，请清理 3 毫米螺栓外壳，以便进行下一步

![image](https://github.com/user-attachments/assets/bf57c2cd-96eb-433b-a32f-719f71e7d2bf)

现在是时候添加 M3 x 16 毫米螺钉及其相应的螺栓，将手指组装到大腕上。从大拇指开始，然后是食指、无名指、小指，最后是拇指。

![image](https://github.com/user-attachments/assets/7442f7b1-b8b9-4130-a5c2-575ad5033ab0)

使用合适的 M8 印刷螺栓将 WristLarge 安装到 RotaWrist3

![image](https://github.com/user-attachments/assets/a46bf66d-fd3f-4aa3-a553-2b8219e771fd)

将微型夹具设置在打印螺栓的凹槽上

![image](https://github.com/user-attachments/assets/f2d454e3-d9bb-4fff-a802-f822da4621fb)

穿过主齿轮的最大丝带

![image](https://github.com/user-attachments/assets/a710336b-51a5-4366-b8fa-595e6f25803b)

然后穿过主齿轮第二条丝带

![image](https://github.com/user-attachments/assets/86770bc3-c6d7-4cbd-bbb6-39d7e4598182)

放置掌上盖并用 3 颗 M3 x 16 毫米螺钉固定

![image](https://github.com/user-attachments/assets/22c91658-8d7a-4aa8-a00e-6582eb01daf2)

拧紧掌上盖时，确保将丝带整齐地放入凹槽中，并真正避免夹住它们

![Uploading image.png…]()

现在将 M2.5 PTFE 管穿过主齿轮特氟隆管 ID1.5MM X OD2.5MM PTFE 管的长度如下：拇指 335mm 食指 300mm 中间 300mm 无名指 300mm 小指 360mm

 


将管子穿过伺服底座孔。管子距离伺服轴约 1.5 厘米。

 


将鱼线穿过管子




并将管子的末端放入预留的孔中，直到无法再插入为止

 


对每根手指重复操作

 


现在获得 5 个弹簧弹簧 3/16″x1-3/4

 


将一根鱼线穿过弹簧的一侧。鱼线总长度约为30厘米

 


将鱼线穿过主指部分的弹簧孔

 


将弹簧穿过第二个手指部分

 


取 5 个小螺丝，我用了一些安装在眼部机构中的伺服器上的螺丝，这些螺丝的直径约为 2 毫米




用钳子将螺丝剪至最大总长度为 4 毫米

 


将弹簧固定到位

 


装上那个小螺丝，把弹簧固定到位。确保螺丝没有刺穿三根带状电线

 


获取或切割五颗 3 毫米、最大长度为 4 毫米的螺钉


拉动鱼线，将弹簧头固定到位，然后安装螺丝。注意，我在螺丝刀上放了一块黑色磁铁，这样可以方便安装螺丝。

 


拧紧螺丝之前，先将鱼线拉出来

 


完成拧紧。确保没有刺穿三根带状电线

 


拿两根针

 


将手指的最后一部分最大限度地折叠起来，并将第一根针穿过手指和弹簧，直到它从另一侧出来。

 

 


折叠手指的第二节，并将第二根针穿过手指和弹簧，直至完全穿过。这样可以为每个手指节设置合适的张力。

 


用小钳子剪断针头

 


滴一滴强力胶，确保针头不会再出来

 


是时候用拇指做同样的事情了，只有两个手指部分，所以弹簧的张力较小，不需要针

 


拇指的另一个不同之处在于，我们将螺丝拧入盖子中，从而将弹簧固定到位。确保不要刺穿电线。虽然我的图片显示已经装好了拇指盖，但先不要装上，你仍然需要接触到内部。

 


让我们把霍尔传感器焊接到电线上。开始焊接中间的电线。注意传感器在图片上的位置，因为一侧是正极，另一侧是负极。霍尔传感器 AH3503




用一小块胶带保护焊锡。我用的是Kapton胶带。这部分操作比较精细。


焊接第二根和第三根电线并用胶带包裹起来

 


缠绕胶带时，胶带的厚度不应超过丝带本身的厚度，否则下一步将其推下去会很困难。

 


小心地将其推回指尖

 


这是指尖应该伸出的长度

 


你可以拉动手掌中的电线，帮助自己将霍尔传感器推回到尖端

 


将钓鱼线缠绕在凹槽周围，然后小心地将手指末端拧到传感器上。

 


注意，手指末端印有小螺纹，可以顺时针旋转至指尖。请勿用力过猛，否则螺纹会损坏。

 


完成每个手指的操作。

 


你可以用一些 16x3mm 的螺丝安装手指盖。虽然我的图片显示手指盖已经装好了，但先不要装，你仍然需要打开内部。


是时候把每根线焊接到 NervoBoard 的传感器板上了。拇指放在“0”上，食指放在“1”上，大拇指放在“2”上，无名指放在“3”上，小指放在“4”上。

 


您可以在此页面上查看有关传感器连接的更多信息：https://inmoov.fr/test-your-finger-sensor/

 


这里你可以看到我放置迷你模拟板的位置。你还可以在滑轮上看到，带小垫圈的螺丝是如何将鱼线用一个结固定住的。要做到这一点，你需要在你想要剪断鱼线的地方涂上一些胶水。

 


要做到这一点，你需要在你想要剪断的编织线上涂点胶水，让接触胶固化。胶水可以让剪断更容易。

 


然后，用锋利的剪刀剪掉涂有胶水的地方。

 


按照我在图中的方式拉动你的钓鱼线，它应该会形成一个大结。

 


拧紧结，将螺钉和垫圈放在结上，并在拧紧螺钉时保持结被拉住。

 


模具中有一个孔，用于插入直径为2毫米的部件，以便在模制硅胶中形成一个复位，以便磁铁复位。圆盘磁铁直径为2.5毫米x1毫米。

 


让它穿过2毫米。我使用了双组分透明RTV硅胶Ecoflex™ 00-10

 


用硅胶套件将每个指尖上的模制部件粘合起来


用指南针确定磁铁的南极。


将磁铁的南极朝向霍尔传感器，插入硅胶模制尖端的复位孔中。请使用木质牙签，因为任何金属工具都会粘在磁铁上。这项工作很精细，必须操作到位才能获得正确的结果。用一滴硅胶套装固定磁铁位置，并等待其干燥。使用此页面https://inmoov.fr/test-your-finger-sensor/测试您的传感器。
