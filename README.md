<div align="center">
  <img src="https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions/blob/main/logo.png" width="128" height="128" alt="Project Logo">
  <h1>解除复制限制 (Lift Copy Restrictions)</h1>
  <p>一个旨在智能解除网页复制限制的油猴脚本。</p>
  
  <p>
     <a href="https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions">
      <img src="https://img.shields.io/badge/GitHub-仓库-blue?style=flat-square&logo=github" alt="GitHub Repo"></a>
    </a>
    <a href="https://greasyfork.org/zh-CN/scripts/543456-%E8%A7%A3%E9%99%A4%E5%A4%8D%E5%88%B6%E9%99%90%E5%88%B6-lift-copy-restrictions"> <img src="https://img.shields.io/badge/GreasyFork-发布-green?style=flat-square&logo=git" alt="GreasyFork"></a>
    </a>
    <a href="https://openuserjs.org/scripts/%E9%80%90%E6%A2%A6%E6%98%9F%E8%BE%B0%E5%A4%A7%E6%B5%B7/%E8%A7%A3%E9%99%A4%E5%A4%8D%E5%88%B6%E9%99%90%E5%88%B6_Lift_Copy_Restrictions"> <img src="https://img.shields.io/badge/OpenUserJS-发布-orange?style=flat-square&logo=javascript" alt="OpenUserJS"></a>
    </a>
    <br>
    <img src="https://img.shields.io/github/package-json/v/zhumengstarsandsea/Lift_Copy_Restrictions?style=flat-square" alt="Version">
    <img src="https://img.shields.io/badge/JavaScript-100%25-yellow?style=flat-square" alt="Language">
    <a href="https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/zhumengstarsandsea/Lift_Copy_Restrictions?style=flat-square" alt="License">
    </a>
  </p>
</div>

---

## 📖 简介 (Introduction)

本脚本尝试解决各种网站上“禁止复制”的恼人问题，对专项支持网站自动采用专用解方案，对其他网站则提供通用方案。


## 🎯 专项支持网站 (Specially Supported Websites)

脚本会自动识别并激活以下网站的专用方案：

| 网站平台 (Platform) | 适用域名 (Domain) |
| :--- | :--- |
| **百度文库** (Baidu Wenku) | `wenku.baidu.com`、`wk.baidu.com` |
| **知乎** (Zhihu) | `zhihu.com` |
| **腾讯文档** (Tencent Docs) | `docs.qq.com` |
| **金山文档** (Kingsoft Docs) | `kdocs.cn` |
| **道客巴巴** (Doc88.com) | `doc88.com` |
| **SegmentFault** | `segmentfault.com` |

---

## 🚀 安装 (Installation)

1.  首先，您的浏览器需要安装一个用户脚本管理器。推荐使用 <img src="https://www.tampermonkey.net/images/icon.png" height="16" alt="Tampermonkey Logo" style="vertical-align: -0.2em;"> **Tampermonkey**。
    * <img src="https://upload.wikimedia.org/wikipedia/commons/9/98/Microsoft_Edge_logo_%282019%29.svg" height="16" alt="Edge Logo" style="vertical-align: -0.2em;"> [Edge 安装链接](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
    * <img src="https://upload.wikimedia.org/wikipedia/commons/e/e1/Google_Chrome_icon_%28February_2022%29.svg" height="16" alt="Chrome Logo" style="vertical-align: -0.2em;"> [Chrome 安装链接](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Firefox_logo%2C_2019.svg" height="16" alt="Firefox Logo" style="vertical-align: -0.2em;"> [Firefox 安装链接](https://addons.mozilla.org/firefox/addon/tampermonkey/)

3.  然后，从以下任一地址安装本脚本：

    *  <img src="https://github.com/greasyfork-org/greasyfork/blob/main/public/images/blacklogo32.png" height="16" alt="GreasyFork Logo" style="vertical-align: -0.2em;"> **[GreasyFork](https://greasyfork.org/zh-CN/scripts/543456-%E8%A7%A3%E9%99%A4%E5%A4%8D%E5%88%B6%E9%99%90%E5%88%B6-lift-copy-restrictions)** (推荐，稳定发布版)
    * <img src="https://github.com/fluidicon.png" height="16" alt="GitHub Logo" style="vertical-align: -0.2em;"> **[GitHub](https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions/releases/tag/new)** (获取最新开发版)
    *  <img src="https://github.com/OpenUserJS/OpenUserJS.org/blob/master/public/images/favicon32.png" height="16" alt="OpenUserJS Logo" style="vertical-align: -0.2em;"> **[OpenUserJS](https://openuserjs.org/scripts/%E9%80%90%E6%A2%A6%E6%98%9F%E8%BE%B0%E5%A4%A7%E6%B5%B7/%E8%A7%A3%E9%99%A4%E5%A4%8D%E5%88%B6%E9%99%90%E5%88%B6_Lift_Copy_Restrictions)** (备用发布地址)
---

## 🛠️ 使用说明 (Usage)

-   **专项网站**: 当您访问**特殊网站**时，脚本会自动运行并解除限制，您无需进行任何操作。
-   **通用网站**: 当您在某个其他网站遇到复制限制时：
    1.  点击浏览器右上角的 <img src="https://www.tampermonkey.net/images/icon.png" height="16" alt="Tampermonkey Logo" style="vertical-align: -0.2em;"> **Tampermonkey** 图标。
    2.  在菜单中点击 **“✅ 加入解除名单”**。
    3.  页面将自动刷新，顺利的话该网站复制限制便会被解除。
    4.  若要让脚本在某个已加入的网站上停止工作，只需再次访问该网站，并在油猴菜单中点击 **“❌ 移出解除名单”** 即可。
-   **查看日志**: 按 `F12` 打开浏览器开发者工具，切换到 `Console` (控制台) 标签页，即可查看脚本输出的工作日志。

---

## 🤝 贡献与反馈 (Contributing & Feedback)

欢迎通过 <img src="https://github.com/fluidicon.png" height="16" alt="GitHub Logo" style="vertical-align: -0.2em;"> **[GitHub Issues](https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions/issues)** 来报告BUG或提出功能建议！

如果您觉得这个脚本对您有帮助，请给这个项目一个 ⭐ Star！您的支持是作者更新的最大动力！

## 📄 许可证 (License)

本项目采用 [AGPL-3.0](https://github.com/zhumengstarsandsea/Lift_Copy_Restrictions/blob/main/LICENSE) 许可证。
