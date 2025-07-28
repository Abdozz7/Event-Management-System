# Virtual Meetings System

A C++-based virtual event management system designed to streamline the organization and participation in online events.this system offers a secure, scalable, and user-friendly experience for organizers and attendees alike.

---

## 🚀 Features

- 🔐 **User Authentication** (Signup/Login with email & password)
- 🧑‍💼 **Role Management** (Organizer vs. Participant)
- 📅 **Event Creation & Management** (Title, description, date, time)
- ✅ **Attendee Registration & Cancellation**
- 🕒 **Waiting List Support** (Auto-register when a slot opens)
- ⭐ **Feedback System** (Ratings and comments)
- 🔍 **Dynamic Search & Filters** (By name, date, organizer, type)
- 🧠 **Factory & Singleton Design Patterns** used for flexibility and control
- 💾 **SQLite3 Database Integration**

---

## 🛠️ Technologies Used

- **Language:** C++
- **Database:** SQLite3
- **Design Patterns:** Factory, Singleton
  
---

## 📂 Database Schema

- **Users**: User info (ID, email, name, affiliation)
- **Events**: Event details (title, time, date, type, capacity)
- **Event_Attendee**: Track user registrations
- **Feedback**: Ratings & comments by users
- **Waiting_List**: Manage overflow users for full events

---

## 🧑‍💻 How to Run

1. Install [CLion](https://www.jetbrains.com/clion/)
2. Open the project folder in CLion.
3. Run `main.cpp`, and the rest of the files will load automatically.
4. Sign up for a new account, or login if you already have one.
5. Enjoy full access to all features!

---

## 👥 Contributors

| Name                  | Major Contributions                         |
|-----------------------|---------------------------------------------|
| **Abdelrahman Essmat**| Event Manager, Registration, Waiting List   |
| **Seif Haytham**      | Event Creation, Dynamic Search, GUI version |
| **Ahmed Khairy**      | Event Creation, Registration                |
| **Abdulrahman Gomaa** | Code Integration, Database                  |
| **Maryam Rageh**      | User System, Feedback                       |

---

## 🙏 Acknowledgments

Special thanks to Dr. Shaymaa and everyone who supported us during this project.

