# eSIM 转实体卡 & 中国大陆可用 eSIM 流量套餐推荐（2026 实测）· [esim.ss](https://esim.ss/)

> 国行手机没有 eSIM 功能？把 eSIM 写进一张实体卡就行。
> 本仓库是独立评测站 **[esim.ss](https://esim.ss/)** 的源码与内容存档：横评 **4 款主流 eSIM 转实体卡**（9eSIM / XeSIM / BeeSIM / ESTK）、**3 个中国大陆可用的 eSIM 流量套餐**（esim.cc / BNESIM / Stellar）、**6 张低成本海外保号卡**，并附完整写卡教程与优惠码。

🌐 **在线阅读（内容持续更新）：<https://esim.ss/>**

<p align="left">
  <a href="https://esim.ss/#cards">eSIM 实体卡对比</a> ·
  <a href="https://esim.ss/#plans">中国流量套餐</a> ·
  <a href="https://esim.ss/#number">海外保号卡</a> ·
  <a href="https://esim.ss/#guide">使用教程</a>
</p>

---

## 目录

- [这个项目是什么](#这个项目是什么)
- [一、eSIM 转实体卡：4 款横评](#一esim-转实体卡4-款横评)
  - [参数对比表](#参数对比表)
  - [各卡详解](#各卡详解)
  - [怎么选？一句话结论](#怎么选一句话结论)
- [二、中国大陆 eSIM 流量套餐](#二中国大陆-esim-流量套餐)
- [三、eSIM 保号卡：低成本长期持有海外号码](#三esim-保号卡低成本长期持有海外号码)
- [四、eSIM 使用教程](#四esim-使用教程)
- [常见问题 FAQ](#常见问题-faq)
- [名词表](#名词表)
- [仓库结构与本地预览](#仓库结构与本地预览)
- [免责声明](#免责声明)

---

## 这个项目是什么

**eSIM 转实体卡**（可复写 eUICC 卡）是一张普通尺寸的 SIM 卡，卡内是可反复写入的 eUICC 芯片：你可以把任意 eSIM Profile 下载进去，让**国行 iPhone、无 eSIM 功能的安卓机**也能自由使用全球 eSIM 套餐，并在多个号码之间随时切换。

esim.ss 做三件事：

1. **横评实体卡** —— 容量、可存 Profile 数、写入次数、切换方式、iPhone 友好度逐项实测对比；
2. **筛流量套餐** —— 中国大陆可直连国际网络（Google / ChatGPT 免 VPN、免实名）的 eSIM 漫游套餐；
3. **算保号成本** —— 每年几块到几十块，长期持有一个能收验证码的海外手机号。

本仓库同时托管站点静态源码（单页 HTML + Open Props），内容变更即部署。

---

## 一、eSIM 转实体卡：4 款横评

### 参数对比表

| 参数 | 9eSIM | XeSIM | BeeSIM | ESTK |
| --- | --- | --- | --- | --- |
| **型号** | V0 / V0 Max / V3 | X1 / X2 / X2 Pro | V1 | C / Plus+ / Max |
| **参考价** | 约 ¥91–163 | 约 ¥91–245 | 约 ¥99–109 | 约 ¥61–173 |
| **存储容量** | **480KB–1.5MB** | — | 340–380KB | **512KiB–1600KiB** |
| **Profile 上限** | **15 / 30 / 50** | 15 / 30 | 8–9 | **最高 60（Max）** |
| **下载次数** | **不限** | X1 限 5 次，X2 起不限 | — | **不限** |
| **切换方式** | STK / Android App | STK / 官方 App | 蓝牙 + 微信小程序 | **STK / 开源 LPA / 读卡器** |
| **iPhone 友好度** | 中（管理需读卡器或 STK） | **X2 Pro 高（免安卓）** | **高（小程序全程）** | **高（STK 直切 + iOS 直接下载）** |
| **App / 生态** | **开源 LPA（NekokoLPA / MiniLPA）** | Android / iOS / 鸿蒙 | 仅微信小程序 / App | **官方 App + 开源（lpac / OpenEUICC）** |
| **特色** | V0 Max / V3 送 1GB 流量 | X2 Pro 含 SeedLink | 官网自营 eSIM 商城 | 5G SA · SoftSIM |
| **优惠** | 9 折码 `YHM` · [直达](https://to.cm/9esim) | 9 折码 `YHM` · [直达](https://to.cm/xesim) | 优惠码 `33250100` · [直达](https://s.tb.cn/c.0xs2qV) | 9 折码 `YHM` · [直达](https://to.cm/estk) |

> 价格随促销波动，最终以各官网实时页面为准。完整可横滑表格见 <https://esim.ss/#cards>。

### 各卡详解

#### 🟣 9eSIM（V0 / V0 Max / V3）—— 容量性价比

主打**开放 eUICC 标准、无账号绑定**。LPA 软件栈开源，兼容 NekokoLPA、OpenEUICC、MiniLPA 等社区工具；STK 菜单秒切 Profile。旗舰 V3 采用 **Kigen OS**（英国制造），兼容 1000+ eSIM 服务商，V0 Max / V3 附赠 1GB 全球流量。

| | |
| --- | --- |
| 型号 / 容量 | V0 480KB · V0 Max 1.1MB · V3 1.5MB |
| 可存 Profile | 15 / 30 / 50 个 · 不限写入 |
| 管理方式 | STK / Android App / 开源 LPA |
| 参考价 | 约 ¥91 / ¥122 / ¥146 |

🎟 9 折优惠码 `YHM` → [9eSIM 直达链接](https://to.cm/9esim)

#### 🔵 XeSIM（X1 / X2 / X2 Pro）—— iPhone 开箱即用

内置 **GSMA 认证证书**，App 覆盖 Android、iOS、HarmonyOS NEXT 三大系统。**X2 Pro 纯 iPhone 也能独立完成写卡**（免借安卓机），并附带 SeedLink。X1 为入门款（限 5 次下载），X2 起不限次写入。

| | |
| --- | --- |
| 型号 | X1（5 次）· X2 · X2 Pro（免安卓） |
| 可存 Profile | 15 / 30 个 |
| 管理方式 | 三系统 App / STK 菜单 |
| 参考价 | 约 ¥91 / ¥175 / ¥219 |

🎟 9 折优惠码 `YHM` → [XeSIM 直达链接](https://to.cm/xesim)

#### 🟡 BeeSIM V1 —— 蓝牙黑科技

卡内直接集成**低功耗蓝牙芯片**：不走 STK、不需要读卡器，手机通过蓝牙（微信小程序 / App）就能写入和管理 eSIM，对 iPhone 用户操作最直观。低功耗设计几乎不影响续航，覆盖 200+ 国家和地区。

| | |
| --- | --- |
| 型号 / 容量 | V1 · 340~380KB 可用 |
| 可存 Profile | 约 8–9 个（按 40KB/个） |
| 管理方式 | 蓝牙 + 微信小程序 / App |
| 参考价 | ¥109 |

🎟 淘宝优惠码 `33250100` → [BeeSIM 直达链接](https://s.tb.cn/c.0xs2qV)

#### ⚫ ESTK（C / Plus+ / Max）—— 生态最全

老牌 eSIM 实体卡，生态最完整：**STK 菜单直接切换**（iPhone 友好），官方 App 之外还兼容 lpac、OpenEUICC 等开源工具，配套读卡器可在电脑上管理。iOS 可直接下载 Profile，支持 5G SA。

| | |
| --- | --- |
| 型号 / 容量 | C 512KiB · Plus+ 1024KiB · Max 1600KiB |
| 可存 Profile | 约 13–60 个 · 不限写入 |
| 管理方式 | STK / 开源 LPA / App / 读卡器 |
| 参考价 | 约 ¥61–173 |

🎟 9 折优惠码 `YHM` → [ESTK 直达链接](https://to.cm/estk)

### 怎么选？一句话结论

| 你是谁 | 推荐 |
| --- | --- |
| **国行 iPhone 用户** | ESTK（STK 直切 + iOS 直接下载）、XeSIM X2 Pro（免安卓写卡）或 BeeSIM（蓝牙全程） |
| **安卓玩家 / 折腾党** | 9eSIM 开源生态最自由，V3 的 Kigen OS 切卡最快 |
| **要大容量多号** | ESTK Max（60 个）或 9eSIM V3（50 个） |
| **预算有限先试水** | 9eSIM V0 或 XeSIM X1（约 ¥102） |

---

## 二、中国大陆 eSIM 流量套餐

这类漫游套餐经**国际出口回传**，Google / ChatGPT 直接可用，**无需 VPN、无需中国实名**。写进上面的实体卡后，国行手机也能随时切换。

| 套餐 | 定位 | 关键价格 | 优惠码 | 链接 |
| --- | --- | --- | --- | --- |
| **esim.cc 年卡** | 长期主力 · 国内支付友好 | 100GB / 365 天 约 ¥339，9 折后约 **¥305** | `9999`（9 折） | [中国套餐](https://to.cm/esimcc) |
| **BNESIM** | 防失联备用 · **流量永不过期** | 100GB 永不过期 约 ¥388，用码后约 **¥310** | `CN20OFF`（8 折） | [中国套餐](https://to.cm/bnesim) |
| **Stellar** | 小流量随买随用 · 超高性价比 | 3GB/30 天 **€0.54 ≈ ¥4.2**；50GB/30 天 **€11.22 ≈ ¥87** | 无需优惠码 | [中国套餐](https://to.cm/rsss) |

**细节补充**

- **esim.cc** —— 支持支付宝、银联及常见银行卡；中国移动 4/5G，ChatGPT / Claude 可用；用户实测 NSA 5G 可达 100Mbps+，部分线路国内应用走香港、国际服务走新加坡。
- **BNESIM** —— 提供**永不过期**流量类型，用多少扣多少；无需中国实名，适合长期备用；中国移动 5G，ChatGPT / TikTok 可用。
- **Stellar** —— 无需中国实名，适合随买随用；中国移动 5G。
- 三者部分线路经香港 / 新加坡出口，实际 IP 以分配为准。

> **一句话总结：** 长期主力选 [esim.cc 100GB 年卡](https://to.cm/esimcc)；短期小流量 [Stellar](https://to.cm/rsss) 更有性价比；防失联备用选 [BNESIM 永不过期套餐](https://to.cm/bnesim)。

---

## 三、eSIM 保号卡：低成本长期持有海外号码

保号卡指**月租极低甚至零月租、可在中国大陆长期漫游收短信**的海外 SIM/eSIM。用途：注册验证 WhatsApp / Telegram / Google、接收境外银行验证码、保留一个真实海外手机号。核心指标是**年持有成本、保号动作、eSIM 支持、大陆漫游收短信是否免费**。

| 卡 | 号码归属 | 年持有成本 | 保号动作 | eSIM | 大陆收短信 | 适合谁 |
| --- | --- | --- | --- | --- | --- | --- |
| 🇭🇰 **[Club SIM](https://www.theclub.com.hk/)** | 香港 +852 | **HK$6（≈¥5.6）** | 缴极低年费 | ✅ | 免费收 | 只要一个能收码的港号 |
| 🇭🇰 **[3HK DIY 储值卡](https://www.three.com.hk/)** | 香港 +852 | HK$36（≈¥33） | 年费套餐 | ✅ | 可收 | 要港号 + 可选流量 |
| 🇭🇰 **[SoSIM](https://www.sosim.hk/)** | 香港 +852 | ≤HK$40 | 按期充值 | ✅ | 可收 | 去港旅游顺便办卡 |
| 🇺🇸 **[Ultra PayGo](https://www.ultramobile.com/paygo/)** | 美国 +1 | $36（≈¥260） | 保持余额自动扣月费 | ✅ | 含 100 条/月 | 要真实美国号（GV 转移、通话） |
| 🇭🇰 **[Cuniq 月神卡](https://www.cuniq.com/)** | 香港 + 内地双号 | ¥108 | 月租自动扣 | ✅ | 双号可收 | 要港号 + 内地副号一步到位 |
| 🇲🇴 **[澳门电信蓝卡](https://www.1888.com.mo/home/index/)** | 澳门 +853 | **¥20** | 年充 ¥20 | —（以官网为准） | 免费收 | 常往大湾区 + 要流量永不过期 |

**亮点速览**

- **Club SIM（香港 csl / HKT 系）** —— 年成本最低，一年 HK$6 保留 852 号码，大陆漫游免费收短信；eSIM 开卡 HK$50 起，远程可办；港股券商、港区 App Store 实用。
- **Ultra Mobile PayGo（美国 T-Mobile「紫卡」）** —— $3/月含 100 分钟 + 100 短信 + 100MB，真实美国号，可做 Google Voice 载体，支持 WiFi Calling，可自助转 eSIM 版。
- **3HK DIY** —— 纯保号 HK$36/年；HK$120/年 档含 12GB 本地 + 12GB 社交流量，保号与流量可分开购买。
- **SoSIM（3HK 旗下）** —— 买卡 HK$33 即含首月 50GB 本地流量 + 1500 分钟，开卡 48 小时内可免费转漫游。
- **Cuniq 月神卡（中国联通香港）** —— ¥9/月一卡双号，港号 + 内地副号一步到位，实名要求较高。
- **澳门电信蓝卡** —— 零月租，流量在**内地 / 香港 / 澳门三地共用**且**永不过期**，每年 ¥20 保号。

> \* 数据采集于 2026 年 7 月官网与社区教程。收短信属正常国际漫游业务，但运营商可能清理长期漫游用户（如 Giffgaff 2026 年的动作），实名 / 地址要求各不相同，请以官网最新条款为准。

### 保号卡和 eSIM 实体卡是什么关系？

**互补关系**：保号卡是**号码**（低成本持有海外手机号），实体卡是**容器**（让不支持 eSIM 的手机能装 eSIM）。手机不支持 eSIM 时，可把 Giffgaff / Club SIM 的 eSIM 版下载到 ESTK、9eSIM 这类实体卡里——**一张卡装下所有保号号码**。

---

## 四、eSIM 使用教程

### 1）第一次用实体卡：通用写卡流程（约 10 分钟）

1. **选卡并插入手机** —— 按上面的参数对比表挑一张适合你手机的卡，像普通 SIM 卡一样插入卡槽。
2. **安装管理工具** —— 各家不同：官方 App（XeSIM 等）、开源 LPA（9eSIM / ESTK 可用 NekokoLPA、MiniLPA 等）、微信小程序（BeeSIM）。
3. **购买 eSIM 套餐** —— 下单后会拿到激活二维码或 `LPA:1$…` 格式的激活码。
4. **写入 Profile** —— 在管理工具里扫码或粘贴激活码，把 Profile 下载到卡里（此时手机需要另一路网络，如 Wi-Fi）。
5. **启用并联网** —— 选中刚写入的 Profile 启用，在系统设置里打开蜂窝数据和数据漫游即可上网。

### 2）国行 iPhone 玩法要点

国行 iPhone 的 eSIM 被禁用但卡槽正常，也装不了安卓 App，三条路任选：

- **STK 菜单切换（最通用）** —— ESTK / 9eSIM / XeSIM 都支持：插卡后在「设置 → 蜂窝网络 → SIM 卡应用程序」里就能看到卡片菜单，直接切换 Profile，**不需要任何 App**。
- **蓝牙管理（最直观）** —— BeeSIM 内置蓝牙芯片，微信小程序连卡即可写入、切换，全程 iPhone 完成。
- **免安卓写卡** —— XeSIM X2 Pro 支持纯 iPhone 独立写卡；ESTK 也可借配套读卡器在电脑上写。其余卡型首次写入时借一台安卓机最省事。

### 3）流量套餐：购买与激活

1. **提前购买** —— 对比 esim.cc、Superalink、BNESIM 后下单（注意激活时限与购买资格，如 esim.cc 需在购买后 90 天内激活）。
2. **提前写入** —— 拿到二维码就可以把 Profile 装进手机或实体卡，不会立即计费——多数套餐首次连上当地网络才开始计时。
3. **落地启用** —— 到达后启用对应 Profile、打开数据漫游，几分钟内自动注册上网。
4. **直连国际网络** —— 这类漫游套餐经国际出口回传，Google / ChatGPT 直接可用，无需 VPN，也无需实名。
5. **热点共享** —— 以套餐页实时规则为准；esim.cc 支持热点，Superalink 当前为每天最多共享 2GB。

### 4）eSIM 保号卡：留一个海外号码

1. **选号码归属地** —— 只要收码选港号（Club SIM 年费最低）；要真实美国号选 Ultra Mobile PayGo。
2. **eSIM 版下载到实体卡** —— 手机不支持 eSIM 时，把保号卡的 eSIM 版写入 ESTK / 9eSIM 等实体卡，一张卡装下所有号码。
3. **记住保号动作** —— 各家不同：缴年费、定期充值或半年一次余额变动，错过会被回收号码。

📖 完整图文版教程：<https://esim.ss/#guide>

---

## 常见问题 FAQ

<details>
<summary><b>国行 iPhone 到底能不能用 eSIM？</b></summary>

国行 iPhone 的 eSIM 功能被禁用，但**物理卡槽是正常的**。把 eSIM Profile 写进一张 eSIM 转实体卡（ESTK / 9eSIM / XeSIM / BeeSIM），插进卡槽即可当普通 SIM 卡用，并可通过 STK 菜单、蓝牙小程序或读卡器切换号码。
</details>

<details>
<summary><b>eSIM 转实体卡合法吗？会不会一次性？</b></summary>

它是符合 GSMA eUICC 标准的可复写 SIM 卡，本质与运营商发行的 eSIM 芯片同源。除 XeSIM X1（限 5 次下载）外，本文推荐的卡型均**不限写入次数**，可反复擦写。
</details>

<details>
<summary><b>一张卡能存几个号码？</b></summary>

取决于容量：BeeSIM 约 8–9 个，9eSIM 15/30/50 个，XeSIM 15/30 个，ESTK 最高 60 个。同一时间只能**激活一个** Profile，其余处于休眠状态，可随时切换。
</details>

<details>
<summary><b>中国大陆用 eSIM 流量套餐需要实名吗？需要 VPN 吗？</b></summary>

推荐的三个套餐均为**国际漫游**性质，无需中国实名；数据经国际出口回传，Google / ChatGPT / TikTok 直接可用，**不需要额外 VPN**。
</details>

<details>
<summary><b>保号卡在国内能收到验证码吗？</b></summary>

可以，收短信属正常国际漫游业务。Club SIM、澳门电信蓝卡在大陆漫游收短信免费，Ultra PayGo 每月含 100 条。但运营商可能清理长期只漫游不使用的用户，请留意各家保号动作。
</details>

<details>
<summary><b>套餐提前买了会马上开始计时吗？</b></summary>

多数套餐**首次连上当地网络才开始计时**，可以出发前就买好并写入卡里。注意部分套餐有激活时限（如 esim.cc 需在购买后 90 天内激活）。
</details>

---

## 名词表

| 术语 | 含义 |
| --- | --- |
| **eSIM** | 嵌入式 SIM，通过下载 Profile 而非插卡来开通号码 |
| **eUICC** | 支持远程配置、可存放多个 Profile 的 SIM 芯片标准 |
| **Profile** | 一个运营商号码/套餐的配置包，写入 eUICC 后即可使用 |
| **LPA** | Local Profile Assistant，负责下载/切换 Profile 的客户端（如 lpac、OpenEUICC、MiniLPA、NekokoLPA） |
| **STK** | SIM Tool Kit，SIM 卡自带的系统级菜单，iPhone 上位于「设置 → 蜂窝网络 → SIM 卡应用程序」 |
| **SM-DP+** | 运营商侧的 Profile 下发服务器，`LPA:1$…` 激活码中的地址即指向它 |
| **5G SA** | 5G 独立组网 |

---
```

内容有更新、价格有变动、发现失效链接，欢迎提 [Issue](https://github.com/FreeyW/esim.ss/issues) 或 PR。觉得有用的话，点个 ⭐ Star 让更多人看到。

---

## 免责声明

本站为**独立评测网站**，与文中任何品牌无隶属关系；所有商标归各自所有者。购买链接含本站推广/优惠标识，通过这些链接下单不会增加你的成本。

内容仅供参考，**价格、套餐与政策以各官网实时信息为准**。跨境通信服务受当地法规约束，请在遵守所在地法律法规的前提下使用。

© 2026 [eSIM.ss](https://esim.ss/)

---

<sub>**关键词：** eSIM 实体卡 · eSIM 转实体卡 · eUICC 可复写卡 · 国行 iPhone eSIM · ESTK · 9eSIM · XeSIM · BeeSIM · 中国 eSIM 流量套餐 · esim.cc · BNESIM · Stellar · 海外保号卡 · Club SIM · Ultra Mobile PayGo · 3HK · SoSIM · Cuniq · 澳门电信蓝卡 · 写卡教程 · LPA · STK · 数字移民</sub>
