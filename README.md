# 🇺🇸 US Visa Appointment Slot Monitor (London / Belfast)  
# 🇨🇳 美国签证预约空位监控（伦敦 / 贝尔法斯特）

> A Tampermonkey script to automatically monitor US visa appointment availability in the UK (Aug–Oct 2025), with notifications and email alerts.  
> 一个用于自动监控英国地区美国签证预约空位的油猴脚本（2025 年 8–10 月），支持通知提醒和邮件推送。

---

## ✨ Features / 功能特色

- ✅ Monitors visa appointment availability in **London** and **Belfast**  
  ✅ 支持检测 **伦敦** 和 **贝尔法斯特** 的预约情况  
- 📅 Targets **August – October 2025** only  (Change what you want)
  📅 仅监控 **2025 年 8 月至 10 月** 的可用日期  (可以改成你自己需要的日期)
- 🔁 Checks every 2 minutes, simulates city switch every 90 minutes  
  🔁 每两分钟自动轮询一次，每 90 分钟模拟切换城市防止锁定  
- 🔔 Desktop notification + 📧 Email alert + 🎵 Sound alert  
  🔔 桌面通知 + 📧 邮件提醒 + 🎵 声音提示  
- 💻 Injects automatically when entering the appointment page  
  💻 进入预约页面后自动注入脚本并启动监控

---

## 📦 Installation / 安装步骤

1. Install [Tampermonkey](https://www.tampermonkey.net/) browser extension  
   安装 [Tampermonkey 油猴插件](https://www.tampermonkey.net/)  
2. Create a new userscript and paste contents of `monitor_inject.js`  
   创建新脚本并粘贴 `monitor_inject.js` 的全部内容  
3. Save and open your [visa appointment page](https://ais.usvisa-info.com/en-gb/niv/schedule/)  
   保存脚本后打开 [签证预约页面](https://ais.usvisa-info.com/en-gb/niv/schedule/)  
4. The script starts running automatically  
   脚本将自动运行并开始监控空位

---

## 📧 Email Alerts / 邮件提醒设置

The script uses [Formspree](https://formspree.io/) to send email alerts.  
该脚本使用 Formspree 免费服务发送邮件提醒，你需要注册自己的账户以获得免费邮件次数。

- Replace the `EMAIL_ENDPOINT` field with your own Formspree endpoint  
  将 `EMAIL_ENDPOINT` 字段替换为你自己的 Formspree 地址  
- You can test email delivery from your browser's dev console  
  可通过浏览器开发者工具控制台测试邮件发送功能

---

## 🛡️ Disclaimer / 使用声明

This script is intended for **personal, non-commercial use only**.  
本脚本仅供**个人学习和非商业用途**。请勿滥用或违反网站服务条款。

作者不对任何由于脚本使用所导致的问题承担责任。  
Use responsibly and at your own risk.

---

## 📄 License / 许可证

MIT License  
自由使用、修改和分发，但请保留作者信息和许可证内容。

---

## ✍️ Author / 作者

Xi
[GitHub](https://github.com/aca22jy)｜欢迎提 issue 或 PR 改进脚本！

