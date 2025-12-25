# Student Management System (MATLAB App Designer)

A professional, GUI-based desktop application developed in **MATLAB** using **App Designer**. This system provides a streamlined interface for managing student records, performing real-time data analysis, and visualizing academic performance metrics.

---

## 🚀 Key Features

### 1. **Data Management (CRUD)**
* **Add Student:** Register new students with details (ID, Name, Department, GPA, Gender, and Email).
* **Update Info:** Modify existing student records directly through the UI table selection.
* **Delete Student:** Remove student entries with a built-in confirmation workflow.
* **Persistent Storage:** Data is automatically saved to a `Student.csv` file, ensuring your data is preserved between sessions.

### 2. **Interactive Search & Selection**
* **Real-time Search:** Instantly find students by name using the search bar.
* **Smart Selection:** Clicking a row in the table automatically populates the input fields for quick editing or viewing.

### 3. **Dynamic Dashboard & Analytics**
The app features an automated analytics suite that updates as data changes:
* **Departmental Analysis:** Bar chart showing the average GPA per department.
* **Gender Performance:** Comparative bar chart for average GPA by gender.
* **Demographics:** Pie chart representing the gender distribution of the student body.

<img width="1630" height="818" alt="Ekran görüntüsü 2025-12-24 090306" src="https://github.com/user-attachments/assets/88f96358-9b6d-4d6a-b40d-594e85b887e4" />


---

## 🛠️ Technical Stack

* **Language:** MATLAB
* **Framework:** App Designer (`matlab.apps.AppBase`)
* **Data Format:** CSV (Comma-Separated Values)
* **Key Functions:** `groupsummary`, `readtable`, `writetable`, `uialert`, `uitable`.

---

## 📂 File Structure

* `StudentManagement.m`: The primary class file containing the UI layout and application logic.
* `Student.csv`: The local database file (automatically created if it doesn't exist).
