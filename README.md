
# 📊 Variable Impact Dashboard

This is an interactive dashboard built with **React** and **Tailwind CSS**, where users can adjust 5–7 variable sliders to influence a calculated **Main Score**. Each variable includes a value and a weight that determines its impact.

---

## 🚀 Features

- Adjustable sliders for value and weight of each variable
- Real-time calculation of a weighted score
- Responsive UI built with Tailwind CSS
- Modular components using the `shadcn/ui` pattern

---

## 🛠 Technologies

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)

---

## 📦 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/variable-impact-dashboard.git
   cd variable-impact-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run locally**
   ```bash
   npm run dev
   ```

4. **Deploy**
   - Recommended: [Vercel](https://vercel.com/import)

---

## 🧮 How It Works

Each variable has:
- **Value (0–100):** The input amount
- **Weight (0–5):** Multiplier indicating its influence

The **Main Score** is calculated as:

```
mainScore = Σ (value × weight) / 100
```
