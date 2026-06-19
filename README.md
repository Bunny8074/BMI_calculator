# BMI Calculator

## Description

The **BMI (Body Mass Index) Calculator** is a simple Python application that calculates a person's Body Mass Index based on their weight and height. BMI is a widely used health indicator that helps determine whether a person is underweight, has a normal weight, is overweight, or is obese.

The program takes the user's weight (in kilograms) and height (in meters) as input, calculates the BMI using the standard formula, and displays the BMI value along with the corresponding health category.

---

## Features

- Calculates Body Mass Index (BMI)
- Accepts weight in kilograms (kg)
- Accepts height in meters (m)
- Displays BMI rounded to two decimal places
- Classifies BMI into health categories:
  - Underweight
  - Normal Weight
  - Overweight
  - Obese
- Simple and easy-to-use command-line interface

---

## Requirements

- Python 3.x

No external libraries are required.

---

## Project Structure

```
BMI-Calculator/
│── bmi_calculator.py
└── README.md
```

---

## How to Run

1. Save the program as `bmi_calculator.py`.
2. Open a terminal or command prompt.
3. Navigate to the project directory.
4. Run the following command:

```bash
python bmi_calculator.py
```

---

## Example

### Input

```
Enter your weight in kilograms (kg): 70
Enter your height in meters (m): 1.75
```

### Output

```
Your BMI is: 22.86
Category: Normal weight
```

---

## BMI Formula

```
BMI = Weight (kg) / (Height (m) × Height (m))
```

---

## BMI Classification

| BMI Range | Category |
|------------|----------------|
| Below 18.5 | Underweight |
| 18.5 – 24.9 | Normal Weight |
| 25.0 – 29.9 | Overweight |
| 30.0 and above | Obese |

---

## Advantages

- Simple and quick BMI calculation
- Helps users understand their weight category
- Useful for learning Python basics such as input handling, arithmetic operations, and conditional statements

---

## Future Enhancements

- Accept height in centimeters or feet/inches
- Add input validation for invalid values
- Create a graphical user interface (GUI)
- Store BMI history for multiple users
- Provide basic health recommendations based on BMI

---

## License

This project is open source and intended for educational and personal learning purposes.
