# 🐍 Snake Game - **(Kotlin | Jetpack Compose)**

A modern and minimalist implementation of the classic **Snake Game**, built entirely using the **Kotlin** programming language and Google's declarative UI toolkit, **Jetpack Compose**.

This project aims to showcase best practices in structuring a Compose application, particularly in handling the logic and state management for simple 2D games, while adhering to **Clean Architecture** principles.

## 🌟 **Key Features**

* **Clean Architecture Inspired:** Clear separation of game logic, data handling, and the user interface.
* **Jetpack Compose:** Fully declarative and modern Android UI development.
* **MVI/MVVM Pattern:** Optimal state management using a unidirectional data flow for a reactive game experience.
* **Classic Gameplay:** Accurate implementation of core Snake mechanics (movement, eating, length increase, and game over).
* **Modular Design:** Logical and maintainable directory structure for scalability.

## 📂 **Project Structure**

The project structure enforces a clear **Separation of Concerns** across the **Data**, **Domain**, and **Presentation** layers, ensuring the project is scalable, testable, and easy to maintain.

## 🌟 **Key Features**

* **Clean Architecture Inspired:** Clear separation of game logic, data handling, and the user interface.
* **Jetpack Compose:** Fully declarative and modern Android UI development.
* **MVI/MVVM Pattern:** Optimal state management using a unidirectional data flow for a reactive game experience.
* **Classic Gameplay:** Accurate implementation of core Snake mechanics (movement, eating, length increase, and game over).
* **Modular Design:** Logical and maintainable directory structure for scalability.

## 📂 **Project Structure**

The project structure enforces a clear **Separation of Concerns** across the **Data**, **Domain**, and **Presentation** layers, ensuring the project is scalable, testable, and easy to maintain.

### 💡 **Layer Responsibilities:**

* **`domain`:** The **core engine**. Contains the pure game rules. It has zero dependencies on Android or Compose.
* **`data`:** The implementation layer for data operations (e.g., saving and retrieving the high score).
* **`presentation`:** The display layer. Uses ViewModels (often placed within `screen`) to manage state and render the UI using Compose.

## 🚀 **Getting Started**

To run and build this project, you will need **Android Studio (Hedgehog or newer)**.

1.  **Clone** the repository:
    ```bash
    git clone [https://github.com/amirdorri/snake-game]
    ```
2.  Open the project in **Android Studio**.
3.  Wait for the Gradle sync to complete.
4.  Run the application on an Android emulator or physical device.

## 🛠 **Technologies Used**

* **Kotlin:** Primary development language.
* **Jetpack Compose:** For building the reactive user interface.
* **Compose Navigation:** For managing screen transitions.
* **Coroutines / Flow:** For handling game state and timed updates.

## 🤝 **Contributing**

Contributions are highly welcome! If you have ideas for improvements, want to fix a bug, or add a new feature, please feel free to open an Issue or submit a Pull Request.
