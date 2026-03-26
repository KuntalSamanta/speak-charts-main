# 📊 Speak Charts – Conversational BI Dashboard

Speak Charts is a web-based Business Intelligence (BI) application that allows users to generate interactive dashboards using natural language queries.
Instead of writing SQL or using complex analytics tools, users can simply type their questions and instantly get visual insights.

---

## 🚀 Features

* 💬 **Natural Language Queries**
  Ask questions like:
  *"Show total revenue by region"*

* 📈 **Automatic Chart Generation**
  The system selects appropriate charts (bar, line, pie) based on the query.

* 📊 **Interactive Dashboard**
  View insights through dynamic and responsive visualizations.

* 🔄 **Conversational Follow-ups**
  Refine results with follow-up queries like:
  *"Now show only East region"*

* ⚡ **Real-Time Processing**
  Generates dashboards instantly from user input.

---

## 🧠 How It Works

1. User enters a query in plain English
2. The system analyzes the query using an AI model
3. Data is processed based on the dataset schema
4. Charts and metrics are generated automatically
5. Results are displayed in a dashboard

---

## 🏗️ Tech Stack

### Frontend

* React (Vite)
* TypeScript
* Tailwind CSS

### Backend

* Supabase (Edge Functions)

### AI Integration

* Google Gemini API

### Visualization

* Recharts / Chart Libraries

### Data Source

* CSV Dataset (Amazon Sales Data)

---

## 📂 Project Structure

```
project-root/
│
├── public/
│   └── data/
│       └── Amazon_Sales.csv
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   └── main.tsx
│
├── supabase/
│   └── functions/
│
├── index.html
└── README.md
```

---

## ▶️ Getting Started

### 1. Clone the Repository

```
git clone https://github.com/your-username/speak-charts.git
cd speak-charts
```

### 2. Install Dependencies

```
npm install
```

### 3. Run the Development Server

```
npm run dev
```

Open your browser at:
👉 http://localhost:8080/

---

## 📌 Example Queries

* Show total revenue by region
* Monthly sales trend for 2023
* Top 5 product categories by sales
* Compare sales across regions

---

## ⚠️ Limitations

* Works on a predefined dataset (CSV)
* Results depend on data quality
* Complex or ambiguous queries may give approximate results

---

## 🔮 Future Improvements

* Upload custom datasets (CSV support)
* Real database integration (SQL querying)
* Voice-based queries
* Advanced filtering and drill-down features
* Improved AI accuracy

---

## 👤 Author

**Kuntal Samanta**


---

## 📄 License

This project is for educational and demonstration purposes.
