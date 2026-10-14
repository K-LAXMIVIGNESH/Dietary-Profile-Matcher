# 🥗 Dietary Recommendation System Using BST

## 📌 Project Overview

The Dietary Recommendation System is a Python-based project that uses a Binary Search Tree (BST) to find the dietary profile whose calorie requirements are closest to a given target. It then recommends meals based on the matched profile's diet type and dietary restrictions.

This project demonstrates the practical application of Data Structures and Algorithms (DSA) in a dietary recommendation system.

## ✨ Features

- Stores dietary profiles using a Binary Search Tree.
- Finds the closest calorie requirement using tree traversal.
- Supports vegetarian and keto diet categories.
- Generates meal plans from predefined meal data.
- Filters meals based on dietary restrictions.
- Displays the matched profile's details and recommended meals.

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- Binary Search Tree (BST)
- Recursion and Tree Traversal
- Dictionaries and Lists

## 📂 Project Structure

    Dietary-Recommendation-System/
    ├── FINAL_CODE_DSA.py
    ├── README.md
    └── requirements.txt

## ⚙️ Installation and Setup

### Prerequisites

- Python 3 installed on your system.
- Git installed (optional).

### Clone the Repository

Replace the URL below with your GitHub repository URL.

    git clone <your-github-repository-url>

Navigate to the project folder:

    cd Dietary-Recommendation-System

## ▶️ How to Run

Execute the Python program:

    python FINAL_CODE_DSA.py

On Windows, you can also use:

    py FINAL_CODE_DSA.py

No external Python packages are required for the current version.

## 🔍 How It Works

1. Creates dietary profiles containing personal details, diet type, calorie requirements, and dietary restrictions.
2. Inserts the profiles into a BST based on calorie requirements.
3. Traverses the tree to calculate the difference between the target calories and each profile's calorie needs.
4. Selects the profile with the smallest calorie difference.
5. Retrieves the meal plan corresponding to the matched profile's diet type and calorie requirement.
6. Filters meals using the dietary restriction terms.
7. Displays the matched profile and available meal recommendations.

## 🧮 Algorithm

**Input:** Target calorie requirement.

**Output:** Closest matching dietary profile and available meal recommendations.

1. Initialize the BST.
2. Insert all dietary profiles into the BST.
3. Perform in-order traversal.
4. Calculate the absolute calorie difference for each profile.
5. Select the profile with the minimum difference.
6. Retrieve the corresponding meal plan.
7. Filter meals according to the listed dietary restrictions.
8. Display the results.

## ⚠️ Limitations

- Dietary profiles and meal plans are hardcoded.
- Meal plans are available only for selected calorie values.
- The current implementation uses a fixed target of 2500 calories.
- Dietary restriction filtering is based on text matching rather than ingredient-level analysis.
- Recommendations are not medically validated.

## 🚀 Future Enhancements

- Add interactive user input.
- Expand the meal database.
- Support more diet types.
- Improve food restriction and allergen handling.
- Develop a web or desktop interface.
- Store profiles in a database.
- Add automated unit tests.

## 🎯 Learning Outcomes

- Understanding Binary Search Trees.
- Implementing recursive tree traversal.
- Applying Object-Oriented Programming.
- Using search algorithms for profile matching.
- Applying DSA concepts to a practical recommendation problem.

## 📄 Disclaimer

This project is developed for educational purposes. Meal recommendations are based on predefined sample data and should not be considered personalized medical or nutritional advice.

---

**Developed using Python 3 | Data Structures and Algorithms Project**
