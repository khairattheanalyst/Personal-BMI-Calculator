# BMI Calculator

## Description
This project computes users’ **Body Mass Index (BMI)** values and assigns them to corresponding health categories.  
It also provides short, friendly health advice based on the user’s BMI classification.

The **Body Mass Index (BMI)** is calculated using the following formula:

$$
\mathrm{BMI} = \frac{\text{Weight (lb)} \times 703}{(\text{Height (in)})^2}
$$

---

## BMI Categories (World Health Organization Standard)

| Category | BMI Range |
|-----------|------------|
| Underweight | < 18.5 |
| Normal weight | 18.5 – 24.9 |
| Overweight | 25.0 – 29.9 |
| Obesity (Class I) | 30.0 – 34.9 |
| Obesity (Class II) | 35.0 – 39.9 |
| Obesity (Class III) | ≥ 40.0 |

---

## Features
- Greets the user by name  
- Requests user weight and height  
- Calculates BMI using the imperial formula  
- Categorizes the user’s BMI result  
- Provides short, friendly health advice  
- Outputs results clearly in the terminal or Jupyter Notebook  

---

## Sample Output

> Example output when a user runs the BMI Calculator in the terminal:

```text
============================================================
                 BMI Calculator (Imperial Units)
============================================================
Hello Khairat, Welcome to your BMI calculator!
I would need the following details from you.

Enter your weight (lb): 160  
Enter your height (in): 65
------------------------------------------------------------
Name: Khairat
BMI: 26.63
Category: Overweight
------------------------------------------------------------
Feedback:
You’re a bit on the heavier side — maybe skip that extra midnight snack.
A little more movement and mindful eating can go a long way.
------------------------------------------------------------
Thank you for using the BMI Calculator!
============================================================
```

Built with ❤️ using Python.
