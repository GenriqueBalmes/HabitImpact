# **Habit Impact** 🚀

## **Project Overview** 📖
*Habit Impact* is a Java-based console application designed to encourage users to develop healthier habits. By allowing users to log daily habits, view weekly summaries, and set personal goals, the application promotes accountability and mindfulness. The program aligns with **Sustainable Development Goal (SDG) 3: Good Health and Well-being**, aiming to foster healthier lifestyles and improve well-being.

👉 **Key Features:**
- Log habits like food intake, hydration, and screen time.
- Track progress through weekly summaries.
- Set and monitor personal goals.
- Reset weekly data for a fresh start.

---

## **Object-Oriented Programming Principles** 🖥️
This project is built using the core principles of Object-Oriented Programming (OOP):

### **1. Encapsulation** 🔒
   - Data fields in the classes, such as `dailyScore` in the `Habit` class, are private to restrict direct access.
   - Public getter and setter methods are used to access and modify private fields safely.
   - **Example:** The `Habit` class uses private fields and public methods to maintain data integrity.

### **2. Inheritance** 🌳
   - The abstract class `Habit` is the parent class, with subclasses like `Food`, `HydrationHabit`, and `ScreentimeHabit` inheriting shared attributes and behaviors.
   - This promotes code reuse and establishes a hierarchical relationship between general and specific habit types.
   - **Example:** The `Food` class extends the `Habit` class to provide specific implementations for logging food habits.

### **3. Polymorphism** 🔀
   - Method overriding is applied in the subclasses to provide specific implementations of the `logHabit` and `provideFeedback` methods.
   - This allows the program to handle different habit types uniformly while enabling specific behavior for each habit.
   - **Example:** Each habit type (e.g., `Food`, `ScreentimeHabit`) overrides the `logHabit()` method to handle different input formats.

### **4. Abstraction** 🎭
   - The abstract `Habit` class defines common properties and behaviors for all habits, while leaving the implementation of certain methods, such as `logHabit` and `provideFeedback`, to the subclasses.
   - This hides implementation details while exposing essential functionalities.
   - **Example:** The `Habit` class provides a template for all habit types, ensuring consistent behavior.

---

## **Sustainable Development Goal (SDG) Integration** 🌍
### **SDG 3: Good Health and Well-being** 💪
This project directly contributes to SDG 3 by:
- **Promoting healthy eating habits** through the `Food Habit` logging feature. 🥗
- **Encouraging hydration** by tracking water intake. 💧
- **Reducing screen time** to improve mental and physical well-being. 📱❌

The program fosters long-term behavioral change by providing users with actionable feedback and motivation to maintain healthier lifestyles. Learn more about SDG 3 [here](https://sdgs.un.org/goals/goal3).

---

## **Instructions for Running the Program** 🛠️

### **Prerequisites**
- Install **Java Development Kit (JDK) 8 or higher**.
- Install [Visual Studio Code](https://code.visualstudio.com/) and the [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).

### **Steps to Run the Program**
1. **Clone the Repository**  
   Use a terminal in Visual Studio Code to clone the repository by typing:  
   ```bash
   git clone <repository-url>
   ```

2. **Open the Project**  
   Navigate to the project folder using the command:  
   ```bash
   cd habit-impact
   ```
   Then open the folder in Visual Studio Code by typing:  
   ```bash
   code .
   ```

3. **Compile the Program**  
   In the terminal, compile the Java files by typing:  
   ```bash
   javac Main.java
   ```
   Alternatively, you can use the "Run and Debug" feature in Visual Studio Code.

4. **Run the Program**  
   Execute the program by typing:  
   ```bash
   java Main
   ```
   Or use the "Run" button in Visual Studio Code.

### **Using the Program**
- **Log a Habit**: Follow the prompts to log food, hydration, or screen time habits.
- **View Weekly Summary**: Select this option to see your total and average scores for the week.
- **Set Goals**: Define weekly goals and track progress.
- **Reset Data**: Clear all logged data to start fresh.

If you encounter issues, ensure your Java environment is properly configured. For guidance, refer to the [Java Setup Documentation](https://code.visualstudio.com/docs/java/java-tutorial).

## **Acknowledgments** 🙏
- Developed as part of the CS 211 - Object-Oriented Programming course at Batangas State University.
---

