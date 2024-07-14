# BMI Measurement Website

## Overview
This website allows users to calculate their Body Mass Index (BMI) and provides tailored feedback based on their BMI category. The feedback includes:
- For underweight individuals: how much weight they need to gain to reach a healthy BMI.
- For healthy individuals: the range of weight they can gain or lose to stay within the healthy BMI range.
- For overweight or obese individuals: how much weight they need to lose to reach a healthy BMI.

## Features
- **BMI Calculation**: Users can enter their weight and height to calculate their BMI.
- **Category-based Feedback**: Provides specific recommendations based on the user's BMI category.
  - **Underweight**: Shows the weight needed to gain.
  - **Healthy Weight**: Shows the weight range for maintaining a healthy BMI.
  - **Overweight/Obese**: Shows the weight needed to lose.
- **Responsive Design**: The website is accessible on various devices.

## BMI Categories
The BMI categories are as follows:
- **Underweight**: BMI < 18.5
- **Healthy Weight**: BMI 18.5 - 24.9
- **Overweight**: BMI 25 - 29.9
- **Obese**: BMI 30 - 34.9
- **Extremely Obese**: BMI ≥ 35

## Usage

1. **Input Data**: 
   - Enter your weight in kilograms.
   - Enter your height in centimeters.

2. **Calculate BMI**:
   - Click the "Calculate" button to compute your BMI.

3. **View Results**:
   - The website will display your BMI and the corresponding category.
   - Based on the category, it will provide recommendations:
     - **Underweight**: Shows the weight needed to gain to reach a BMI of 18.5.
     - **Healthy Weight**: Shows the range of weights for a BMI between 18.5 and 24.9.
     - **Overweight/Obese**: Shows the weight needed to lose to reach a BMI of 24.9.

## Example
- **User Input**:
  - Weight: 60 kg
  - Height: 170 cm

- **Output**:
  - BMI: 20.8 (Healthy Weight)
  - Recommendation: Healthy. To stay within this range, your weight should be between 54 kg and 72 kg.

## Development
### Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Hosting**: GitHub Pages

### Calculation Formula
The BMI is calculated using the following formula:
BMI = weight in kilograms / (height in meters)^2

### Handling Edge Cases
- Ensuring valid input (positive numbers for age, weight and height).
- Providing error messages for invalid inputs.

## Future Enhancements
- Adding support for other units (e.g., pounds and inches).
- Providing dietary and exercise recommendations.
- Integrating with health tracking APIs.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue on the project's repository.

## Contact
For any inquiries, please contact [kumarbhattarai666@gmail.com].

