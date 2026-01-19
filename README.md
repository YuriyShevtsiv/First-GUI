Tkinter GUI Application
📌 Description

This project is a simple Tkinter-based GUI application written in Python.
It demonstrates how to create a window with labels, input fields, buttons, and how to update UI elements dynamically based on user input.

The interface allows the user to:

Enter text into an input field

Click a button

See the label text update dynamically and change its color

The application interface is written in Ukrainian.

🛠 Requirements

Python 3.x

Tkinter (included by default with most Python installations)

To check your Python version:

python --version

▶️ How to Run the Application

Save the code into a file, for example:

main.py


Run the file using Python:

python main.py


The GUI window will open automatically.

🖥 Application Features

Main Window

Title: "Мій перший GUI-додаток Tkinter"

Size: 450x300

Custom background color

Label

Large green text by default

Updates text dynamically when the button is clicked

Changes text color to yellow after update

Text Entry

Allows the user to input custom text

Input is displayed inside the label after clicking the button

Button

Triggers the label update

Styled with custom colors

⚙️ How It Works

The user enters text into the input field.

When the "Оновити лейбл" button is clicked:

The function update_label_content() is called.

If text is entered, the label displays:

Введено текст: 'your text'


If no text is entered, the label shows a default message.

The label text color changes to yellow.

📂 Project Structure
project-folder/
│
├── main.py      # Main application file
└── README.md    # Project documentation

🧠 Learning Purpose

This project is ideal for beginners who want to learn:

Basic Tkinter window setup

Using Frame, Label, Entry, and Button

Handling button events

Updating widgets dynamically with .config()

📄 License

This project is free to use for educational purposes.