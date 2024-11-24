# **BMI Calculator**

This project is a user-friendly **Body Mass Index (BMI) Calculator** built with **Streamlit**, a Python-based web application framework. The calculator allows users to input their weight and height in different units and calculates their BMI, providing instant feedback on their health status.

---

## **Features**
- **Weight Input**: Enter your weight in kilograms.
- **Height Input Options**: 
  - Centimeters
  - Meters
  - Feet
- **Real-Time BMI Calculation**: The BMI is calculated as soon as the required inputs are provided, using the formula:
  \[
  BMI = \frac{\text{Weight (kg)}}{\text{Height (m)}^2}
  \]
- **Health Feedback**: Based on the calculated BMI, the app provides feedback in the following categories:
  - Extremely Underweight
  - Underweight
  - Healthy
  - Overweight
  - Extremely Overweight
- **Responsive Design**: Works seamlessly on desktops and mobile browsers.

---

### **How to Run the App**

1. **Clone the Repository**  
   Open a terminal and clone the repository to your local machine:  
   ```bash
   git clone https://github.com/kushals256/BMI-Calculator.git
   ```  

2. **Navigate to the Project Directory**  
   Change to the project directory:  
   ```bash
   cd BMI-Calculator
   ```

3. **Install Streamlit**  
   If you don't have Streamlit installed, run the following command:  
   ```bash
   pip install streamlit
   ```

4. **Run the Application**  
   Start the Streamlit app:  
   ```bash
   streamlit run BmiCalc.py
   ```  
   A local URL (e.g., `http://localhost:8501`) will appear. Open it in your browser to use the app.

---

## **Health Status Classification**
The app categorizes your BMI as follows:
| **BMI Range**       | **Health Status**         |
|----------------------|---------------------------|
| Less than 16         | Extremely Underweight     |
| 16 - 18.5            | Underweight              |
| 18.5 - 25            | Healthy                  |
| 25 - 30             | Overweight               |
| Greater than 30      | Extremely Overweight     |

---

## **Technologies Used**
- **Streamlit**: For building the interactive web application.
- **Python**: Core programming language for BMI calculations and logic.
  
---
