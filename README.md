# Unity Quiz and Snake Game

Welcome to our Unity project featuring a psychological quiz and an engaging snake game. This README provides a quick overview of the project's structure, features, and setup.

## Features

- **Psychological Quiz:**
  - Blue background for feeling trust and privacy.
  - Background sound for engagement.
  - Persona identification via Python analysis.
  - Quiz output saved as "quiz_output.csv."

- **Snake Game:**
  - Dynamic snake configuration based on quiz personas.
  - Happy and sad emojis for scoring.
  - Transient sad emojis to represent fleeting moments.
  - Game concludes on collision.

## Project Structure

- **Quiz Game:**
  - **Scripts:**
    - "GameManager.cs" - Manages quiz flow.
  - **Data:**
    - "DataListQA" - Array storing quiz questions.
  - **Output:**
    - "quiz_output.csv" - CSV file containing quiz personas.

- **Snake Game:**
  - **Scripts:**
    - "Board.cs" - Initializes game space.
    - "Snake.cs" - Defines snake and loads CSV personas.
    - "Game.cs" - Manages scoring and game state.

## Quiz Game

1. Answer quiz questions.
2. Quiz output is saved as "quiz_output.csv."

## Snake Game

1. Play after completing the quiz.
2. Snake configuration based on quiz personas.
3. Collect happy emojis, avoid sad emojis.
4. Game concludes on collision, showing the final score.
