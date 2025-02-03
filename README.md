# Snake Game - Python (Pygame)

This project is a simple 2-player snake game built with Python and Pygame. One player controls a snake using the keyboard, while the other snake is controlled by AI. The game ends when one snake collides with the other snake's body or with its own body.  
This game is fully generated using ChatGPT-03-mini-High, for testing its coding compatibility.

### Features:
- **Player-controlled snake** using arrow keys.
- **AI-controlled snake** that moves intelligently towards food.
- **Snake growth**: Both snakes grow when they eat food.
- **Boundary wraparound**: Snakes wrap around the screen edges.
- **Collision detection**: The game ends if a snake's head collides with its body or the other snake's body.
- **Game-over screen**: Shows the winner and the reason for the game over.

---

## Getting Started

To run the Snake Game locally, you will need to have Python and Pygame installed.

### Prerequisites

1. **Python Installation**:

    #### For macOS:
    If you don't have Python installed, you can install it via Homebrew (recommended) or by downloading it from the Python website.
    - **Install Python with Homebrew**:
      ```bash
      brew install python
      ```
    - **Download Python**:
      Visit the [official Python website](https://www.python.org/downloads/) to download and install the latest version.

    #### For Windows:
    - **Download Python**:
      Visit the [official Python website](https://www.python.org/downloads/) and download the installer for Windows. During installation, ensure you check the box that says "Add Python to PATH."

    Once Python is installed, verify the installation by running:
    ```bash
    python --version
    ```
    You should see the Python version you installed.

---

2. **Clone the Repository**:

    To get the game on your local machine, clone the repository using Git:

    ```bash
    git clone https://github.com/yourusername/snake-game.git
    cd snake-game
    ```

    Replace `https://github.com/yourusername/snake-game.git` with the actual URL of your repository.

---

3. **Set up a Virtual Environment**:

    A virtual environment will help you manage the project's dependencies. Follow these steps to create and activate a virtual environment.

    ```bash
    python -m venv venv
    # Activate the virtual environment:
    # For macOS/Linux:
    source venv/bin/activate
    # For Windows:
    venv\Scripts\activate
    ```

    You should now see `(venv)` in your terminal prompt, indicating that the virtual environment is active.

---

4. **Install Dependencies**:

    After activating the virtual environment, install the necessary dependencies (Pygame in this case).

    ```bash
    pip install pygame
    ```

---

5. **Run the Game**:

    With the dependencies installed, you can run the game using the following command:

    ```bash
    python main.py
    ```

---

## Additional Information

- **Game Controls**:  
    - Use the **arrow keys** to control the player-controlled snake.
    - The **AI-controlled snake** will automatically move towards the food and try to avoid obstacles.

- **Game Over**:  
    The game ends if either snake collides with its own body or the other snake's body. The winner will be displayed on the screen, along with the reason for the game over.

---

## Troubleshooting

- **Python version issue**:  
    If you encounter issues with Python version compatibility, ensure you are using Python 3.13 or higher. You can verify the Python version by running:
    ```bash
    python --version
    ```

- **Pygame installation issue**:  
    If you face issues installing Pygame, try upgrading `pip`:
    ```bash
    pip install --upgrade pip
    ```

---

## Contributing

If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Contributions are welcome!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
