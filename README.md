# School-Catalogue
# 🏫 School Catalogue Project

This project is part of Codecademy's **Learn Intermediate Python 3: Object-Oriented Programming** course. It demonstrates the use of Python OOP principles by modeling a school system with classes like `School`, `HighSchool`, `MiddleSchool`, and a managing class `SchoolCatalog`.

---

## 🔧 Features

- ✅ Object-Oriented design using Python classes
- 🧬 Inheritance from a base `School` class
- 🎓 Support for student enrollment and sports teams
- 📚 `SchoolCatalog` class to manage a list of schools
- ✍️ Getter and Setter usage for encapsulation
- ✅ Includes a full test suite with `unittest`

---

## 🧠 Concepts Covered

- Classes and Objects  
- Inheritance and Method Overriding  
- Encapsulation with Getters and Setters  
- Composition and Aggregation  
- Object Instantiation and Method Usage  
- Data Structures: Lists  

---

## 🏗️ Project Structure

```text
school_catalogue/
│
├── school_catalogue.py      # Main classes and logic
├── test_school_catalogue.py # Unit tests using unittest
└── README.md                # Project documentation


🚀 How to Run
Clone this repo

bash
Copy
Edit
git clone https://github.com/yourusername/school-catalogue.git
cd school-catalogue
Run the main script

bash
Copy
Edit
python school_catalogue.py
Run unit tests

bash
Copy
Edit
python test_school_catalogue.py
📄 Example Output
yaml
Copy
Edit
School Catalog:
High School: Roosevelt High, Ranking: 9
Middle School: Lincoln Middle, Honors: True

Students at Roosevelt High:
['Alice']

Sports Teams at Roosevelt High:
['Basketball']
🧪 Testing
Framework: unittest

Run test cases for all main class methods

Checks for student/school insertion, class output, and integrity

💡 Future Improvements
Add Student class with more detailed data (grade, age, etc.)

Add CSV/JSON import/export features

Build a CLI or Web UI for better interaction

Extend catalog with ElementarySchool or College

