# 🚗 Vehicle Builder CLI - TypeScript + OOP

This is a command-line application built with TypeScript that allows users to create and interact with different types of vehicles: **Cars**, **Trucks**, and **Motorbikes**. The app uses **Object-Oriented Programming (OOP)** principles and the **Inquirer** package for user prompts.

## 📹 Walkthrough Video

👉 [Watch the demo here](https://app.screencastify.com/v3/watch/Qn7kTSB3SKa02WLhZoos)

---

## 🛠 Features

- Create new vehicles: Car, Truck, or Motorbike
- Select existing vehicles
- Perform actions unique to each vehicle type
- View results of those actions in the terminal
- Loop back to perform multiple actions or exit the app

---

## 🚀 How to Run

Make sure you have **Node.js** and **npm** installed.

1. Clone the repo
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the app:
   ```bash
   npm start
   ```

---

## 📦 Technologies Used

- [TypeScript](https://www.typescriptlang.org/)
- [Inquirer](https://www.npmjs.com/package/inquirer)
- OOP: Classes and Inheritance
- Node.js

---

## 🧱 Vehicle Types and Actions

### 🚙 Car
- Basic vehicle creation and common actions

### 🛻 Truck
- Includes additional prompts (e.g., load capacity)
- Unique action: **Load Cargo**

### 🏍 Motorbike
- Includes additional prompts (e.g., hasSidecar)
- Streamlined, fast-action behavior

---

## 📁 File Structure

```
├── src/
│   ├── vehicles/
│   │   ├── Car.ts
│   │   ├── Truck.ts
│   │   └── Motorbike.ts
│   ├── index.ts
│   └── prompts.ts
├── tsconfig.json
├── package.json
└── README.md
```

---

## 🧑‍💻 Author

Created by a developer for educational and practice purposes with TypeScript and OOP.

---

## ✅ License

This project is licensed under the MIT License.

---
