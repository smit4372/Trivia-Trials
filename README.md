# Trivia Trials

**Trivia Trials** is an interactive trivia game where players answer progressively challenging questions, use lifelines strategically, and aim to achieve the highest possible score. With engaging gameplay mechanics and dynamic question loading, Trivia Trials promises an exciting experience for all trivia enthusiasts.

---

## Features

1. **Challenging Levels**:
   - 15 levels of increasing difficulty.
   - Players earn or lose points based on their answers.

2. **Dynamic Question Loading**:
   - Questions are loaded from external files for scalability and customization.
   - Randomized question order for a unique experience every time.

3. **Lifelines**:
   - 4 lifelines available, each usable once per game:
     - **Audience Poll**
     - **50:50**
     - **Double Dip**
     - **Skip the Question**

4. **Score Management**:
   - Points earned vary by level difficulty.
   - Post-level 10 gameplay transitions to a high-stakes "do or die" mode.

5. **Win Conditions**:
   - Earn as many points as possible.
   - Successfully answer all 15 questions to win the grand prize.

---

## How to Play

1. Clone or download the repository to your local machine.
   ```bash
   git clone https://github.com/smit4372/trivia-trials.git
   ```

2. Compile the game using any C++ compiler (e.g., `g++`):
   ```bash
   g++ -o trivia_trials trivia_trials.cpp
   ```

3. Run the compiled program:
   ```bash
   ./trivia_trials
   ```

4. Follow the on-screen instructions to play the game.

---

## File Structure

```
Trivia Trials/
├── README.md                # Game documentation
├── src/
│   └── main.cpp             # Main game source code
├── questions/               # Folder containing question files
│   ├── question1.txt
│   ├── question2.txt
│   └── ...
├── build/
├── .gitattributes
└── .gitignore

```

- **`questions/`**: Contains individual text files for each question. Each file includes:
  - The question text.
  - Four answer choices.
  - The correct answer.

---

## Sample Question File Format

Example: `question1.txt`
```
What is the capital of France?
Paris
London
Berlin
Madrid
Paris
```

---

## Technologies Used

- **Programming Language**: C++
- **Randomization**: Used for shuffling questions and lifelines.
- **File Handling**: To dynamically load questions.

---

## Future Enhancements

1. Add more lifelines for varied gameplay.
2. Implement a graphical user interface (GUI).
3. Include categories or difficulty levels for questions.
4. Multiplayer mode.
5. Online leaderboard to track high scores.

---

## Contribution Guidelines

Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

**Smit Desai**  
[GitHub Profile](https://github.com/sdesai36) 
[LinkedIn Profile](https://www.linkedin.com/in/smitldesai4372/)
Feel free to reach out with any questions or feedback!

---

## Acknowledgments

- Inspired by trivia games like *Who Wants to Be a Millionaire?*.
- Thanks to everyone who provided feedback and support during development.
