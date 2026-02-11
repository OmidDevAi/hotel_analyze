# 🏨 Hotel Data Manager  

A simple **Tkinter-based GUI application** to store hotel-related data (Name, Cost, Weight) into a local SQLite database. Perfect for small-scale data entry with instant feedback! 💾✨  

---

## 🌟 Features  
- 📝 Easy form input for **Name**, **Cost**, and **Weight**  
- 🔒 Input validation (non-empty fields + numeric checks)  
- 💾 Auto-created SQLite database (`data.db`) with `hotel` table  
- ✅ Success/error messages via pop-up alerts  
- 🧹 Automatic form clearing after successful submission  

---

## 🛠️ Requirements  
- Python 3.x  
- Built-in libraries only:  
  - `sqlite3`  
  - `pandas` *(optional – included but not used yet)*  
  - `tkinter`  

> 💡 No external dependencies! Just run and go.

---

## ▶️ How to Run  
1. Clone or download this project  
2. Open your terminal in the project folder  
3. Run:  
```bash
python app.py
```
*(Assuming your script is named `app.py`)*  

4. Fill the form and click **"Save to Database"** 💚  

---

## 🗃️ Database Schema  
Table: `hotel`  
| Column   | Type    | Description        |  
|----------|---------|--------------------|  
| `FIND`   | INTEGER | Auto-increment ID  |  
| `FNAME`  | TEXT    | Hotel name         |  
| `COST`   | INTEGER | Price (required)   |  
| `WEIGHT` | INTEGER | Optional weight (defaults to 0) |  

---

## 📸 Preview  
![App Screenshot](demo.png) *(Optional: add screenshot later)*  

---

## 🚀 Future Ideas  
- 📊 Add data viewing/export (CSV/Excel)  
- 🔍 Search & edit existing entries  
- 🎨 Modern UI with themed widgets  

---

> Made with ❤️ and ☕ | Happy coding! 💻🐍