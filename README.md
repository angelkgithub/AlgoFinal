# 🎓 Curriculum Scheduler (AlgoV3)

This app automatically generates class schedules using a scheduling algorithm.  
It’s built with **Python** and **Streamlit** to make scheduling simple and efficient.  

---

## 🧩 Requirements

Before running the app, make sure you have the following installed:

1. **Python** (version 3.8 or higher)  
   - Check if Python is installed by running:  
     ```bash
     python --version
     ```

2. **Required Python libraries**  
   Open your terminal or command prompt and run:
   ```bash
   pip install streamlit pandas numpy
   ```

---

## 🚀 How to Run the App

### Option 1: Using the Launch File (Easiest Way)

1. **Download the Project**
   - Click on the download button and choose “Download as ZIP”.

2. **Extract the ZIP File**
   - Right-click the ZIP file → select “Extract All”.

3. **Locate the App Folder**
   - Go to:
     ```
     \AlgoV3\AlgoV3\CurriculumScheduler_V3
     ```

4. **Run the App**
   - Double-click `launch_app.bat` to start the app automatically.  
   - Your browser should open the Streamlit web interface.

---

### Option 2: Run Manually Through Terminal

If the `launch_app.bat` file doesn’t work, you can start the app manually:

1. Open the folder:
   ```
   \AlgoV3\AlgoV3\CurriculumScheduler_V3
   ```

2. Open the terminal inside that folder  
   (you can right-click → “Open in Terminal”)

3. Run one of the following commands:
   ```bash
   python -m streamlit run app.py
   ```
   or simply:
   ```bash
   streamlit run app.py
   ```

4. Wait a few seconds — a local URL will appear (something like `http://localhost:8501`)  
   Click it or copy-paste it into your browser.

---

## 💡 Tips

- If the app doesn’t launch, double-check that Python and Streamlit are installed correctly.  
- You can stop the app anytime by pressing `Ctrl + C` in the terminal.  
- For a smoother experience, make sure no other apps are using port **8501**.

---

## 🧠 About the Project

This project uses a scheduling algorithm to automatically assign subjects, rooms, and faculty while minimizing conflicts.  
It’s part of the **AlgoV3** system, designed for efficient academic scheduling and management.
