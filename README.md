# 🦚 Janmashtami Greeting — Jai Shree Krishna

A simple Python program that creates a colorful **Janmashtami greeting** using ASCII art and terminal colors.

The project displays **"JANMASHTAMI"** in large ASCII-style text followed by a festive **"Jai Shree Krishna"** message. 🪈🦚

## ✨ Features

* 🎨 Colorful terminal output
* 🦚 Large ASCII-art **JANMASHTAMI** heading
* 🪈 Displays **Jai Shree Krishna**
* 🐍 Built with Python
* 💻 Runs directly in the terminal

## 🛠️ Technologies Used

* **Python**
* **PyFiglet** — Generates ASCII text art
* **Termcolor** — Adds colors to terminal output

## 📦 Installation

Install the required packages with:

```bash
pip install pyfiglet termcolor
```

## 🚀 Usage

Run the Python script:

```bash
python janmashtami.py
```

The terminal will display a colorful greeting similar to:

```text
     JANMASHTAMI

Jai Shree Krishna
```

## 💻 Code

```python
from pyfiglet import figlet_format
from termcolor import colored

print(colored(figlet_format("JANMASHTAMI",
                            font="silent"), "yellow"))

print(colored("Jai Shree Krishna", "cyan"))
```

## 📚 What This Project Demonstrates

This beginner-friendly project demonstrates:

* Importing functions from Python packages
* Generating ASCII art with `pyfiglet`
* Formatting terminal output
* Applying colors with `termcolor`
* Creating simple festive command-line programs

## 🪷 Festival Message

**Jai Shree Krishna! 🦚🪈**

May Lord Krishna's blessings bring happiness, peace, and prosperity.

## 📄 License

This project is open-source and available for learning and personal use.
