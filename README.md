# 🎓 Student Knowledgebase Application
[Fall 2025] CS 151 - Team 33 - Term Project

This is a small desktop application for faculty members to manage student profiles. 
You can add/edit students, record timestamped comments, search, and see reports for whitelisted/blacklisted students.

## 🧾 Features
Create, edit, delete student profiles
Add dated comments (auto timestamped)
Search by name, role, academic status, languages, databases
Reports page with Whitelisted / Blacklisted filters
Double-click a student in Reports to open a detail window

---

## ⚙️ Requirements
- **JDK 17 or newer**
- **JavaFX SDK 17+**
- **SQLite JDBC Driver**
- Compatible IDE: IntelliJ IDEA / Eclipse

---

## 📂 Project Structure
```
src/
 └── cs151/
      ├── application/      → Main.java
      ├── controller/       → All JavaFX controllers
      ├── db/               → Database setup and helper functions
      ├── model/            → Data models
      └── util/             → Utility classes (FxUtil)
resources/
 └── All .fxml files
```

---

## 🧠 Usage Flow
1. **Home Page** → Navigate to all sections  
2. **Define Programming Languages** → Add/remove languages  
3. **Define Student Profile** → Create a new profile, add comments  
4. **Search Student Profiles** → Find students by role, skill, etc.  
5. **Reports Page** → Filter whitelisted/blacklisted students  
6. **Student Details Popup** → Double-click report entry to view profile + comments

---

## 👩‍💻 Team members
Sukirth Chanda  
Evie Ho  
Tanishq Tyagi  
Girum Yaye  

GitHub Repository Example
