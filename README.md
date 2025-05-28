# 📰 Desktop News Notifier

A lightweight Python 🐍 desktop app that fetches top news 🗞️ from Hindustan Times via RSS 🌐 and displays them as pop-up desktop notifications 💻🔔 using `notify2`. Stay updated 📡 in real-time ⏱️ from your Ubuntu desktop 🧾🧠!

## ✨ Features
- 📡 Real-time news headlines from RSS feed
- 🧠 Lightweight and minimal
- 🔔 System pop-up notifications using `notify2`
- 🛠️ Simple, readable code

## 📸 Preview
![Preview](./screenshot.png) <!-- Replace with actual screenshot path if available -->

## 📦 Requirements
- Python 3.x 🐍
- `requests` 📡
- `notify2` 🔔

Install dependencies using pip:
```bash
pip install requests notify2
```

🛠️ Usage

1. Clone the repository:
  
  git clone https://github.com/aniketmondal1210/Desktop-News-Notifier.git
  cd Desktop-News-Notifier

2. Replace the ICON_PATH in notifier.py with the full path to your icon image 🖼️.

3. Run the app:
   python notifier.py

📁 Project Structure
├── notifier.py       # Main script for showing notifications
├── topnews.py        # Fetches and parses RSS news feed
├── screenshot.png    # Optional screenshot of app in action
└── README.md         # Project documentation

🙌 Contributing

Feel free to fork 🍴 the repo and submit a pull request 🤝 to enhance features or fix bugs.
📜 License

This project is open-source under the MIT License.
Made with ❤️ by Aniket Mondal
