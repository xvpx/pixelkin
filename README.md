# 🧬 Pixelkin

## 🌟 Project Overview
Pixelkin is a locally hosted wallpaper website that provides users with a modern interface for browsing, searching, and generating wallpapers. The project leverages local AI services for tagging and generating wallpapers, offering a unique and personalized experience for users.

## 📁 Project Structure
```
pixelkin/
├── README.md
├── PRD.md
└── .gitignore (to be created)
```

## 📄 Product Requirements Document
For detailed information about the project requirements, features, and technical specifications, please refer to the [PRD.md](./PRD.md) file.

## 🛠️ Setup
(To be completed when project development begins)

## 📦 Deployment
### Initial Server Setup
1. Install Git on the Windows server if not already installed
2. Clone the repository:
   ```powershell
   git clone https://github.com/xvpx/pixelkin.git
   cd pixelkin
   ```
3. Install project dependencies:
   ```powershell
   npm install
   ```

### Updating the Server
To pull the latest changes from GitHub:
1. Open PowerShell on the server
2. Navigate to the project directory:
   ```powershell
   cd path\to\pixelkin
   ```
3. Pull the latest changes:
   ```powershell
   git pull origin main
   ```
4. Install any new dependencies:
   ```powershell
   npm install
   ```
5. Restart the application (if using PM2):
   ```powershell
   pm2 restart pixelkin-app
   ```

## 🚀 Usage
(To be completed when project development begins)

## 🔑 Key Features
- Modern, responsive website layout
- AI-powered tagging system using Ollama with LLaVA
- Wallpaper generation using Stable Diffusion
- Local hosting on a Windows server (IP: 192.168.0.65)
- Tag-based search and filtering

## 🤝 Contributing
(To be defined when project development begins)

## 📜 License
(To be defined when project development begins)
