** QA Career Basics **

What is QA and why companies pay for it? - Quality Assurance (QA) makes sure software works the way users and the business expect, before real customers find the problems. QA is about preventing problems; testing is the activity of finding them.A bug found in production can cost far more to fix than one found during development.
Testers think like users, like attackers and like the business all at once.

What is the difference between QA and testing? - QA is the process-level work that prevents defects (reviews, standards, good requirements). Testing is executing the product to find defects. Testing is one part of QA.
What is the difference between QA and QC? - QA is process-focused and preventive: it improves how software is built so fewer defects appear. QC is product-focused and detective: it checks the finished product to find defects. Testing is one QC activity.

Can testing prove software has no bugs? - No. Testing can show bugs are present, not that they are absent. That is why we test based on risk, focusing effort where failures would hurt users or the business most.

What is shift-left testing? -Moving testing activities earlier in the project, such as reviewing requirements, joining design discussions and writing tests alongside code, so defects are found when they are cheapest to fix.
What qualities make a good tester? - Curiosity, attention to detail, clear communication, user empathy and the habit of backing every claim with evidence.
What do you do when a developer says your bug is 'not a bug'? - Go back to the requirement or expected user behaviour, share clear evidence (steps, screenshot, logs) and discuss the impact on the user calmly. If it's still unclear, ask the product owner to decide. The goal is the right outcome, not winning the argument.
SDLC - SDLC is how software gets built. requirement gathering, design, development, testing, deployment and maintenance. In Waterfall these happen one after another. In Agile they repeat in short cycles, often two weeks long.
STLC - STLC is how testing happens inside it. requirement analysis (what can be tested), test planning (scope, effort, tools)(HOW will we handle the work?"), test case design ( is the operational phase where testers create the actual step-by-step scenarios to validate the software against its original requirements.)("WHAT specific steps will we check?), test environment setup (prepares the required hardware, software, tools, configurations, and test data to execute test cases.)("WHERE will we execute our tests?), test execution (run tests, log bugs)(testing the software to check whether it works as expected.) and test closure (report results and lessons learned)(reviewing all testing activities, documenting the results, and officially finishing the testing process.). Each phase has entry criteria (what must be ready to start) and exit criteria (what must be true to finish).


What is the V-Model?- (Verification and Validation Model) -  A development model where each development phase has a matching test phase: requirements with acceptance testing, system design with system testing, architecture with integration testing and coding with unit testing. It highlights planning tests early. 
  Development (Down the V)           Testing (Up the V)
  
  Business Requirements -----------> Acceptance Testing
     System Design ---------------> System Testing
        Architecture Design ------> Integration Testing
           Module Design --------> Unit Testing
                      \          /
                       \ Coding /
 Requirement Analysis : means understanding what the customer needs before developing the software. ------------ Acceptance Testing : means checking whether the finished software does what the customer actually wanted.                    
System Design: Designing the overall software structure --------- System Testing: Testing the entire app as a whole package (matches System Design).
Architecture Design: Planning how different parts of the system talk to each other ----------- Integration Testing: means checking whether different parts of a software application communicate and work properly with each other.
Module Design: means breaking a big software system into smaller parts so that each part can perform a specific task.-------------- Unit Testing : means checking one small part of a software application at a time to make sure it works properly.
Agile : is a software development approach where a project is divided into small parts, and each part is developed and tested continuously.
Scrum : is an Agile framework that helps a team organize its work into short development cycles called Sprints. Scrum means dividing project work into small tasks, completing them within a fixed period, and reviewing the results regularly.

What is the difference between Definition of Done and acceptance criteria?- Acceptance criteria are specific to one story and describe its expected behaviour. The Definition of Done applies to every story and describes quality standards like review, testing and documentation.

**Agile and Scrum for testers- Agile and Scrum are important concepts in software testing. They explain how developers and testers work together to develop, test, and deliver software in small steps.
**Agile is a software development approach where a project is divided into small parts, and each part is developed and tested continuously.
** A sprint is a fixed 1-4 week cycle; work is written as user stories. ***
**A story is 'done' only when it is tested and meets the Definition of Done.**
**What is Scrum? - "Scrum is an Agile framework that organizes work into short development cycles called Sprints. It helps teams plan tasks, collaborate, track progress, and deliver working software regularly."
**What is a Sprint? - "A Sprint is a fixed-length period, usually between one and four weeks, during which the Scrum Team works to achieve a specific goal and deliver a usable product increment."
**How a sprint works for a tester
During sprint planning you help estimate stories, including testing effort. Through the sprint you test stories as soon as they're ready, not at the end. In the daily stand-up you share what you tested, what's blocked and any risks. In the review you help demo, and in the retrospective you suggest process improvements.
What is the role of a tester in Scrum? - "As a tester, my responsibility is to understand user stories, review acceptance criteria, prepare test cases, perform functional and regression testing, report defects, and collaborate with developers to ensure software quality throughout the Sprint."
**Types of testing you must know**
Functional Testing- Checks whether a feature works according to the requirements. 
Example: Does the login button allow a user to log in with valid credentials?
Non-Functional Testing- Checks how well the application works.
Example: Does the login page load quickly when 1,000 users access it?
**Smoke Testing vs Sanity Testing --
Smoke Testing - Checks the major functions of a new software build to make sure it is stable enough for further testing.
Sanity Testing - Checks a specific feature or area after a small change or bug fix to confirm it works correctly.
Retesting: Checking whether a previously failed test case passes after the developer fixes the bug.
Regression Testing: Checking whether existing features still work after new changes or bug fixes.
**Testing Levels :
*Unit Testing - Unit testing checks small pieces of code, usually by developers.
* Integration testing - Integration testing checks pieces working together, such as the app and the payment service.
*System testing- System testing checks the whole application end to end.
* Acceptance testing- Acceptance testing (UAT) confirms it meets business needs, often with real users.
* Black-Box Testing - Testing software functionality without looking at its internal source code. Example: Enter a username and password and check whether login works.
* White-Box Testing- Testing the internal code, logic, conditions and execution paths.Example: Checking whether all branches of a login function execute correctly.
* Exploratory Testing- Exploratory Testing means testing an application freely using your knowledge, experience and creativity to discover unexpected bugs.

* ***Test scenarios vs test cases**
* What is the difference between a test scenario and a test case?- A test scenario describes what needs to be tested at a high level, while a test case provides detailed steps, test data, preconditions, and expected results to verify a specific condition.
* What are the important parts of a test case?- A test case includes a test case ID, title, preconditions, test data, test steps, expected result, actual result, and status.
* Write test cases for a login page.- Valid email and password logs in. Wrong password shows an error. Unregistered email shows an error. Empty fields show validation. Password is masked. Account locks after repeated failures. Forgot-password link works. SQL-like input is rejected safely. Session ends after logout.
* What is Boundary Value Analysis?- Boundary Value Analysis is a test design technique that checks values at and around the boundaries of an input range. For example, if a field accepts values from 1 to 100, we test 0, 1, 100, and 101
* What is a Traceability Matrix?- A Traceability Matrix is a document that maps requirements to test cases. It helps ensure that all requirements are covered by testing.
  ***What is the Bug Life Cycle?***- The Bug Life Cycle means all the steps a bug follows from the time a tester finds it until the bug is fixed and closed. -When a tester finds a problem in software, they report it. The developer fixes it, and the tester checks again. If everything works correctly, the bug is closed.
  **Steps of the Bug Life Cycle- 
  1.New-The tester finds a problem and reports it for the first time.
  2.Assigned- The team leader gives the bug to a developer to fix.
  3.Open / In Progress- The developer starts working on the bug.
  4.Fixed- The developer fixes the problem.
  5.Retest-The tester checks again to see whether the problem is fixed.
  6.Verified-The tester confirms that the bug is fixed and everything works correctly.
  7.Closed-The tester closes the bug because it is working correctly.
  **A strong bug report- Clear title (what, where), environment (browser, device, build), steps to reproduce, expected result, actual result, severity, and evidence such as screenshots, video or console logs. If a developer can reproduce it in one try, you wrote a great report. Example: Bug Title: Wrong total when applying two coupons., Environment: Chrome browser, Windows 11.,Steps: Open the website, add a product, apply two coupons and check the total., Expected Result: The website should show the correct discounted total., Actual Result: The website shows the wrong total., Severity: Medium., Evidence: Screenshot of the wrong total.
  **Severity vs Priority- Severity:How serious is the bug? , Priority: How quickly should the bug be fixed?
  ***Tools every tester uses***
  *What are Testing Tools?- Testing tools are software or applications that help a tester find bugs, check features and make sure software works correctly.
  **Jira-tracking stories and bugs.Jira is used to manage tasks, report bugs and track problems.
  **Browser DevTools – Find Website Problems.console errors, network calls, mobile view.console errors, network calls, mobile view.
  **Postman -for APIs and basic SQL for checking data.Postman is used to test APIs without opening the website.
  **SQL helps testers check whether information is correctly saved in a database.
  ** Tracking and test management- Jira is the most common tool for stories and bugs. Test cases often live in tools like TestRail, Zephyr or Xray, or in simple spreadsheets at smaller companies. Learn to write a clean ticket and filter a list of bugs; that alone covers most daily work.
  **Browser DevTools-Press F12 in Chrome. The Console shows JavaScript errors, the Network tab shows each request with its status code (200 OK, 404 Not Found, 500 Server Error) and response, and the device toolbar lets you test mobile sizes. Attaching a failed network request to a bug report makes developers very happy.
  **API, database and automation-Postman lets you send API requests and check responses without a UI. Basic SQL (SELECT, WHERE, JOIN) lets you confirm data was saved correctly. Selenium and Playwright automate browsers, and Git with a CI tool like GitHub Actions runs tests on every change.
  **What HTTP status codes should a tester know?- 200 OK, 201 Created, 400 Bad Request, 401 Unauthorized (not signed in), 403 Forbidden (no permission), 404 Not Found and 500 Internal Server Error.
  **Why should a tester know SQL?- SQL helps testers check whether information is correctly saved in the database. It also helps find database-related problems.
  **What is a QA Career Path?- QA (Quality Assurance) is a career where you check software to make sure it works correctly and has fewer problems.
  **Different Types of QA Roles- 1. Manual QA Engineer: A Manual QA Engineer tests software manually without writing automation code. Main responsibilities: Check whether features work correctly., Write test cases., Find and report bugs., Retest fixed bugs., Check the website or application.
2. Automation Test Engineer/SDET: An Automation Test Engineer writes code to test software automatically. Main responsibility: Write automation scripts., Run tests automatically., Find bugs using automated tests., Save time by reducing repeated manual work. example:Playwright, Selenium, API tests).
  **What is an SDET(Software Development Engineer in Test)?- An SDET uses programming and software development skills to build testing systems.an engineer who writes code to test software, builds and maintains automation frameworks and often works on test infrastructure and CI pipelines. Main responsibilities: Write test automation code., Build testing frameworks., Test APIs., Work with developers., Maintain automated testing systems.
  **4. Performance Tester
