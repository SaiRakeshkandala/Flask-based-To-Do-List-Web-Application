# ✅ Flask To-Do List Web Application  

A simple and user-friendly To-Do List web application built using Flask and SQLite. This app helps users manage their daily tasks efficiently with features to add, view, complete, and delete tasks.  

---

## 🎯 Features  
- 📝 **Add Tasks**: Add new tasks to the list.  
- 📋 **View Tasks**: View all tasks along with their completion status.  
- ✅ **Mark as Completed**: Mark tasks as completed.  
- 🗑️ **Delete Tasks**: Remove tasks from the list.  

---

## 🛠️ Technologies Used  
- **Flask**: Python web framework for backend development.  
- **SQLite**: Lightweight database for storing tasks.  
- **HTML/CSS**: For frontend design and layout.  

---

## 🚀 How to Run Locally  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/flask-todo.git
   cd flask-todo
   ```

2. Create and activate a virtual environment:  
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:  
   ```bash
   python app.py
   ```
   The application will run on `http://127.0.0.1:5000/`.

---

## 🛠️ Deployment  

### Deploy on Heroku  

1. Log in to Heroku:  
   ```bash
   heroku login
   ```

2. Create a new Heroku app:  
   ```bash
   heroku create your-app-name
   ```

3. Push your code to Heroku:  
   ```bash
   git add .
   git commit -m "Deploy Flask To-Do List"
   git push heroku main
   ```

4. Open your deployed app:  
   ```bash
   heroku open
   ```

---

## 📂 Project Structure  
```
flask_todo/
├── app.py                # Main application file
├── templates/            # HTML templates
│   ├── base.html         # Base layout
│   ├── index.html        # Homepage template
├── static/               # Static files (CSS)
│   ├── style.css         # Stylesheet for the app
├── requirements.txt      # Python dependencies
├── Procfile              # Heroku deployment file
├── runtime.txt           # Python version for Heroku
├── tasks.db              # SQLite database
```

---

## 🛡️ License  
This project is licensed under the **MIT License**.  

---

## 🤝 Contributions  
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.  

---

## 📬 Contact  
For any queries or suggestions, reach out to:  
📧 **your-email@example.com**

---

Enjoy managing your tasks effectively! 🚀  
