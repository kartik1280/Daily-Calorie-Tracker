# Daily Calorie Tracker CLI

A simple Python command-line application to help you track your daily calorie intake, compare it against your personal daily limit, and save your session logs for future reference.

## Features

- Log multiple meals with names and calorie amounts
- Calculates total and average calorie intake
- Warns if daily calorie limit is exceeded
- Displays a neatly formatted summary table
- Optionally saves daily session data to a file

## Getting Started

### Prerequisites

- Python 3.13.7 installed on your system

### Running the Tracker

1. Clone or download this repository to your computer.
2. Open your terminal or command prompt.
3. Navigate to the folder containing `Tracker.py`.
4. Run the program by typing: python Tracker.py


### How to Use

- Enter the number of meals you had today when prompted.
- For each meal, enter the meal name and the number of calories (decimals allowed).
- Enter your daily calorie limit.
- View the summary of meals, total calories, average calories, and whether you stayed within your limit.
- Choose whether to save the session log by typing "yes" or "no":
- If yes, enter the date for this session in `DD/MM/YYYY` format.
- The data will be saved/appended to `record.txt` in the project directory.

### Example

Welcome to the Daily Calorie Tracker!
This tool helps you record your meals and calories
it checks if you stayed within your daily limit
and it can save your session for future tracking.

enter the number of meals you've had today: 3
enter the name of meal 1: Breakfast
enter the anount of calories in Breakfast: 350
enter the name of meal 2: Lunch
enter the anount of calories in Lunch: 600
enter the name of meal 3: Snack
enter the anount of calories in Snack: 150

What is your daily calorie limit: 1100
Great job! You're within your daily calorie limit.

Meal Name Calories

Breakfast: 350.0
Lunch: 600.0
Snack: 150.0
Total: 1100.0
Average: 366.67

Do you want to save this session to a file? (yes/no): yes
enter today's date (like 02/08/2025): 04/10/2025
Session has been saved to record.txt!

Thank you for using the Daily Calorie Tracker!
Stay healthy and have a great day! 😊


## Notes

- Calories can be entered as decimal values.
- The program prevents division by zero errors if no meals are entered.
- The saved session log (`record.txt`) appends new entries to preserve history.
- Make sure to enter the date yourself when saving; automatic date functionality is not included.

## License
This project is for learning purposes. Feel free to use and modify it with proper credit.

## Author
Kartik Sharma



