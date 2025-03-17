# **PIM (PostImpact)** 🎯

**PIM** is a modern and scalable Python-based application designed to efficiently manage and streamline product information. Follow the steps below to set up and run the project in your local or production environment.

---

## **🚀 Getting Started**

Before you begin, ensure you have the following installed:

- **Python 3.8+**
- **pip** (Python Package Manager)
- **PostgreSQL**

---

### **📥 Clone the Repository**

To get started, clone the repository and switch to the main branch:

```bash
git clone https://github.com/kashiftariq1997/pim.git
cd pim
git checkout main
```

---

### **🌱 Create a Virtual Environment**

Set up a virtual environment to isolate project dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### **📦 Install Dependencies**

Install all required Python packages:

```bash
pip install -r requirements.txt
```

---

### **🔐 Set Up Environment Variables**

Create a `.env` file in the project root.  
For environment variable details, please contact the developer.

---

### **🗄️ Database Migrations**

1. **Generate Migrations:**

   ```bash
   python manage.py makemigrations
   ```

2. **Apply Migrations:**

   ```bash
   python manage.py migrate
   ```

---

### **🌐 Run the Development Server**

Start the Django development server:

```bash
python manage.py runserver
```

Then, open your browser and navigate to:

```
http://127.0.0.1:8000
```

---

