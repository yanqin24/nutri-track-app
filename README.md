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
- **Backend**: Python, Flask  
- **Database**: MySQL  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Export Tools**: Openpyxl, ReportLab  
- **Deployment Ready**: Can be hosted with Flask or deployed to AWS/GCP

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

## Project Structure
```
├── app.py                      # Main Flask app
├── templates/                  # HTML templates
├── static/                     # CSS and images
├── data/recipes.csv            # Sample recipe dataset
├── reports/                    # Exported PDF, XLS, JPG
├── utils/
│   ├── analysis.py             # Nutrition calculations
│   ├── report_generator.py     # PDF/Excel generation
├── requirements.txt
```

## License
This project is licensed under the MIT License.
Images and icons used are royalty-free or generated internally.

## Author
Yan Qin
Qianyi Wu

