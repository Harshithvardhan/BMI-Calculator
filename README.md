# 🧮 BMI Calculator

A simple **BMI (Body Mass Index) Calculator** built using **Python and Tkinter**. The application provides a graphical user interface where users can enter their height and weight, select the appropriate units, and calculate their BMI.

## 📌 Overview

This project was developed as a beginner-friendly Python application to demonstrate:

* GUI development using Tkinter
* User input handling
* Mathematical calculations
* Conditional statements
* Input validation
* Basic event-driven programming

The application allows users to select **feet or centimeters** for height and **pounds or kilograms** for weight.

## ✨ Features

* 🖥️ Simple graphical user interface
* 📏 Height input in **feet or centimeters**
* ⚖️ Weight input in **pounds or kilograms**
* 🧮 Automatic BMI calculation
* 📊 BMI category display
* ❌ Input validation for invalid values
* ⚡ Simple and lightweight Python application

## 🛠️ Technologies Used

* **Python**
* **Tkinter**

Tkinter is used to create the application's GUI, including input fields, dropdown menus, buttons, and result display.

## 📂 Project Structure

```text
BMI-Calculator/
│
├── bmi.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/OIBSIP-BMI-Calculator.git
```

### 2. Navigate to the Project

```bash
cd OIBSIP-BMI-Calculator
```

### 3. Run the Application

```bash
python bmi.py
```

> Tkinter is included with most standard Python installations, so no additional external libraries are required.

## 🖥️ How to Use

1. Launch the application.
2. Enter your height.
3. Select the height unit:

   * Feet
   * Centimeters
4. Enter your weight.
5. Select the weight unit:

   * Pounds
   * Kilograms
6. Click **Calculate BMI**.
7. The calculated BMI category will be displayed.

## 🧮 BMI Calculation

The application uses different formulas depending on the selected height unit.

### Height in Feet / Weight in Pounds

```text
BMI = 703 × weight / height²
```

### Height in Centimeters / Weight in Kilograms

```text
BMI = weight / height²
```

The program converts the entered height into the required unit before performing the calculation.

## 📊 BMI Categories

The application displays the following categories:

| BMI Range   | Category    |
| ----------- | ----------- |
| ≤ 18.4      | Underweight |
| 18.5 – 24.9 | Normal      |
| 25.0 – 39.9 | Overweight  |
| 40.0+       | Obesity     |

The category is displayed directly in the application after calculation.

## 🔄 Application Workflow

```text
User Opens Application
        ↓
Enter Height
        ↓
Select Height Unit
        ↓
Enter Weight
        ↓
Select Weight Unit
        ↓
Click "Calculate BMI"
        ↓
Validate Input
        ↓
Calculate BMI
        ↓
Determine BMI Category
        ↓
Display Result
```

## 🛡️ Input Validation

The application checks whether the entered values are valid numeric values and ensures that height and weight are greater than zero. If invalid input is provided, an appropriate message is displayed.

## 🎯 Learning Outcomes

Through this project, I learned:

* Python GUI development
* Tkinter widgets and layouts
* Handling user input
* Event-driven programming
* Mathematical calculations
* Conditional logic
* Input validation
* Creating simple desktop applications

## 🔮 Future Improvements

Possible improvements include:

* 📱 Add a more modern and responsive interface
* 📊 Display the calculated BMI value along with the category
* 📈 Add a BMI range chart
* 💾 Store previous calculations
* 🌙 Add dark mode
* 👤 Add age and gender-based information
* 📋 Add health and fitness recommendations
* 🖼️ Improve the overall UI/UX

## 👨‍💻 Author

**Harshith Vardhan**

* GitHub: https://github.com/Harshithvardhan
* LinkedIn: Add your LinkedIn profile here

## 📜 License

This project was developed for **educational and internship purposes** as part of the **OIBSIP Internship Program**.
