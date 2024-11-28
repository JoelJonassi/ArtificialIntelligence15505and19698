## 💻 About the Project

This project was developed as part of an **Artificial Intelligence** course and focuses on optimizing class schedules for a university. The main goal is to minimize campus travel and reduce classroom usage by creating an intelligent agent that can automate and improve scheduling decisions.

Key challenges included adhering to constraints like class duration, classroom availability, and scheduling preferences, all while ensuring an optimal schedule that balances efficiency with the university’s needs.

### Problem Constraints:
- Classes are 2 hours long, taking place on weekdays.
- Each class consists of 10 lessons per week, with 1 or 2 online sessions.
- No more than 3 lessons per day are allowed for a class.
- Online sessions cannot be scheduled immediately before or after in-person lessons.
- Only 2 lessons are allowed in the morning, and 2 in the afternoon.
- Each class needs 2 to 4 lessons in specific classrooms.
- Classrooms cannot be double-booked.
- All lessons must start by 9 AM and end by 6 PM.

### Solution:
Using constraint satisfaction problems (CSP), we developed an intelligent agent that efficiently schedules classes, optimizing for fewer campus visits and minimal classroom usage.

---

## ⚙️ Functionalities

The intelligent agent developed in this project achieves the following functionalities:
- **Class Schedule Optimization**: Automatically schedules classes, ensuring adherence to the constraints.
- **Resource Allocation**: Efficiently assigns classrooms, ensuring no double bookings.
- **Campus Travel Minimization**: Reduces the number of days students and professors must travel to campus.
- **Air Conditioning Minimization**: Reduces the number of classrooms used, contributing to energy savings by minimizing air conditioning usage.

---

## 🚀 How to Run the Project

### Prerequisites:
- Python (version 3.6 or above)
- Jupyter Notebook or any Python IDE
- Required libraries: `numpy`, `pandas`, `sklearn`, etc.

### Steps to Run:
1. Clone the repository:
    ```bash
    git clone https://github.com/JoelJonassi/Artificial_Intelligence_15505_19698.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Artificial_Intelligence_15505_19698
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

---
