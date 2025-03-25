# nutri-track-app 🍽️  
A personal dietary tracking and analysis system built with Python, Flask, and MySQL. It helps users record daily meals, analyze nutritional intake, and generate personalized health reports.

---

## 📌 Project Overview  
NutriTrack enables users to input their dietary information, automatically analyzes nutritional content (calories, fat, protein, carbs), and visualizes data through charts and downloadable reports. Designed for usability and extensibility, it combines back-end logic, data visualization, and report generation in a modular way.

---

## ✨ Features
- 🥗 **Meal Logging Interface**: Enter meals and portions through structured web forms
- 📊 **Nutritional Analysis**: Calculate daily intake of calories, protein, fat, and carbohydrates
- 📈 **Data Visualization**: Generate line charts, bar charts, pie charts using `Matplotlib` and `Seaborn`
- 📄 **Report Export**: Download analysis as PDF, Excel, or JPG via `ReportLab` and `Openpyxl`
- 🧠 **Recipe Recommendation**: Match recipes from MySQL database based on current nutrient gaps
- 🧱 **Modular Design**: Functions split across Flask routes, Pandas processing, and rendering logic

---

## 💡 Tech Stack
- **Backend**: Python
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Export Tools**: Openpyxl, ReportLab  

---

## 🛠️ Getting Started

### ✅ Prerequisites
- Python 3.8+
- MySQL server (or local test DB)
- `pip install -r requirements.txt`

### ▶️ Run Locally
```bash
python app.py
```
Then open http://localhost:5000 in your browser.

## Screenshot
<img width="854" alt="image" src="https://github.com/user-attachments/assets/c28fd2ac-a95a-4cc6-ad42-43d79231d436" />
<img width="856" alt="image" src="https://github.com/user-attachments/assets/35b791ea-7967-4076-bf56-5d86ec6bdb73" />
<img width="856" alt="image" src="https://github.com/user-attachments/assets/a5884894-cc4b-4e64-99e7-c6162195a6a6" />
<img width="856" alt="image" src="https://github.com/user-attachments/assets/cccfb6e1-c4b4-4d38-acb3-d29933ca0d88" />
<img width="855" alt="image" src="https://github.com/user-attachments/assets/1eb4ff49-39f5-4230-8c93-d5f1ad37d8bf" />
<img width="856" alt="image" src="https://github.com/user-attachments/assets/df5ff96a-d231-4c0a-b327-ceb2354c9349" />

## License
This project is licensed under the MIT License.
Images and icons used are royalty-free or generated internally.

## Author
Yan Qin
Qianyi Wu

