> <span style="color: red; font-weight: bold;">注意！注意！注意！</span>
>
> <span style="color: red; font-weight: bold;">借助于AI大时代，即将回归！（年前应该会更新一波）</span>



# 资源接口(接口地址见底部)

**各类资源软件所需的接口，一些资源接口，及一些接口收集** 

**目前已经有的接口**(点击可跳转)

* [TVBox接口](#TVBox)
* [Legado阅读3.x书源](#Legado-3.x)

---

> **关于接口地址连通性说明**
>
> * 默认提供的地址为 `*.520993.xyz` 域名的链接
>   * 优点：短、看着舒服、使用方便
>   * 缺点：由于地区运营商限制，**部分地区可能无法访问**
> * 若出现无法访问，可先尝试使用给出的备用地址，若依然无法访问，则请参阅 **[备用地址](#备用地址)**
>
> 
>
> **关于软件无法下载的问题说明**
>
> * 由于蓝奏云的原因，手机打开分享链接如果无法直接下载（提示“开通会员”），将浏览器设为 **“电脑模式”** 打开链接即可


---

# 防失联

## 加入Telegram

> 直接点击链接即可 [https://t.me/CandyMujSource](https://t.me/CandyMujSource)


## **关注公众号**

1、在微信```添加朋友-公众号```中搜索 **CandyMuj** 进行添加

2、扫描下方二维码直接添加

<div align=center>
<img src="https://p.sda1.dev/13/8ee512e428148ed382f1503d7c0a0a53/wx.png" alt="CandyMuj" width="300" />
</div>

---

<a id="TVBox"></a>

# TVBox（影视）

> **本仓暂时不考虑IOS，软件也没有列出IOS的，因为我不用苹果！！！故关于苹果的软件和问题一概不回复！！！**

## 配置地址

* 配置地址(含极少福利资源)： https://tv.520993.xyz/candymuj.json
  * 备用：https://gh-proxy.com/raw.githubusercontent.com/CandyMuj/ResourceInterface/main/TVBox/candymuj.json
  * 备用：https://cdn.jsdelivr.net/gh/CandyMuj/ResourceInterface/TVBox/candymuj.json
  * 备用：https://gcore.jsdelivr.net/gh/CandyMuj/ResourceInterface/TVBox/candymuj.json
  
* 配置地址1(无福利资源)：https://tv.520993.xyz/candymuj1.json
  * 备用：https://gh-proxy.com/raw.githubusercontent.com/CandyMuj/ResourceInterface/main/TVBox/candymuj1.json
  * 备用：https://cdn.jsdelivr.net/gh/CandyMuj/ResourceInterface/TVBox/candymuj1.json
  * 备用：https://gcore.jsdelivr.net/gh/CandyMuj/ResourceInterface/TVBox/candymuj1.json

## 高级配置

* 由于部分配置（例如Cookie之类的），若全都由我提供是不可能的，且配置直接由我写死也不好，故开放了一种方式**可以自己在本地自定义部分敏感配置**
* 这部分配置，可根据需要配置，若不需要可将配置直接移除即可，但需保证为标准Json格式
* 默认会在本机 `/Android/CandyMuj/TVBox/conf` 下自动生成一个名为 `conf.json` 的配置，若没有则自行在目录下新建一个
* 具体配置项请参考 [conf.template.json](TVBox/conf/conf.template.json)
* 配置会随着后期开发有增减，请关注 [conf.template.json](TVBox/conf/conf.template.json) 文件的最新内容，关注其变动

## 推荐软件下载

<details>
  <summary>目前主流的影视壳子系列</summary>

**A. TVBoxOSC 系（老牌，跟 FongMi 不同源）**

| 项目                                      | 状态                                                         |
| ----------------------------------------- | ------------------------------------------------------------ |
| `q215613905/TVBoxOS`                      | 原 TVBoxOSC，2999★，**仍在维护**，最后提交 2026-09-14，现在由**于俊/jun** 维护；分支 `main`、`dev`、`oldTv`、`file_transfer` |
| `takagen99/Box`                           | 3083★，TVBoxOSC 的 UI 美化版，分支 `main`、`dev`、`dark`，最后提交 **2026-02-27**（贡献者 Rycbar123、juejijianghuaa） |
| 影视仓、可视TV Max、月光宝盒 Box/Max/Plus | 闭源魔改，同架构不同壳                                       |

**B. FongMi（蜂蜜）系——你要的重点**

| 项目                                                         | 说明                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| `FongMi/TV`                                                  | 主源码，10286★，GPL-3.0，单分支 `fongmi`，文档站 `fongmi.github.io/TV` |
| `FongMi/Release`                                             | APK 发布仓库，7490★，只剩 `fongmi` 分支                      |
| `FongMi/CatVodSpider`                                        | 爬虫 jar/js 示例仓库，943★，2026-11-02 仍在更新              |
| `okcaptain/TV`                                               | 81★，OK 自己的源码 fork（2024-01-12 建，2024-10-01 停）      |
| `okcaptain/CatVodOpen`、`okcaptain/CatPawOpen`               | OK 在爬虫引擎侧的延续项目，他现在的精力主要在这里            |
| `lystv/fmapp`                                                | 278★，OK 侧的发布镜像，分支有 `main`、`ok`、`app`、`img`、`pg*`，`ok` 分支末尾 3.6.2 / 3.9.3-pro（2026-01 至 02） |
| `kknifer7/TV-K`                                              | 139★，2025-12 起的移动端 fork，配 FreeBox 用                 |
| `haha459862/BearTV`、`jadehh/FongMiTV`、`mokudong/FongMiTV`、`raptorz/TVBox-mobile`、`15840213978a/fongmi`、`linfern-mou/fongmi` | 小规模个人 fork，同源改包                                    |
| 蜂蜜下游魔改（宝盒、西夏、开心、天微、木鱼、猫TV、春盈天下、三林、欧歌、星辰等） | 基本全是拿 FM 的 APK 换皮，不公开源码                        |

**C. CatVod 系**：`CatVodOpen`（okcaptain 维护的开放版）、`CatPawOpen`（2025-01 起接续 CatVodOpen）。

</details>

### 首选（FongMi影视系列）

> 个人开发及验证，基于此，不保证其他壳子的兼容性，如果其他壳子存在Bug，可以反馈，但不一定会处理（视问题复杂度以及修复的价值高低考量）
>
> 注意：由于蓝奏及GitHub的单文件上传限制，部分安装包通过网盘下载

<details>
  <summary>关于FongMi和OK相关的一些说明</summary>

- FongMi影视移除java单独版本的说明：2025.04.03 v3.4.5版开始移除 java 单独版本，目前安装 java 的版本会自动升级成 py 的版本

  后续版本只区分v7a和v8a： v7a兼容新旧设备，大多数设备都可以使用特点：支持更多特殊协议直播源 v8a只能在新设备上安装特点：适配新硬件，在新设备上可以最大限度发挥硬件性能，运行会更高效

- FongMi影视版本说明：

  - mobile = 手机版
  - leanback = 电视版
  - java = jar + js 爬虫
  - python = jar + js + py 爬虫
  - arm64_v8a = 64 位元
  - armeabi_v7a = 32 位元
  - dev = 內测版
  - kitkat = 4.x 版
  - release = 正式版

- OK影视的时间线

  ```
  2022-06-22  FongMi/TV 建仓（源码，GPL-3.0）
  2023-08-11  FongMi/Release 建仓，2.0.4  →「影视」
  2024-01-12  2.2.0：APK 改为提交进分支目录 apk/release
  2024-01-21  2.2.3：最后一个 FongMi 时代的包，之后提交者变 okjack
  2024-01-28  2.2.4 → 品牌变「OK影视」，OK 线开始
  2024-05-13  改为 CI 机器人推包（作者 action@github.com）
  2024-10-01  OK 源码在 TV 仓 okjack 分支冻结（最后一版 2.5.8）
  2025-04-05  FongMi 回归，3.4.9（版本号故意越过 OK 的 2.8.3）→「影视」
  2025-06-25  OK 最后一版源码级版本 2.9.6（此后只有私有构建）
  2026-01-21  OK影视Pro 3.9.3
  2026-01-22  OK 线最后产物 3.6.2 —— OK 从此停更
  2026-09-29  Release 仓 Clean：分支里的 apk/ 全删，tag 全部重建
  2026-10-08  module release
  2026-11-01  FongMi 5.8.7（当前最新）
  ... FongMi 版本持续维护更新中
  ```


  - **两条线是同一个包名**（都 `com.fongmi.android.tv`，同一张 `CN=FongMi` 证书），所以 OK 版和 FM 版互为覆盖升级路径，同一个手机只能留一个。
  2. **OK 从来没有公开源码**；公开的只有 2024-10-01 之前那批（现在在你 fork 的 `okjack` 分支里），2.5.9 之后的 100 多个版本号（→3.6.2/3.9.3）都是在私有环境编的，仓库里只有 APK。

- OK影视Pro版的说明


  - 并非什么会员版，是在同一APP上额外加入了部分功能，差异如下：
  - 在基础版上额外加入 VLC 播放内核 + 云备份/跨端推送 + 扫码授权 + 代码加固。
  - 它的版本号高出一截，原因只是人为把版本号段抬高了一档（号段有意错开一档），跟功能多少无关。两版撞号时一眼能分清，也方便更新检查（apk/release/ 用 mobile.json/leanback.json 报版本，apk/pro/ 只放一个 v.txt 写 3.9.3 + changelog）。


</details>

#### 手机版（Android）

* [FongMi影视](https://dwzz.cc/video_mobile_fm)
* [OK影视](https://dwzz.cc/video_mobile_ok)
* [OK影视Pro](https://dwzz.cc/video_mobile_ok_pro)

#### TV电视版（Android）

- [FongMi影视](https://dwzz.cc/video_tv_fm)
- [OK影视](https://dwzz.cc/video_tv_ok)
- [OK影视Pro](https://dwzz.cc/video_tv_ok_pro)

### 次选（更多影视壳子）

更多电视盒子应用可前往 [TVAPP](https://github.com/youhunwl/TVAPP) 第三方聚合仓库下载（众包整理，收集的十分全）

**注意：除上述推荐的版本外，其他壳子不保证对我的源的兼容性，但可以折腾玩玩。另外优先推荐使用开源的。最后还是推荐优先使用上方首选推荐的。** 



---

<a id="Legado-3.x"></a>

# Legado 3.x（阅读）

## 配置地址

* 书源配置：https://yd.520993.xyz/candymuj.json
  * 备用：https://gh-proxy.com/raw.githubusercontent.com/CandyMuj/ResourceInterface/main/Legado/candymuj.json
  * 备用：https://cdn.jsdelivr.net/gh/CandyMuj/ResourceInterface/Legado/candymuj.json
  * 备用：https://gcore.jsdelivr.net/gh/CandyMuj/ResourceInterface/Legado/candymuj.json


## 关于软件下载及使用方法

[关注公众号 `CandyMuj`](#建议关注公众号) 通过底部菜单 **`资源分享` -> `免费看小说和漫画`** 获取文章查看

---

# 备用地址

> 由于主地址接了Cloudflare，部分时候或地区会存在 **无法访问或加载缓慢的问题，建议使用备用地址**
>
> **备用地址：** 就是GitHub的地址，加了个加速服务，如果备用地址也用不了了，可以自己百度一下， **找一个能用的加速服务进行替换即可**

## 示例

> 此处以TVBox地址作为示例，其他源同理，修改一下原始地址即可
>
> 下方的加速网址和加速地址仅作为示例，不一定有效且快速，需自行去找加速服务

GitHub的原始源地址为：https://raw.githubusercontent.com/CandyMuj/ResourceInterface/main/TVBox/candymuj.json

百度或其他搜索引擎搜索 [GitHub文件加速](https://www.baidu.com/s?wd=GitHub文件加速)，选择并进入一个加速网站：https://moeyy.cn/gh-proxy

得到一个加速地址：https://github.moeyy.xyz/

可根据网站内的说明进行地址拼接，则得到加速后的源地址：https://github.moeyy.xyz/https://raw.githubusercontent.com/CandyMuj/ResourceInterface/main/TVBox/candymuj.json
