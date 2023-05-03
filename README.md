## **Workout Tracker**

# Exercise Tracker with Nutritionix and Sheety APIs

This Python script allows users to input a list of exercises they have done and logs the information in a Google Sheet via the Sheety API. The script uses the Nutritionix API to get details about the exercises, such as the number of calories burned, and then logs the workout information to a Google Sheet using the Sheety API.

## Prerequisites

To run this script, you will need:

- Python 3.x
- The `requests` library
- Nutritionix API credentials (app ID and API key)
- Sheety API credentials (username and password)

## Installation

To install the `requests` library, run the following command:

```
pip install requests
```

## Usage

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/exercise-tracker.git
   ```

2. In the cloned repository, open the `exercise_tracker.py` file in a text editor.

## Configuration

To configure the program, you will need to set the following constants in the workout_tracker.py file:

GENDER: Your gender ('male' or 'female').
WEIGHT_KG: Your weight in kilograms.
HEIGHT_CM: Your height in centimeters.
AGE: Your age.
APP_ID: Your Nutritionix API ID.
API_KEY: Your Nutritionix API key.
exercise_endpoint: The Nutritionix API endpoint for exercise tracking.
sheet_endpoint: The Sheety API endpoint for logging the exercise details.
You will also need to provide your Sheety API username and password for authentication.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

The Nutritionix API and Sheety API were used for exercise tracking and logging, respectively.
