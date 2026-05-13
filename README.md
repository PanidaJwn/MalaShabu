# 🐷 MalaShabu - Restaurant Management System

A Java Swing desktop application for managing a Shabu restaurant — handling menu items, employees, and orders with a simple file-based storage system.

---

## 📸 Screenshots

### Login & Main Menu
| Login | Main Menu |
|-------|-----------|
| ![Login](screenshots/Screenshot_2023-12-13_171449.png) | ![Main Menu](screenshots/Screenshot_2023-12-13_171615.png) |

### Item Management
| Item Management Menu | Add Item |
|----------------------|----------|
| ![Item Management](screenshots/Screenshot_2023-12-13_171719.png) | ![Add Item](screenshots/Screenshot_2023-12-13_171929.png) |

| View Item | Delete Item | Update Item |
|-----------|-------------|-------------|
| ![View Item](screenshots/Screenshot_2023-12-13_172240.png) | ![Delete Item](screenshots/Screenshot_2023-12-13_172401.png) | ![Update Item](screenshots/Screenshot_2023-12-13_172449.png) |

### Employee Management
| Employee List | Add Employee |
|---------------|--------------|
| ![Employee List](screenshots/Screenshot_2023-12-13_172812.png) | ![Add Employee](screenshots/Screenshot_2023-12-13_173718.png) |

| Remove Employee | Change Employee Data | Employee Detail |
|-----------------|----------------------|-----------------|
| ![Remove](screenshots/Screenshot_2023-12-13_173926.png) | ![Change](screenshots/Screenshot_2023-12-13_173951.png) | ![Detail](screenshots/Screenshot_2023-12-13_173747.png) |

### Order Management
| Order Management |
|------------------|
| ![Order Management](screenshots/Screenshot_2023-12-13_174101.png) |

---

## ✨ Features

- **Authentication** — Login system with auto-lock after 3 failed attempts
- **Item Management** — Add, view, update, and delete menu items
- **Employee Management** — Manage staff records (Full-time & Part-time)
- **Order Management** — Create and manage customer orders
- **File-based Storage** — Data stored in plain `.txt` files, no database required

---

## 🛠️ Tech Stack

- **Language:** Java
- **UI Framework:** Java Swing (NetBeans Form Designer)
- **Storage:** File-based (`.txt`)
- **Build Tool:** Apache Ant (`build.xml`)
- **IDE:** NetBeans / VS Code

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 8 or higher
- VS Code + [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

### Run the App

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/MalaShabu.git
cd MalaShabu
```

2. Open `src/MalaShabu/system/Main.java` in VS Code

3. Right-click → **Run Java**

Or using Ant:
```bash
ant run
```

---

## 🔑 Default Credentials

```
Username : admin
Password : 1234
```

> ⚠️ The system will exit automatically after 3 incorrect login attempts.

---

## 📁 Project Structure

```
MalaShabu/
├── src/
│   └── MalaShabu/
│       ├── component/
│       │   ├── auth/          # Login screen
│       │   ├── item/          # Item management screens
│       │   ├── Employee/      # Employee management screens
│       │   └── order/         # Order management screens
│       ├── model/             # Data classes (Item, Order, etc.)
│       ├── service/           # Business logic
│       └── system/            # Main entry point & Main Menu
├── storage/                   # Data files (.txt)
├── screenshots/               # App screenshots
├── build.xml
└── README.md
```

---

## 📂 Data Storage

All data is stored in the `storage/` folder as comma-separated text files:

| File | Content |
|------|---------|
| `item.txt` | Item name, price, quantity |
| `order.txt` | Order records |
| `orderLine.txt` | Order line items |
| `labour.txt` | Employee records |

---

## 👨‍💻 Author

Developed as a university Programming course project.
