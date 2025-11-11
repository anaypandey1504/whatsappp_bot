# 💬 whatsapp_bot

## 📘 Overview

**whatsapp_bot** is a **Node.js-powered interactive chatbot** that automates message delivery, course management, or notifications through **WhatsApp**.  
It enables users or organizations to send daily updates, reminders, and messages using the **WhatsApp Business API** — making learning, engagement, or communication more accessible and automated.

---

## 🚀 Features

- Automatically sends scheduled messages to users on WhatsApp.  
- Supports template-based messages to stay compliant with WhatsApp session policies.  
- Integrates with external databases (like Airtable) for dynamic message content.  
- Can be deployed easily to cloud platforms such as **Railway**, **Render**, or **Vercel**.  
- Built with scalability and modularity in mind.

---

## 🎥 Demo  
*(Add your demo video or screenshots here)*  
Example: `Demo.Video.mp4`

---

## ⚙️ Tech Stack

| Component | Description |
|------------|--------------|
| **Node.js** | Backend runtime for building fast, scalable applications. |
| **Express.js** | Framework used to handle API routes and server logic. |
| **WhatsApp Business API** | Enables sending and receiving messages at scale with customers or learners. |
| **Airtable** | Used as a backend database to store and manage user and course data. |
| **Railway** | Platform for simple, one-click deployment of Node.js apps. |

---

## 🧰 Prerequisites

Before running the bot, make sure you have:

- ✅ WhatsApp Business API account (via WATI or similar provider)  
- ✅ Airtable account  
- ✅ Railway (or any cloud hosting service) account  

---

## 🔑 Setup & Configuration

### 1. Clone the repository
```bash
git clone https://github.com/anaypandey1504/whatsappp_bot.git
cd whatsappp_bot
2. Install dependencies
bash
Copy code
npm install
3. Configure environment variables
Rename the .env_example file to .env and fill in the required values:

ini
Copy code
API=<your_wati_access_token>
apiKey=<your_airtable_api_key>
base=<your_airtable_base_id>
URL=<your_wati_server_url>
4. Run the bot locally
bash
Copy code
npm start
☁️ Deployment Guide (Railway)
Create a new GitHub repository for the bot.

Log in to your Railway account.

Click New Project → Deploy from GitHub repo.

Link your GitHub repository containing the bot.

Add all environment variables under the Variables section.

Click Deploy Now.

Your WhatsApp bot will automatically start after deployment 🎉.

🧩 Notes
WhatsApp sessions expire after 24 hours of the user's last message.
After this, you can only send template messages until the user replies.

Use a cron job or scheduler to send automated template messages daily.

👥 Author
Developed by: Anay Pandey
📧 Email: anaypandey1504@gmail.com
🐙 GitHub: @anaypandey1504

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to submit a pull request or open an issue.

⭐ Show Your Support
If this project helped you, please give it a ⭐ on GitHub — it means a lot!