A Performance Tester checks how fast and stable software is.

Example:

Imagine 10,000 people visit a shopping website at the same time.

The tester checks:
- Does the website become slow?
- Does the server crash?
- Can the website handle many users?
Remember: Performance Testing = Check speed and stability.
**5. Security Tester
A Security Tester checks whether software is safe from security problems.

Example:
- Can someone access another user's account?
- Is user information protected?
- Can unauthorized people access private pages?
Remember: Security Testing = Check software safety.
**6. QA Lead / QA Manager
A QA Lead manages the testing team and testing activities.

Main responsibilities:
- Manage QA team members.
- Assign testing tasks.
- Review test reports.
- Communicate with developers.
- Plan testing activities.
Remember: QA Lead = Manage the testing team.
  ****How to Get Your First QA Job**
  1. How Can You Get Your First QA Job?
Getting your first QA job can be difficult when you don't have work experience.

But companies don't always look for experience. They also want to see what you can actually do.

In simple words: You need to show your testing skills, not just certificates.

For example:
- Write test cases.
- Find bugs on a website.
- Create bug reports.
- Learn basic SQL.
- Practice API testing.
- Create a small testing project.
These things can help you get your first QA job.
2. Three Important Things to Get a QA Job
1. Build a Portfolio (Show Your Work)
A portfolio is a collection of your work that shows your skills.

For example, you can choose an online shopping website and test it.

Your project can include:
- 20 test cases.
- 3 bug reports.
- Screenshots of bugs.
- Testing results.
- A small automation script (optional).
You can upload your work to GitHub.

Website: GitHub

Remember: Portfolio = Proof of your skills.
2. Learn Important QA Skills
Before applying for a QA job, learn these important topics.
Skills	What you should learn
Manual Testing	How to test software manually
Test Cases	How to write testing steps
Bug Reporting	How to report software problems
Jira	How to track bugs
SQL	How to check database information
Postman	How to test APIs
Automation	Basic Playwright or Selenium
3. Apply for Jobs
After learning the basics and preparing some practical work, start applying.

You can search for these positions:
- Junior QA Engineer
- Junior Software Tester
- Manual QA Tester
- QA Intern
- Software Test Engineer
- Trainee QA Engineer
Useful job websites:
- BDJobs
- LinkedIn Jobs
- Bdjobs Career
