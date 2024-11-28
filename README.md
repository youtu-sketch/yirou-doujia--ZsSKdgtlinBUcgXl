

> 兴趣是最好的老师，**HelloGitHub** 让你对编程感兴趣！


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224846650-277365647.png)


## 简介


**HelloGitHub** 分享 GitHub 上有趣、入门级的开源项目。



> [github.com/521xueweihan/HelloGitHub](https://github.com)


这里有实战项目、入门教程、黑科技、开源书籍、大厂开源项目等，涵盖多种编程语言 Python、Java、Go、C/C\+\+、Swift...让你在短时间内感受到开源的魅力，对编程产生兴趣！




---



> 以下为本期内容｜每个月 **28** 号更新


### C 项目


1、[deskhop](https://github.com)：基于树莓派的双机鼠标键盘共享方案。这是一款用于快速切换鼠标和键盘的桌面切换工具，解决了用户在多台计算机之间共享键盘和鼠标时遇到的繁琐和延迟问题。它通过硬件中介设备，支持在不同操作系统（Linux、macOS、Windows）之间通过拖动鼠标或使用快捷键实现输入的无缝切换。该项目完全开源，且不需要安装额外的驱动。硬件则是基于 Raspberry Pi Pico 和 USB 输入/输出协议，支持自定义配置并提供多种附加功能，如慢速鼠标模式、屏幕锁定和游戏模式。来自 [@无间之钟](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631490-1469022793.gif)


2、[kyanos](https://github.com)：深入内核的网络流量分析工具。这是一个基于 eBPF 的网络问题分析工具，能够实时监控和分析 HTTP、Redis 和 MySQL 请求。它支持强大的流量过滤功能，可根据进程、容器、协议信息和耗时等条件进行精确过滤，并提供多维度聚合抓取的数据包信息，适用于排查远程服务慢查询等问题。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631401-851608181.gif)


3、[minisign](https://github.com)：简单易用的文件签名工具。这是一个开箱即用的文件数字签名与验证工具，只需要简单的命令即可生成和验证文件签名。它基于 Ed25519 公钥签名系统，提供可靠的文件完整性验证功能，适用于软件分发和文件共享等场景。



```
# 创建密钥
minisign -G
# 对文件进行签名
minisign -Sm HelloGitHub.txt
# 验证签名
$ minisign -Vm HelloGitHub.txt -P xxxx

```

### C\# 项目


4、[AvaloniaVisualBasic6](https://github.com)：经典的 VB6 IDE 跨平台重生计划。该项目使用 C\# 语言和 Avalonia 框架复刻了经典的 Visual Basic 6 IDE，支持创建、保存、加载和运行 VB6 语言的项目，能够在 Windows、macOS、Linux 和浏览器中运行。来自 [@39499740](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631735-256175834.gif)


5、[FileConverter](https://github.com)：右键轻松转换和压缩文件的工具。这是一个专为 Windows 设计的文件转换和压缩工具，用户可以通过右键菜单轻松完成文件格式转换和压缩操作。它完全免费开源，支持多种文件格式、批量处理等功能，并提供包括中文在内的多语言支持。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631414-1710360116.gif)


### C\+\+ 项目


6、[carla](https://github.com)：开源的自动驾驶研发模拟平台。这是一款用于自动驾驶研究的开源模拟器，专为自动驾驶系统的开发、训练和验证提供虚拟环境。它包含免费的数字资产库，包括城市布局、建筑和车辆模型等，支持灵活配置传感器套件和环境条件。还提供了容易上手的 Python API，方便开发者进行车辆控制、传感器配置和环境参数调整。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631354-61066678.png)


7、[PrismLauncher](https://github.com)：开源的 Minecraft 启动器。该项目是基于 MultiMC 开发的 Minecraft 启动器，旨在帮助用户轻松管理多个 Minecraft 版本和实例。它优化了启动器的使用体验，支持快速切换不同版本、模组配置和游戏设置，兼容 Windows、Linux 和 macOS 平台。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631663-1043751935.png)


8、[zeal](https://github.com)：实用的离线文档浏览工具。该项目是受 Dash 启发、专为开发者打造的离线文档查询工具，无需联网即可访问各种编程语言和框架的 API 文档。它提供简洁的界面和多种编辑器插件，并支持自定义文档的创建和导入，适合在没网的环境下查看技术文档。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631590-2042540833.png)


### Go 项目


9、[dpanel](https://github.com)：轻量级的 Docker 可视化管理面板。这是一款专为国内用户设计的 Docker 可视化管理面板，采用全中文界面。它安装简单且资源占用低，运行在容器内部对宿主机无侵入，支持容器管理、镜像管理、文件管理以及 Compose 管理等功能。来自 [@donknap](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631739-920242971.png)


10、[go\-blueprint](https://github.com)：快速生成 Go Web 项目结构的工具。这是一个用于快速搭建 Go 语言 Web 项目的命令行工具，集成了 Chi、Gin、Fiber、Echo 等多种流行的 Go 框架。它支持选择 MySQL、Postgres、Redis 等主流数据库，还提供了 WebSocket 和 Docker 等高级设置。用户只需选择技术栈，即可生成一套完整的 Go Web 项目架子。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631409-1886984647.png)


11、[lute](https://github.com)：对中文更友好的 Markdown 引擎。这是一个用 Go 语言编写的 Markdown 引擎，实现了最新的 GFM/CM 规范。它是将 Markdown 文本转换成一个抽象语法树（AST），无需正则表达式解析速度更快，支持 GFM/CM 规范、内置代码高亮、术语修正、格式化（中英文间自动插入空格）和 Emoji 解析等功能。来自 [@两双筷子sqldc](https://github.com) 的分享



```
func main() {
	luteEngine := lute.New() // 默认已经启用 GFM 支持以及中文语境优化
	html:= luteEngine.MarkdownStr("demo", "**Lute** - A structured markdown engine.")
	fmt.Println(html)
	// Lute - A structured Markdown engine.


}

```

![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631617-1687196493.png)


12、[OliveTin](https://github.com)：极简的 Shell 命令 Web 管理平台。该项目提供了一个简单直观的 Web 界面，让用户能够快速执行预先设定好的 Shell 命令。它开箱即用、配置简单、占用资源少，可以将复杂的命令简化成网页上的一个按钮。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631824-1425918663.png)


13、[wanderer](https://github.com)：开源的探险轨迹记录与分享平台。该项目是用于记录和管理用户的户外探险轨迹的 Web 平台，帮助你保存珍贵的行程数据。它采用 Go\+Svelte 开发，提供上传、保存、查看（多种视图）和分享冒险轨迹的功能，并支持自托管。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631575-94446417.png)


### JavaScript 项目


14、[moodist](https://github.com)：免费、高颜值的白噪音网站。这是一个有助于专注与放松的听觉网站，无需注册完全免费。它界面简洁、操作方便，内置 75 种白噪音，用户可根据个人喜好自由选择与组合，找到适合自己的声音环境。同时，Moodist 还支持定时关闭、番茄时钟、快捷键等功能。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631357-391028418.png)


15、[rot.js](https://github.com)：开发 Roguelike 游戏的 JavaScript 工具包。这是一个无依赖的 JavaScript 库，专为开发 Roguelike（肉鸽）游戏而设计，包含地图生成、随机数生成、路径寻找、按键处理和照明等多个模块。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631360-1032718440.png)


16、[slugify](https://github.com)：将字符串转化成 URL 友好的 JS 库。该项目是用于将字符串转换为适合在 URL 中使用的格式，输出由小写字母、数字和短横线组成的字符串，不含空格和特殊字符，这种格式有助于搜索引擎优化（SEO）。



```
var slugify = require('slugify')

slugify('some string') // some-string

// if you prefer something other than '-' as separator
slugify('some string', '_')  // some_string

```

17、[starlight](https://github.com)：基于 Astro 的一站式文档解决方案。该项目是基于 Astro 框架打造的文档主题，可用于快速搭建和部署文档网站。它界面美观、开箱即用、访问速度快，支持网站导航、搜索、国际化、SEO 和各种插件。来自 [@小小修真者](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631556-1770727174.png)


18、[xiaoju\-survey](https://github.com)：企业级的问卷调查平台。这是一款免费且专业的调研系统，旨在为个人和企业提供一站式产品级的调研解决方案。它前后端均已开源，并支持 Docker 一键部署，内置了多种题型和模版，支持逻辑编排、自定义品牌、权限管理、数据分析和导出等功能，可用于创建问卷、考试、测评和复杂表单。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631744-609162981.png)


### Kotlin 项目


19、[ab\-download\-manager](https://github.com)：Kotlin 开发的下载工具。这是一款开源的桌面下载工具，专为提供便捷快速的下载体验而设计。它拥有现代化的界面和更快的下载速度，支持下载队列、速度限制和浏览器插件功能，兼容 Windows 和 Linux 平台。来自 [@DeShuiYu](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631720-226540988.png)


20、[Olauncher](https://github.com)：极简的 Android 启动器。这是一款免费、无广告的 Android 启动器，主屏幕上最多可设置 8 个应用，提供极简的 Android 使用体验，并支持手势、双击锁屏和每日壁纸等功能。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631820-557460410.png)


### Python 项目


21、[ASCII\-generator](https://github.com):[wgetCloud机场](https://tabijibiyori.org)：生成文字图的 Python 库。该项目是一款将图片和视频转换为 ASCII 艺术风格作品的工具，即用字符艺术化地表达图像内容。它使用简单，支持将图片转换为文本或 ASCII 风格图片，以及将视频转换为 ASCII 风格视频，并提供颜色选择等多种功能。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631916-739240263.jpg)


22、[icloud\_photos\_downloader](https://github.com)：iCloud 照片下载工具。这是一款用 Python 开发的工具，可用于批量下载 iCloud 照片。它提供了复制、同步和移动三种操作模式，支持 Live Photos、自动删除重复数据、增量下载等功能，适合用于 iCloud 照片迁移和备份等场景。


23、[imagehash](https://github.com)：基于哈希值识别相似图像的 Python 库。该项目的算法不同于传统的加密哈希算法（如 MD5、SHA\-1），它专注于图像内容的相似度分析，对有细微不同的图片可生成相似的哈希值，用于计算图片相似度，支持平均哈希、感知哈希、差分哈希等算法，适用于快速识别版权图片等场景。



```
from PIL import Image
import imagehash

# 计算第一个图像的哈希值
hash = imagehash.average_hash(Image.open('tests/data/imagehash.png'))
print(hash)
# 哈希值：ffd7918181c9ffff

# 计算第二个图像的哈希值
otherhash = imagehash.average_hash(Image.open('tests/data/peppers.png'))
print(otherhash)
# 哈希值：9f172786e71f1e00

# 比较两个图像哈希值是否相等
print(hash == otherhash)  # False

# 计算并输出哈希值的汉明距离
print(hash - otherhash)  # 33 汉明距离（差异度）

```

24、[mopidy](https://github.com)：Python 写的音乐服务器。这是一个易扩展的 Python 音乐服务器，支持扫描和播放本地音乐，并集成多个在线音乐流媒体，还可通过插件扩展音乐源、管理界面和在线播放器等功能。


25、[pyarmor](https://github.com)：强大的 Python 脚本加密工具。这是一个用于对 Python 脚本进行混淆处理的命令行工具，仅需一条命令即可完成加密操作。它提供丰富的加密选项，用来平衡安全与性能，支持将加密后的脚本绑定到特定机器、设置加密有效期和 Themida 保护等功能。来自 [@Xuefeng Xu](https://github.com) 的分享


### Rust 项目


26、[kanata](https://github.com)：跨平台的键盘重映射工具。这是一个用 Rust 语言开发的键盘重映射工具，用户可根据自身需求自定义键盘布局和功能，支持点击按住、组合键编程、设置按键响应速度，适用于 Windows、Linux 和 macOS 系统。


27、[surrealdb](https://github.com)：端到端的云原生数据库。这是一个用 Rust 开发的多模型数据库，支持表格（Table）、文档（Documents）和图（Graph）数据模型。它既可以作为数据库使用，也可作为 API 后端服务，支持 SQL、GraphQL、ACID 事务、图查询和全文索引等多种查询方式。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631598-1804615991.png)


28、[tauri](https://github.com)：Rust 驱动的跨平台桌面应用开发框架。这是一个用于构建更小、更快、更安全的桌面和移动应用的框架，支持 macOS、Windows、Linux、Android 和 iOS 平台。它允许使用前端框架构建用户界面，并内置应用打包器、系统托盘图标和原生通知等功能。来自 [@DeShuiYu](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631738-794453276.png)


### Swift 项目


29、[Off\-Day](https://github.com)：休息日闹钟不响的 iOS 应用。这是一个专为 iOS 用户开发的节假日闹钟应用，内置多个公共假期模板，用户可以轻松标记假期，实现自动管理工作日和假期的闹钟设置，确保休息日不再被闹钟打扰。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631581-1894834436.png)


### 人工智能


30、[krita\-ai\-diffusion](https://github.com)：Krita 的 AI 绘画助手插件。这是一个专为 Krita 绘画软件开发的 AIGC 插件，旨在提供更便捷和可控的图像生成体验。用户只需选择区域并输入文本提示，即可轻松实现图像填充、扩展、放大、添加和删除对象等操作，支持本地运行、Stable Diffusion、ControlNet、IP\-Adapter 和自定义检查点等功能。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631716-1813488231.png)


31、[netron](https://github.com)：跨平台的机器学习模型查看工具。这是一个神经网络、深度学习和机器学习模型的可视化工具，支持多种模型格式，包括 ONNX、TensorFlow Lite、Core ML、Keras、Caffe、Darknet 和 PyTorch 等。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631629-1301859943.png)


32、[Perplexica](https://github.com)：AI 驱动的搜索引擎工具。这是一个开源的 AI 搜索引擎工具，灵感来源于 Perplexity AI。它结合了 SearxNG 和大语言模型（LLMs）等技术，能够理解你的问题并深入互联网查找答案，可作为传统搜索引擎的替代品。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631721-305475829.png)


33、[TensorRT\-YOLO](https://github.com)：灵活易用的 YOLO 部署工具。这是一款专为 NVIDIA 设备优化的 YOLO 部署工具。它通过集成 TensorRT 插件和 CUDA 技术，提供 C\+\+ 和 Python API，显著提升了推理速度和易用性，支持多种 YOLO 版本，适用于目标检测、实例分割、姿态识别、旋转目标检测和视频分析等多种场景。来自 [@Laugh](https://github.com) 的分享



```
import cv2
from tensorrt_yolo.infer import DeployDet, generate_labels_with_colors, visualize

# 初始化模型
model = DeployDet("yolo11n-with-plugin.engine")
# 加载图片
im = cv2.imread("test_image.jpg")
# 模型预测
result = model.predict(cv2.cvtColor(im, cv2.COLOR_BGR2RGB))
print(f"==> detect result: {result}")
# 可视化
labels = generate_labels_with_colors("labels.txt")
vis_im = visualize(im, result, labels)
cv2.imwrite("vis_image.jpg", vis_im)

```

![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631825-1336000506.gif)


### 其它


34、[BewlyBewly](https://github.com)：优化 bilibili 网站界面的浏览器插件。这是一个第三方的 B 站浏览器插件，通过优化 bilibili 网站的界面来提升用户体验，支持 Chrome、Edge 和 Firefox 浏览器。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631830-1343306840.png)


35、[frpc\-desktop](https://github.com)：跨平台的 frp 桌面客户端。该项目是内网穿透工具 frp 的桌面客户端，更方便地实现内网穿透。它开箱即用、界面清爽，支持开机启动、多用户、配置导入和导出等功能，适用于 Windows、Linux 和 macOS 平台。来自 [@蠢🐷](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631064-2012290347.png)


36、[keeptrack.space](https://github.com)：卫星数据 3D 可视化工具。这是一个为非专业人士开发的开源天体力学工具，支持查看卫星数据、模拟卫星发射和解体等功能，适合用于教育和科普等场景。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631745-964248252.png)


37、[openhaystack](https://github.com)：利用苹果网络实现物品追踪的框架。该项目是基于苹果的 Find My 网络，实现跨设备的定位与追踪。它通过将支持蓝牙的设备转化为类似 AirTag 的追踪器，轻松定位个人物品的位置，方便找回。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631841-2045529043.jpg)


38、[ping\-clock](https://github.com)：显示网络延迟的时钟。这是一个自制的时钟，用于显示 ping 指令的响应时间，整体造价约为 150 欧元。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224632103-1837850602.gif)


39、[spotube](https://github.com)：开源的 Spotify 客户端。该项目是基于 Flutter 开发的 Spotify 客户端，完全免费且无广告。它使用 Spotify、JioSaavn 和 YouTube 作为音乐源，用户无需登录即可自由下载音乐，支持桌面和移动设备。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241127224631719-273605143.png)


### 开源书籍


40、[copenhagen](https://github.com)：《Web 应用认证实现指南》。这是一本介绍如何在 Web 应用中实现认证（auth）的书籍，内容涵盖设计认证流程、存储用户凭据、保护用户数据等方面的指导与建议。


41、[php\-the\-right\-way](https://github.com)：《PHP: The Right Way》。这是一本适合初学者进阶的 PHP 书籍，介绍了 PHP 的最佳实践和编码规范，已被翻译成包括中文在内的多国语言。


## 最后


感谢参与分享开源项目的小伙伴们，欢迎更多的开源爱好者来 HelloGitHub 自荐/推荐开源项目。如果你发现了 GitHub 上有趣的项目，就[点击这里](https://github.com)分享给大家伙吧！


本期有你感兴趣的开源项目吗？如果有的话就留言告诉我吧～如果还没看过瘾，可以[点击阅读](https://github.com)往期内容。


感谢您的阅读，如果觉得本期内容还不错的话 **求赞、求分享** ❤️


