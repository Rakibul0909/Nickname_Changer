

# 💎 Free Fire Nickname Changer API

⚡ Change Free Fire Nicknames via UID, Access Token, or JWT ⚡

---

## 🚀 Features

🔐 Guest Login (UID + Password) 🔑 Access Token Support 🪙 JWT Token Support ⚡ Fast Flask API 🔒 AES + Protobuf Encryption 📊 Clean JSON Responses

---

## 📡 Base URL

http://127.0.0.1:5001

---

## 📥 API Endpoints

GET /guest?uid={uid}&password={password}&name={new_name}

GET /token?access_token={access_token}&name={new_name}

GET /token?jwt={jwt_token}&name={new_name}

---

## 🌐 Example Requests

http://127.0.0.1:5001/guest?uid=123456789&password=yourpassword&name=NewName

http://127.0.0.1:5001/token?access_token=YOUR_ACCESS_TOKEN&name=NewName

http://127.0.0.1:5001/token?jwt=YOUR_JWT_TOKEN&name=NewName

---

## 📤 Response Format

```json
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

Python 3.8+
Flask
requests
pycryptodome
protobuf


---

🏷️ Tags

FreeFire API
Nickname Changer
Flask API
Gaming Tools
Python API


---

👨‍💻 Credits

@INDRAJIT_1M
@spideyabd


---

🔗 Join Telegram

https://t.me/INDRAJITFREEAPI
https://t.me/SPIDEYFREEFILES


---

⚠️ Disclaimer

This project is for educational purposes only.
Use at your own risk.

---

Ab yeh **exact GitHub style README** hai:

✔ Har section copyable  
✔ Clean formatting  
✔ No extra garbage  
✔ Direct render perfect  

Agar chaho to next step me **0** bhi bana sakta hoon (pro README style).