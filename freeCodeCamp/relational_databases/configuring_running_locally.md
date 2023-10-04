# How to run freeCodeCamp courses locally?

---

This is done by running a docker container on the computer that has the software and file structure required for the tutorials.

## Prerequisites

- [x] The docker engine
- [x] VS Code
- [x] The [DEV Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [x] Git

## Running a project in Docker

1. Clone the RDB Alpha repo to your computer:
   `git clone https://github.com/freeCodeCamp/rdb-alpha`.
2. Open a terminal and navigate to the rdb-alpha directory with `code .`
3. In VS Code, open the command palette with `ctrl + shift + p`. Then enter and run `Dev Containers: Rebuild and Reopen in Container`.
4. A new VS Code window will open and begin building the Docker image. It will take several minutes to build the first time.
5. Once the image is finished building, open the command palette again with `Ctrl + Shift + P`, enter and run `CodeRoad: Start`. The command won't be available until the extension has finished installing in your container.
6. In the CodeRoad window, click "Start New Tutorial"
7. Click the `URL` tab and enter the URL of the `tutorial.json` file for the project you want to start (ex: https://raw.githubusercontent.com/freeCodeCamp/learn-bash-by-building-a-boilerplate/main/tutorial.json) Full list of available tutorials below.
8. Click the "Start" button to start lessons.

## Switching through courses

> If one restarts or switch projects, the progress on a tutorial will be lost along with any files or folders created.

1. Open the command palette with `Ctrl / Cmd + Shift + P`, enter and run `Dev-Containers: Rebuild Container`
2. Wait for VS Code to reopen and reload the container
3. Open CodeRoad from the command palette like before, click "Start New Tutorial", and enter the URL of the `tutorial.json` file for the project you want to do.

## Available Courses

Here is a list of tutorials currently available. Open one of them and use its URL, as described in the instructions above, to start it.

- [Learn Bash by Building a Boilerplate](https://raw.githubusercontent.com/freeCodeCamp/learn-bash-by-building-a-boilerplate/main/tutorial.json)
- [Learn Relational Databases by Building a Mario Database](https://raw.githubusercontent.com/freeCodeCamp/learn-relational-databases-by-building-a-mario-database/main/tutorial.json)
- [Celestial Bodies Database](https://raw.githubusercontent.com/freeCodeCamp/learn-celestial-bodies-database/main/tutorial.json)
- [Learn Bash Scripting by Building Five Programs](https://raw.githubusercontent.com/freeCodeCamp/learn-bash-scripting-by-building-five-programs/main/tutorial.json)
- [Learn SQL by Building a Student Database: Part 1](https://raw.githubusercontent.com/freeCodeCamp/learn-sql-by-building-a-student-database-part-1/main/tutorial.json)
- [Learn SQL by Building a Student Database: Part 2](https://raw.githubusercontent.com/freeCodeCamp/learn-sql-by-building-a-student-database-part-2/main/tutorial.json)
- [World Cup Database](https://raw.githubusercontent.com/freeCodeCamp/learn-world-cup-database/main/tutorial.json)
- [Learn Advanced Bash by Building a Kitty Ipsum Translator](https://raw.githubusercontent.com/freeCodeCamp/learn-advanced-bash-by-building-a-kitty-ipsum-translator/main/tutorial.json)
- [Learn Bash and SQL by Building a Bike Rental Shop](https://raw.githubusercontent.com/freeCodeCamp/learn-bash-and-sql-by-building-a-bike-rental-shop/main/tutorial.json)
- [Salon Appointment Scheduler](https://raw.githubusercontent.com/freeCodeCamp/learn-salon-appointment-scheduler/main/tutorial.json)
- [Learn Nano by Building a Castle](https://raw.githubusercontent.com/freeCodeCamp/learn-nano-by-building-a-castle/main/tutorial.json)
- [Learn Git by Building an SQL Reference Object](https://raw.githubusercontent.com/freeCodeCamp/learn-git-by-building-an-sql-reference-object/main/tutorial.json)
- [Periodic Table Database](https://raw.githubusercontent.com/freeCodeCamp/learn-periodic-table-database/main/tutorial.json)
- Learn GitHub by Building a List of Inspirational Quotes (coming soon)
- [Number Guessing Game](https://raw.githubusercontent.com/freeCodeCamp/learn-number-guessing-game/main/tutorial.json)

obs: \
`git branch -m my_first_branchhhh master` \
`git fetch origin` \
`git branch -u origin/master master` \
`git remote set-head origin -a` AFTER CHANGING THE DEFAULT BRANCH NAME
