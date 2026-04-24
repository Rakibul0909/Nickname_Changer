💎 Free Fire Nickname Changer API

A Flask-based API to modify player nicknames in Garena Free Fire using multiple authentication methods such as Guest Login, Access Token, and JWT.

---

🚀 Features

- 🔐 Guest Login (UID + Password)
- 🔑 Access Token based authentication
- 🪙 Direct JWT support
- ⚡ Fast and lightweight Flask API
- 📦 Protobuf + AES encrypted communication
- 📊 Detailed JSON response with diagnostics

---

📡 API Base URL

http://127.0.0.1:5001

---

📥 Usage

🔐 1. Using UID & Password (Guest Login)

/guest?uid={uid}&password={password}&name={new_name}

Example:

http://127.0.0.1:5001/guest?uid=123456789&password=yourpassword&name=NewName

---

🔑 2. Using Access Token

/token?access_token={access_token}&name={new_name}

Example:

http://127.0.0.1:5001/token?access_token=YOUR_ACCESS_TOKEN&name=NewName

---

🪙 3. Using JWT Token

/token?jwt={jwt_token}&name={new_name}

Example:

http://127.0.0.1:5001/token?jwt=YOUR_JWT_TOKEN&name=NewName

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

📤 Response Format

{
  "response_status": "SUCCESS",
  "operation_message": "Nickname successfully changed!",
  "account_details": {
    "account_id": "...",
    "old_name": "...",
    "new_name": "...",
    "region": "...",
    "authentication_method": "..."
  }
}

---

⚠️ Important Notes

- This project is for educational purposes only
- Do not misuse or attempt unauthorized access
- Using automation tools may violate game policies
- Always keep your credentials secure

---

🧠 How It Works

1. Authenticate using selected method
2. Convert credentials → JWT (if needed)
3. Encrypt request using AES
4. Send request to game server
5. Return structured response

---

👨‍💻 Credits

- @INDRAJIT_1M
- @spideyabd

---

📢 Community

Join for more tools & updates:

- https://t.me/INDRAJITFREEAPI
- https://t.me/SPIDEYFREEFILES

---

⭐ Support

If you like this project, give it a ⭐ on GitHub!