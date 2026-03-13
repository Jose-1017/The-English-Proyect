# Numerical Comparison Analyzer 🧮

This project consists of a computational logic script designed to evaluate the magnitude relationship between two floating-point values. It serves as a fundamental tool for automated decision-making.

---

## 📝 Functional Description
The program operates under a hierarchical control flow. Its objective is to classify the relationship between two numerical inputs into one of three possible categories: **Equality**, **First-value superiority**, or **Second-value superiority**.

### The Logical Process:

1. **Data Capture:** The system prompts the user for two values. These are processed as decimal numbers (`float`), allowing for greater precision than simple integers.
2. **First Validation (Equality):** The program first checks if both numbers occupy the same value on the number line. If so, it issues an equality confirmation and terminates.
3. **Magnitude Evaluation (Alternative Condition):** If the numbers are not equal, the system moves to a second stage where it checks if the first value entered is greater than the second.
4. **Resolution by Exclusion:** If none of the previous conditions are met (they are not equal and the first is not greater), the system logically deduces that the second number is the larger one, without the need for an explicit third 
