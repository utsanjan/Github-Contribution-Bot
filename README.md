# GitHub Contribution Bot

**Does your GitHub Graph looks like a noob<br>
with a few number of Commits and Push?<br>
Do you want to have your contribution<br>
graph with lots of commit like pro,<br>
then this project is at your rescue.<br>
Manipulate your GitHub profile's<br>
contribution graph with ease**

## 🔸 List of Contents

- [Introduction](#-introduction)
- [Installation](#%EF%B8%8F-installation)
- [Commits](#-commits)

### 🤓 Introduction

The project uses [Moment](https://www.npmjs.com/package/moment), a JavaScript date library for parsing, validating, manipulating, and formatting dates. It allows you to make a commit on past date done by subtracting the years from given date and make commits over a period of regular days. Also you can do alot with this code.

### 🛠️ Installation

Clone and fork the repository to make the changes in your local system.

```git-bash
git clone https://github.com/utsanjan/Github-Contribution-Bot
cd Github-Contribution-Bot
```

Now this command creates a directory named node_modules and installs all the required packages in it.

```javascript
npm install
```

Finally, run the project to see what the moment package does.

```javascript
node index.js
```

Voilà!!
You can see the commit date in terminal.

### 💻 Commits

```javascript
subtract(year, "y");
```

year here represents the year to start the commits. Greater the value of year, more dense the graph along main axis. Example - subtract(2,'y')

```javascript
add(days, "d");
```

Difference of commits between timestamps. Less the value of days, more dense the contributon graph will be. Example - add(4,'d')
