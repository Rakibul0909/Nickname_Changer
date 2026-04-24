💎 Free Fire Nickname Changer API

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask-API-black?style=for-the-badge">
</p><p align="center">
  ⚡ Modify Free Fire Nicknames using UID, Access Token, or JWT ⚡
</p>---

🚀 Features

- 🔐 Guest Login (UID + Password)
- 🔑 Access Token authentication
- 🪙 Direct JWT support
- ⚡ Fast & lightweight Flask API
- 📦 AES Encryption + Protobuf support
- 📊 Detailed JSON response

---

📡 Base URL

http://127.0.0.1:5001

---

📥 API Usage

🔐 Guest Login (UID + Password)

/guest?uid={uid}&password={password}&name={new_name}

---

🔑 Access Token Method

/token?access_token={access_token}&name={new_name}

---

🪙 JWT Token Method

/token?jwt={jwt_token}&name={new_name}

---

🌐 Example Requests

http://127.0.0.1:5001/guest?uid=123456789&password=yourpassword&name=NewName

http://127.0.0.1:5001/token?access_token=YOUR_ACCESS_TOKEN&name=NewName

http://127.0.0.1:5001/token?jwt=YOUR_JWT_TOKEN&name=NewName

---

📤 Response Format

{
  "metadata": {
    "author": "@INDRAJIT_1M & @spideyabd",
    "timestamp": "YYYY-MM-DD HH:MM:SS"
  },
  "response_status": "SUCCESS",
  "operation_message": "Nickname successfully changed!",
  "http_status_code": 200,
  "account_details": {
    "account_id": "123456789",
    "old_name": "OldNick",
    "new_name": "NewNick",
    "region": "IND",
    "release_version": "OB53",
    "authentication_method": "TOKEN_BASED_AUTH"
  },
  "server_feedback": {
    "headers": {},
    "raw_hexadecimal": "",
    "plaintext_response": ""
  }
}

---

⚙️ Installation

git clone https://github.com/yourusername/ff-nickname-api.git
cd ff-nickname-api
pip install -r requirements.txt
python app.py

---

🧪 Requirements

- Python 3.8+
- Flask
- requests
- pycryptodome
- protobuf

---

🧠 How It Works

1. Authenticate (UID / Token / JWT)
2. Convert → JWT (if needed)
3. Encrypt payload using AES
4. Send request to game server
5. Return structured JSON response

---

⚠️ Important Notes

- ❗ For educational purposes only
- ❌ Do not misuse or access accounts without permission
- ⚡ May violate game policies if abused
- 🔒 Keep credentials secure

---

👨‍💻 Credits

- @INDRAJIT_1M
- @spideyabd

---

📢 Join Telegram (Click Below)

<p align="center">
  <a href="https://t.me/INDRAJITFREEAPI">
    <img src="https://img.shields.io/badge/Join%20Telegram-INDRAJITFREEAPI-2CA5E0?style=for-the-badge&logo=telegram">
  </a>
</p><p align="center">
  <a href="https://t.me/SPIDEYFREEFILES">
    <img src="https://img.shields.io/badge/Join%20Telegram-SPIDEYFREEFILES-2CA5E0?style=for-the-badge&logo=telegram">
  </a>
</p>---

⭐ Support

If you like this project, give it a ⭐ on GitHub and share it!

---