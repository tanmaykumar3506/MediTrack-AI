# MediTrack AI 💊
### Pharmacy Management & Inventory Tracking System

MediTrack AI is a pharmacy management system developed to make daily pharmacy operations easier. It helps manage medicines, track inventory, record sales, and monitor expiry dates.

The project also includes a Machine Learning feature that analyzes previous sales data to predict future medicine demand. This can help pharmacies maintain proper stock and avoid unnecessary shortages or overstocking.

## Features

- **Dashboard:** View important information about medicines, stock, and sales in one place.
- **Medicine Management:** Add, update, search, and manage medicine details.
- **Inventory Management:** Track available stock and medicine batches.
- **Expiry Alerts:** Identify medicines that are expired or approaching their expiry date.
- **Sales Management:** Record medicine sales and maintain transaction history.
- **Low Stock Alerts:** Identify medicines that need to be restocked.
- **Demand Forecasting:** Use Machine Learning to estimate future medicine requirements.
- **Login System:** Provide secure access to the pharmacy management system.

## Technologies Used

| Area | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Database ODM | Mongoose |
| Machine Learning | Python, Scikit-learn |
| Data Processing | Pandas, NumPy |
| Algorithm | Random Forest Regression |
| Version Control | Git & GitHub |

## Project Structure

```text
MediTrack-AI/
│
├── backend/
│   ├── ml/
│   │   ├── forecast.py
│   │   └── requirements.txt
│   │
│   ├── src/
│   │   ├── config/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   │
│   ├── .env.example
│   ├── package.json
│   ├── seed.js
│   └── server.js
│
├── frontend/
│   ├── css/
│   ├── js/
│   └── index.html
│
├── MediTrack_AI_12310424_Report.pdf
├── MediTrack_AI_Presentation.pptx
├── package-lock.json
└── README.md
```

## Getting Started

Follow these steps to run the project on your computer.

### 1. Clone the Repository

```bash
git clone https://github.com/tanmaykumar3506/MediTrack-AI.git
```

```bash
cd MediTrack-AI
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the backend folder by copying `.env.example`.

For Windows PowerShell:

```powershell
Copy-Item .env.example .env
```

Add your MongoDB connection details and other required configuration values to the `.env` file.

### 4. Install Python Dependencies

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the required packages:

```bash
pip install -r ml/requirements.txt
```

### 5. Start MongoDB

Make sure MongoDB is running and your connection string is correctly configured.

### 6. Add Sample Data

Run the following command from the backend folder:

```bash
node seed.js
```

### 7. Start the Application

```bash
npm start
```

Open your browser and visit:

```text
http://localhost:4000
```

## Machine Learning

One of the main parts of this project is medicine demand forecasting.

I used a Random Forest Regression model to analyze historical medicine sales and estimate future demand.

The basic process is:

1. Collect historical sales data.
2. Process and prepare the data using Pandas and NumPy.
3. Train the Random Forest model.
4. Analyze the prediction results.
5. Estimate medicine demand for upcoming days.

The forecasting feature is intended to help pharmacies make better inventory decisions.

## Project Files

Along with the source code, this repository includes:

- `MediTrack_AI_12310424_Report.pdf` – Project documentation.
- `MediTrack_AI_Presentation.pptx` – Project presentation.

## Future Improvements

Some features I would like to add in the future:

- Better sales and inventory analytics.
- Automated stock notifications.
- Supplier management.
- Improved demand prediction.
- Cloud deployment.
- Support for multiple pharmacy stores.

## Developer

**Tanmay Kumar**

B.Tech Computer Science and Engineering  
Lovely Professional University

GitHub: [tanmaykumar3506](https://github.com/tanmaykumar3506)

Project: [MediTrack-AI](https://github.com/tanmaykumar3506/MediTrack-AI)

---

This project was developed as part of my academic work to apply my knowledge of web development, databases, and Machine Learning to a real-world problem.

If you find the project useful or interesting, feel free to explore the repository and share your feedback!

**Thank you for visiting!**
