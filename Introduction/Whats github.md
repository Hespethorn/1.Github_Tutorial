# CS 自学指南

> *Everyone should enjoy CS if you have a good teacher to teach you a good course.*

[![Website](https://img.shields.io/badge/website-csdiy.wiki-blue)](https://csdiy.wiki)
[![License](https://img.shields.io/github/license/PKUFlyingPig/cs-self-learning)](https://github.com/PKUFlyingPig/cs-self-learning/blob/master/LICENSE)
[![Issues](https://img.shields.io/github/issues/PKUFlyingPig/cs-self-learning)](https://github.com/PKUFlyingPig/cs-self-learning/issues)
[![Stars](https://img.shields.io/github/stars/PKUFlyingPig/cs-self-learning)](https://github.com/PKUFlyingPig/cs-self-learning)
GitHub 从注册到登录全流程 🚀

📝 注册账号  
步骤 1️⃣：访问官网  
打开浏览器，输入官网地址：  
https://github.com  
点击右上角 "Sign up"（注册）按钮。

!https://example.com/signup-button.png  


步骤 2️⃣：填写基本信息  
输入以下信息：  
Username（用户名）：全局唯一，后续无法修改  

Email（邮箱）：需真实有效（用于账号验证和找回密码）  

Password（密码）：至少 15 位，建议混合大小写字母和符号  

💡 小技巧：密码复杂度要求高？直接复制下方模板（替换字母）：  

Github_123@YourName

步骤 3️⃣：验证邮箱  
点击 "Continue" 后，GitHub 会发送验证邮件到你的邮箱  

打开邮箱，点击 "Verify your email address" 完成验证  

   (若未收到邮件，检查垃圾箱或等待 1-2 分钟)

步骤 4️⃣：完成注册  
根据提示选择个人使用场景（如 "I'm a developer"），点击 "Complete setup" 即可进入主页。

🔑 登录账号  
步骤 1️⃣：进入登录页  
访问 https://github.com/login  
输入已注册的 Username/Email 和 Password。

!https://example.com/login-page.png

步骤 2️⃣：两步验证（可选）  
如果开启了两步验证（2FA）：  
输入密码后，系统会要求输入动态验证码  

通过 Google Authenticator 或短信获取验证码  

⚠️ 安全建议：强烈推荐绑定手机并开启两步验证！

步骤 3️⃣：登录成功  
登录后默认进入 Dashboard（控制台），可查看关注的项目、通知和仓库列表。

❗ 常见问题处理  
问题 1：忘记密码  
在登录页点击 "Forgot password?"  

输入注册邮箱，GitHub 会发送重置链接  

按指引设置新密码  

问题 2：邮箱未收到验证邮件  
检查邮箱的 垃圾邮件/广告邮件 文件夹  

等待 5 分钟后刷新邮箱  

若仍未收到，点击登录页的 "Resend verification email"  

问题 3：账号被锁定  
频繁输错密码会导致账号临时锁定（15 分钟）  

等待锁定解除后重试  

🛠️ 登录后必备设置  
1️⃣ 修改个人资料  
点击右上角头像 → "Settings" → 可修改头像、姓名、简介等信息。

2️⃣ 绑定 SSH 密钥  
进入 Settings → SSH and GPG keys  

点击 "New SSH key" → 复制本地生成的 SSH 公钥  

      # 生成 SSH 密钥（终端执行）
   ssh-keygen -t ed25519 -C "your_email@example.com"
   cat ~/.ssh/id_ed25519.pub
   

3️⃣ 开启两步验证  
进入 Settings → Account security  

在 Two-factor authentication 中选择验证方式（推荐 Authenticator App）

🌐 其他登录方式  
GitHub CLI：通过命令行工具登录(这个俺目前也在学)

    gh auth login --scopes "repo,workflow"
  
第三方登录：支持 Google、GitHub Enterprise 等  

📌 温馨提示：  
登录后建议收藏常用链接：  

个人仓库：github.com/你的用户名  

新建仓库：github.com/new  

遇到问题优先查看 GitHub Status（状态页）(https://www.githubstatus.com)

  

