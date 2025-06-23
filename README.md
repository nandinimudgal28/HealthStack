# 🏥 HealthStack – Integrated Healthcare Management System

**HealthStack** is a full-stack web application designed to streamline and digitize healthcare services by connecting hospitals, doctors, and patients in a unified platform. It enables real-time health record tracking, appointment scheduling, e-prescriptions, and medical test management, complete with real-time communication support.

---

## 🚀 Features

- 👩‍⚕️ Multi-role access for Hospitals, Doctors, and Patients
- 📅 Online appointment booking & schedule management
- 🧾 E-prescription generation and access to medical history
- 📂 Centralized patient health record management
- 💬 Real-time doctor-patient chat (WebSockets)
- 📧 Email notifications for appointments and updates (via MailTrap)
- 📊 Admin dashboard for hospital staff and doctors

---

## 🛠 Tech Stack

| Layer       | Technology                                                                 |
|-------------|-----------------------------------------------------------------------------|
| **Frontend**  | HTML, CSS, JavaScript, Bootstrap, AJAX                                     |
| **Backend**   | Python, Django, Django REST Framework                                      |
| **Database**  | SQLite                                                                     |
| **Real-time** | Django Channels (WebSockets)                                               |
| **Dev Tools** | Visual Studio Code, Google Colab                                           |
| **Other**     | MailTrap for testing email notifications                                   |

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/HealthStack.git
cd HealthStack

# 2. Create and activate virtual environment
python -m venv venv
source venv/Scripts/activate     # For Windows
# OR
source venv/bin/activate         # For macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py makemigrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
