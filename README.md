# Cohcode: The C Programming Game

Cohcode is an educational game designed to help beginners learn and practice basic C programming concepts in a fun and interactive way. Inspired by classic platformers like Super Mario, this game merges gameplay with coding challenges to create an engaging learning experience.

## Purpose

The goal of Cohcode is to provide an accessible platform for students and coding enthusiasts to build a strong foundation in C programming while enjoying an adventurous game setting. Players progress through levels by solving coding problems that mirror real-world programming tasks.

## Features

- **Interactive Coding Challenges**: Players solve C programming problems to advance through the game.
- **Fun Gameplay**: Explore vibrant levels, collect items, and overcome obstacles while learning.
- **Step-by-Step Learning**: Concepts like variables, loops, and functions are introduced progressively.
- **Immediate Feedback**: Players receive instant feedback on their code to understand errors and improve.
- **Progress Tracking**: Keep track of your learning milestones as you complete levels.

## Gameplay Overview

1. **Start the Adventure**: Begin your journey as a character navigating through a platformer world.
2. **Solve Coding Problems**: Encounter puzzles where you must write or fix C code to unlock paths and continue.
3. **Collect Rewards**: Earn points and items for solving challenges correctly and efficiently.
4. **Advance Levels**: Each level introduces new programming concepts, increasing in complexity.

## Backend Technology

The backend for Cohcode is built using **Spring Boot**, providing a robust and scalable framework for managing game data, user progress, and coding challenge validation. Key features include:

- RESTful APIs for seamless communication between the game client and server
- User authentication and progress tracking
- Database integration for storing user data and level details
- Real-time feedback for coding solutions

## Piston API Integration for C Code Execution

To enhance the learning experience, Cohcode integrates **Piston API**, a powerful tool that allows players to execute and validate their C code in real-time. By utilizing Piston API, the game can instantly compile and run player-submitted C code, providing feedback on whether the solution is correct or if there are errors to fix.

### How it Works:

- **Code Submission**: After players write their C code to solve a challenge, the code is sent to the backend.
- **Code Execution**: The backend uses the Piston API to run the C code on a secure server.
- **Instant Feedback**: Piston compiles and executes the code, returning the output and any errors to the game in real-time.
- **Validation**: The game compares the output with expected results, providing players with immediate feedback on their solution.

### Benefits of Using Piston API:

- **Real-time Execution**: Players can test their solutions immediately after submitting their code, helping them understand mistakes and corrections faster.
- **Support for Multiple Languages**: Although primarily focused on C, Piston also supports various other languages, making it scalable for future game expansions.
- **Security**: Piston executes code in isolated environments to prevent malicious activity and ensure a safe environment for players.
- **Fast Feedback Loop**: The API is optimized for fast execution, providing almost instant results to keep the gameplay smooth and engaging.

### Backend Integration:

- **Spring Boot and Piston API**: Cohcode’s backend, built with Spring Boot, communicates seamlessly with Piston API to send player code and receive feedback.
- **Code Compilation**: When the player submits their C code, the backend sends the code to the Piston API, which compiles it and runs the program.
- **Error Handling**: If there are errors in the code (such as syntax errors or runtime exceptions), Piston returns detailed error messages, which are displayed to the player to help them debug.

## Target Audience

- Beginners with no prior programming experience
- Students looking for an interactive way to learn C programming
- Educators who want to gamify coding lessons

## Benefits

- Makes learning C programming approachable and enjoyable
- Combines theory with practical application
- Encourages problem-solving and logical thinking

## Development Tools

- **Game Engine**: Unity
- **Programming Language for Game Logic**: C#
- **Backend Framework**: Spring Boot
- **C Code Integration**: Custom parsers and compilers to validate player-written code
- **API for Code Execution**: Piston API

## Getting Started

1. **Clone the repository**: `git clone https://github.com/PongsatornWaiyaworn/Coh_game.git`
2. **Install dependencies**: Follow the instructions for setting up Unity, Spring Boot, and other necessary dependencies.
3. **Run the game**: Launch the Unity game to begin solving C programming challenges.
4. **Backend setup**: Configure Spring Boot to handle Piston API integration for code validation.

## Contributing

If you'd like to contribute to Cohcode, feel free to fork the repository, submit pull requests, or open issues for bugs or feature requests. Contributions are welcome!
