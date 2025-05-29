# 💱 Currency Converter App

A simple and responsive currency converter built with **React** and **Tailwind CSS**. This application allows users to convert amounts between different currencies using real-time exchange rates fetched from a public API.

## 🚀 Features

- Convert between 150+ currencies
- Swap functionality to reverse conversion
- Real-time exchange rates via public API
- Responsive UI with Tailwind CSS
- Custom React hook for API handling (`useCurrencyInfo`)

---

## 🛠️ Tech Stack

- **React** (Functional Components + Hooks)
- **Tailwind CSS** (Utility-first CSS Framework)
- **JavaScript**
- **Public Currency API** from [@fawazahmed0/currency-api](https://github.com/fawazahmed0/currency-api)

---

## 📂 Project Structure

```bash
src/
│
├── components/
│   └── InputBox.jsx        # UI component for currency input
│
├── hooks/
│   └── useCurrencyInfo.js  # Custom hook for fetching exchange rates
│
└── App.jsx                 # Main app component
````

---

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Mithilesh-27/Currency-Converter.git
   cd Currency-Converter
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Open in browser:**

   ```
   http://localhost:5173
   ```

---

## 🌐 API Reference

Data is fetched from:
[https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/)

---

## 🙏 Acknowledgement

This project is built by following Hitesh Choudhary on Chai aur Code. I’ve made a few customizations for learning purposes.

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).
