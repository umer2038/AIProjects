**Game Bot – AI Agent for Street Fighter II using Machine Learning
Artificial Intelligence Project | Spring 2025
Team Size: 3 | Role: ML Engineer & Game AI Developer
**
In this exciting project, we built an intelligent Game Bot that plays Street Fighter II Turbo using machine learning algorithms instead of rule-based or reinforcement learning logic. The goal was to create a general-purpose bot capable of playing with any character, based purely on in-game percepts and learned behavior from data.

We started by understanding and reverse-engineering the game’s real-time API via the BizHawk emulator, where we accessed player states, moves, coordinates, and health stats. Our team played several rounds manually to generate a custom dataset of percepts (game states) and actions (button presses), which we then used to train classification models.

The core of our solution was a supervised learning pipeline that predicts optimal actions in real-time. The trained model was embedded into the bot logic to react dynamically during gameplay.

This project allowed us to blend real-time systems, game AI, and ML in a unique and challenging way.

**Key Contributions**
Reverse-engineered Street Fighter II's internal mechanics using BizHawk emulator.

Created a real-time data logging system to capture in-game percepts and corresponding human actions.

Trained ML models (e.g., Random Forest, KNN, MLP) to map game states to actions.

Integrated the trained model with the emulator to control the bot live during gameplay.

Achieved dynamic, character-independent bot behavior.
