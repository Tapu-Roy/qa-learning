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
