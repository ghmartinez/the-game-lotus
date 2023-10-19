# The Lotus Game Web Application

Welcome to the official repository of **The Lotus Game**, a web application built using Ruby on Rails. The Lotus Game is a strategic challenge-based game where players can create accounts, take on challenges, and compete to win challenges from other players. 🪷

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Lotus Game is a unique and engaging web-based game where players can register, challenge each other, and strategically win challenges to accumulate their collection of challenges. Each player is assigned a challenge generated by the admin, and the objective is to successfully complete the challenge and take on challenges from other players.

## Features

- User Registration: Players can create user accounts to participate in the game.
- Challenge Generation: Admins can generate challenges for each registered user.
- Challenge Gameplay: Players receive challenges from other users and aim to win them.
- Challenge Collection: Successful completion of challenges allows players to collect challenges from opponents.
- Leaderboard: Keep track of top players based on the number of challenges won.
- User Profiles: Customize user profiles with avatars, bios, and challenge collections.

## Installation

Follow these steps to set up and run The Lotus Game on your local machine:

1. Clone this repository: `git clone git@github.com:ghmartinez/the-lotus-game.git`
2. Navigate to the project directory: `cd the-lotus-game`
3. Install the required gems: `bundle install`
4. Set up the database: `rails db:create db:migrate`
5. Start the Rails server: `rails server`
6. Open your web browser and visit: `http://localhost:3000`

## Usage

1. Register an account on the website.
2. Once registered, the admin will generate a challenge for you.
3. Review the challenge details and strategize your approach.
4. If you successfully win a challenge from another user, you'll gain their challenge.
5. Keep completing challenges and collecting new ones to rise in the leaderboard.

## Contributing

Contributions to The Lotus Game are welcome! If you'd like to contribute new features, improvements, or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m "Add your commit message"`
4. Push the changes to your fork: `git push origin feature/your-feature-name`
5. Create a pull request explaining your changes.
