CodeArena — College Coding Practice & Contest Platform

CodeArena is a front-end prototype for a college coding practice and contest platform. It brings coding challenges, multiple-choice quizzes, timed contests, a student dashboard, and a leaderboard into one responsive interface.

Project status: Front-end prototype/demo. It uses sample data and browser storage; it does not currently have a backend, user authentication, or a real code-execution engine.

Features

Student login demo: Enter a name or roll number to open the platform. The name is saved in the browser's localStorage.

Dashboard: View sample stats, recommended practice activities, and upcoming contest cards.

Problems and quizzes: Browse sample coding problems and multiple-choice quizzes with difficulty labels.

Code editor interface: View a problem, edit starter code, and choose from the displayed language options: JavaScript (Node.js), Python 3, C++, and Java.

Submission demo: Submitting code displays a simulated evaluation result. It does not compile or execute the submitted code.

Quizzes: Answer multiple-choice questions and receive feedback for correct or incorrect answers.

Timed contest: Try a 15-minute, 10-question multiple-choice contest, navigate between questions, and view a result summary.

Leaderboard: View sample student rankings and demo rating information.

Responsive UI: Styled for different screen sizes using Tailwind CSS utility classes.

Built With

HTML5

CSS

JavaScript (vanilla)

Tailwind CSS via CDN

Font Awesome for icons

Google Fonts: Inter and Fira Code

Getting Started

Run locally

Download or clone this repository.

Keep the HTML file in the project root and rename it to index.html (recommended).

Open index.html in a modern web browser.

No package installation or build step is required. An internet connection is needed to load the Tailwind CSS, Font Awesome, and Google Fonts resources from their CDNs.

Clone using Git

Replace the placeholders with your GitHub username and repository name:

git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>

Then open index.html in your browser.

How to Use

Enter any name or roll number on the login screen.

Explore the dashboard, problems, quizzes, contests, and leaderboard.

Open a coding problem to view its description and starter code.

Attempt a quiz or start the timed contest to see the demo feedback and results.

The login name and solved count are stored in browser localStorage. This is only for demonstrating the interface and is not a secure account system or persistent multi-user database.

Current Limitations

There is no backend, database, or real authentication.

Code submissions are simulated; submitted code is not run against test cases.

The language selector is part of the interface only; it does not switch or configure a compiler.

Some controls, such as code execution and contest registration, are placeholders and may not perform an action.

Dashboard statistics, ratings, participants, and leaderboard entries are sample/demo values.

Browser localStorage data is local to the browser and device where the project is opened.

Possible Future Improvements

Add a backend and database for user accounts, problems, submissions, and contest history.

Integrate a secure code-execution service with test cases and runtime limits.

Make problem search, difficulty filters, and contest registration functional.

Add real-time contest participation and server-backed leaderboards.

Add automated tests, error handling, and accessibility improvements.

Deployment

Because this is a static front-end project, it can be hosted using GitHub Pages:

Push the HTML file and README.md to your GitHub repository.

In the repository, open Settings → Pages.

Under the build and deployment options, choose Deploy from a branch.

Select the main branch and the repository root (/), then save.

Open the published URL shown in the Pages section after deployment completes.

Make sure the main HTML file is named index.html for the root page to load automatically.

License

No license has been specified for this project yet. Add a LICENSE file if you intend to publish it with explicit reuse permissions.
