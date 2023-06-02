# AutoBangumi-go
该项目为个人使用的一个自动追番工具，其主要功能是从其它资源网站收集种子文件，通过重命名后推送给下载软件进行下载，文件通过重命名后可以直接被jellyfin直接识别  
通过配置要看的番剧名称，实现自动追番

该项目的宗旨是解放双手  

**注: 该项目永不收费, 用爱发电, 仅仅为了实现看番自由**

# 功能
- 支持Mikan站点
- 支持Qb下载器
- 支持订阅和补齐番剧
- 自动文件重命名
- 遵循分辨率与字幕语言优先规则
- 自动重新下载画质更高的剧集
- 支持使用TelegramBot 搜索番剧，然后自动追番

# 正在开发的功能
- [x] 接入Aria2
- [x] 接入pikpak, 支持多个pikpak免费账号/VIP账号
- [x] 实现智能下载器，默认使用QB下载, 如果有pikpak会员/免费账号，那么全部使用pikpak离线下载后转aria2，如果pikpak免费次数耗尽，则会交给QB下载, 如果QB下不动，则会自动转pikpak
- [ ] 支持里番下载（hanime）
- [ ] Web UI
- [ ] 接入种子站点 萌番组
- [ ] 接入种子站点 动漫花园
- [ ] 接入种子站点 nyaa
- [ ] 识别OVA, TV, 合集

# 免责声明
1. 本项目仅为一个自动化工具，用于收集互联网上分享的种子文件，并自动推送到下载工具进行下载。
2. 本项目的目的是为了提供便利，方便用户获取资源，但并不提供任何直接的下载功能。
3. 本项目仅收集互联网上已公开分享的种子文件，并不参与或控制这些种子文件的内容和来源。
4. 用户在使用本项目时，需自行判断和承担下载内容的合法性、适用性以及可能存在的风险。
5. 本项目的开发者和贡献者不对用户通过本项目获取的任何资源的合法性、准确性、完整性或安全性承担责任。
6. 本项目的开发者和贡献者不对用户在使用本项目过程中可能遭受的任何直接或间接损失或损害承担责任。
7. 用户在使用本项目时，需要遵守相关法律法规和平台规定，并承担因违反相关规定而可能产生的责任和后果。
8. 本项目可能会因为互联网环境、网站变更等因素导致功能失效或不稳定，对此我们不做任何保证。
9. 请在使用本项目之前仔细阅读和理解以上免责声明，并确保你同意并接受其中的条款和条件。如果你不同意或无法接受这些条款，请不要使用本项目。