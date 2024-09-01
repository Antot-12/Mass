# 🏋️ Body Mass Index (BMI) Calculator

This repository contains a simple Python script that calculates your Body Mass Index (BMI), provides information about BMI categories, and gives some basic details about the developer.

## 📋 Features

- **BMI Calculation**: Input your weight and height, and the script will calculate your BMI and give you a brief interpretation of your result.
- **BMI Information**: Provides a breakdown of what different BMI ranges indicate about your body weight.
- **Developer Information**: Shows basic details about the version and the creator of the script.

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### 🛠️ Running the Script

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Antot-12/Mass.git
    cd Mass
    ```

2. **Run the script**:
    ```bash
    python bmi_calculator.py
    ```

3. **Follow the prompts**:
    - The script will display a menu with the following options:
      - `1`: Calculate your BMI.
      - `2`: Get information about BMI categories.
      - `3`: Get information about the developer.
      - `4`: Exit the program.

### 📊 Understanding BMI Results

After calculating your BMI, you will receive a message explaining your BMI category:
- **BMI ≤ 16**: Critical underweight, advice to eat more.
- **16 < BMI ≤ 18**: Underweight, suggestion to gain some weight.
- **18 < BMI ≤ 25**: Normal weight, you are doing great!
- **25 < BMI ≤ 30**: Overweight, advice to exercise more.
- **BMI > 30**: Obesity, it's recommended to seek professional advice.

### 📄 Example Usage

```bash
Виберіть ваш варіант: 
1 - Порахувати ІМТ
2 - Інформація про ІМТ
3 - Інформація про розробника
4 - Вийти
Ваш вибір: 1
Ведіть вашу вагу, кг: 70
Ведіть ваш зріст, см: 170

Ваш ІМТ:  24.22
Твоя маса тіла є нормальною, відпочивай)
