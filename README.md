# Real-Time Chat App

A feature-rich real-time chat application where users can seamlessly communicate, share files, and interact with messages.

## 🚀 Features

- **Real-time messaging** powered by Socket.io
- **File sharing** (Images, PDFs, and Documents)
- **Emoji reactions** to messages
- **Edit & delete** messages
- **Offline notifications** with Twilio SMS service
- **Typing indicators**
- **User online/offline status**

## 🛠️ Tech Stack

- **Frontend:** React
- **Backend:** Node.js (Express)
- **Real-time communication:** Socket.io
- **Notifications:** Twilio

## 📁 Project Setup

### Clone the repository
```bash
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app
```

### Install dependencies
#### For backend
```bash
cd backend
npm install
```

#### For frontend
```bash
cd frontend
npm install
```

### Environment Variables
Create `.env` files in both `frontend` and `backend` directories and add the following:

#### Backend `.env`
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
```

#### Frontend `.env`
```
REACT_APP_BACKEND_URL=http://localhost:5000
```

### Run the app

#### Backend
```bash
cd backend
npm start
```

#### Frontend
```bash
cd frontend
npm start
```

The app will now run at `http://localhost:3000`

## 📸 Screenshots

_Add screenshots showcasing your app's features!_

## 🎯 Future Improvements

- Group chats
- Message read receipts
- Push notifications

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and create a pull request.

## 🧾 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


