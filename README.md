# Fitness Tracker – Java OOP Application

This is a console-based fitness tracking application developed in Java as part of CST8284 – Object-Oriented Programming at Algonquin College. The app calculates and evaluates a user’s activity level and calorie balance based on user input. It also includes a full suite of automated unit tests using JUnit.

## 🚀 Features

- User input via console (Scanner)
- Calculates:
  - Distance walked (gender-based)
  - Weekly active minutes
  - Activity level: Active / Moderately Active / Sedentary
  - Calorie surplus or deficit
- Dynamic report generation using `System.out.printf`
- JUnit testing with 11 unit tests covering all major methods

## 🧱 Class Structure

- `FitnessTracker`: Core class with:
  - Instance variables (name, gender, steps, etc.)
  - Methods: `calcDistance()`, `calcWeeklyActiveMinutes()`, `determineActiveLevel()`, `calcMaintenanceCalories()`, `displayFitnessData()`

- `FitnessTrackerTest`: Main class with console input for real-time user interaction

- `FitnessTrackerTest2`: JUnit test class with multiple test cases validating all logical calculations

## 🧪 Example Output

![Output Screenshot](Lab_Section_321_Mahmoud_Ibrahim_output2.jpg)

## 🧠 Skills Demonstrated

- Object-Oriented Programming (encapsulation, constructors, methods)
- Java control structures and user input
- Modular code design and documentation
- Unit Testing with `JUnit` and assertions
- Code clarity and professional formatting

## ▶️ How to Run

1. Clone this repo:
   ```
   git clone https://github.com/Mahmoud3Ibrahim/Fitness-Tracker.git
   ```

2. Compile and run `FitnessTrackerTest.java` to launch the app:
   ```
   javac FitnessTracker.java FitnessTrackerTest.java
   java FitnessTrackerTest
   ```

3. Run tests with JUnit in your IDE or via:
   ```
   javac -cp .:junit-4.13.2.jar:hamcrest-core-1.3.jar FitnessTrackerTest2.java
   java -cp .:junit-4.13.2.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore FitnessTrackerTest2
   ```

## 📸 UML Diagrams

![UML Main Class](Lab_Section_321_Mahmoud_Ibrahim_UML_main.png)  
![UML Tracker](Lab_Section_321_Mahmoud_Ibrahim_UML._FitnessTracker.jpg)  
![UML Test](Lab_Section_321_Mahmoud_Ibrahim_UML_FitnessTrackerTest2.jpg)

---

📌 **Course**: CST8284  
👨‍🏫 **Instructor**: Dr. Leanne Seaward  
👨‍💻 **Author**: Mahmoud Ibrahim – 041163059  
📅 **Term**: Winter 2025
