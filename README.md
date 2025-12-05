📘 Daily Homework

1️⃣ What are the web applications used in Python?

Python provides several frameworks for building web applications:

Popular Web Frameworks

Django – Full-stack framework for large applications

Flask – Lightweight framework for small/medium apps & APIs

FastAPI – High-performance API development

Pyramid

Bottle

Web2Py

Types of Web Applications Built Using Python

E-commerce platforms

Social networking sites

REST APIs

Data dashboards

Blog/CMS systems

Authentication systems

2️⃣ Git – 10 Common Commands
git init
git clone <repo-url>
git status
git add .
git add <filename>
git commit -m "message"
git push origin main
git pull
git branch
git checkout <branch>
git merge <branch>

3️⃣ What is GitHub?

GitHub is a cloud-based platform used to store and manage Git repositories.
It enables:

Collaboration between developers

Version control

Pull requests & code reviews

Issue tracking

CI/CD & project management

4️⃣ Difference Between Compiler and Interpreter
Feature	Compiler	Interpreter
Translation	Entire code at once	Line-by-line
Speed	Faster	Slower
Error detection	After full compilation	Immediately
Output	Creates executable	No executable file
Languages	C, C++, Java	Python, JavaScript

5️⃣ What are HackerRank, Project Euler, and Boot.dev?
HackerRank

A coding practice and technical interview preparation platform with challenges in algorithms, data structures, SQL, and more.

Project Euler

A platform offering mathematical and logical programming challenges to develop problem-solving skills.

Boot.dev

An online learning platform focused on backend development, offering courses in Python, Go, databases, and computer science fundamentals.

6️⃣ What is TDD and BDD?
TDD (Test-Driven Development)

TDD is a development method where tests are written before the code.

Cycle:

Write a failing test

Write code to pass the test

Refactor

Advantages:

Fewer bugs

Clean code

High test coverage

BDD (Behavior-Driven Development)

BDD focuses on the behavior expected by the user, written in simple language.

Uses the Given–When–Then format.

Advantages:

Better communication between dev, QA, and business

Requirements become clear

Tests describe real user behavior

7️⃣ What are the features of a web application?
General Features

User authentication (Login/Register)

Database connectivity

Dynamic content

API interactions

Security (SSL, hashing, sessions)

Responsive UI

Error handling & logging

Technical Features

Client–server architecture

Session management

CRUD operations

Deployment & scalability

8️⃣ What is SQL?

SQL (Structured Query Language) is used to manage and interact with relational databases.

SQL is used for:

Creating databases/tables

Inserting, updating, deleting data

Querying data

Joining tables

Managing permissions

Examples of SQL Commands
SELECT * FROM users;
INSERT INTO users VALUES (1, 'Yashwanth');
UPDATE users SET name='Yash' WHERE id=1;
DELETE FROM users WHERE id=1;

9️⃣ Why do we use environment variables? How do they help?

Environment variables store configuration and sensitive information outside the source code.

Why they are useful:

Secure (no hardcoded secrets)

Different values for dev, test, production

Easy to manage and update

Makes applications portable

Examples
SECRET_KEY=abc123
DATABASE_URL=mysql://root:pass@localhost/db
API_KEY=xyz789
