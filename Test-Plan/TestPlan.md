Reddit Manual Testing – Test Plan

1.	Overview
The Reddit Manual Testing Project aims to validate the core functionalities of a Reddit-like web application via manual testing. The modules under test include Authentication, Post Management, Commenting, Voting, Profile Management, and Subreddit Membership. The objective is to identify defects, ensure feature correctness, and validate that the system behaves as expected under normal and edge cases.

2.	Scope
a)	Inclusion
•	Authentication: login, signup
•	Post Management: creating text posts, image posts
•	Commenting: add, edit, and delete comments, upvote/downvote comments
•	Voting: upvote/downvote posts
•	Profile Management: view profile, edit profile
•	Subreddit Membership: join subreddit, leave subreddit

b)	Exclusion
•	Backend performance, stress, or load testing
•	API or integration-level testing beyond UI flows
•	Security testing (e.g. penetration, SQL injection)
•	Mobile / responsive UI testing (unless explicitly included)

3.	Test Environments
•	Browsers: Chrome (latest), Brave (latest), Edge (latest)
•	OS: Windows 10 and 11
•	Network: stable broadband/Ethernet
•	Device: Desktop/laptop
•	Test Data: accounts with valid and invalid credentials, sample posts, comments

4.	Test Strategy
•	Functional Testing: Validate each feature works as intended (e.g. login with valid/invalid credentials, posting, and comment flows).
•	Positive & Negative Testing: Both valid inputs and invalid / boundary cases.
•	Exploratory Testing: Use the app in unanticipated ways to find hidden issues.
•	Reusability / UI Checks: Validate basic UI consistency, alignment, error messages, etc.

5.	Test Deliverables
•	Test Plan Document
•	Test Scenarios & Test Cases
•	Screenshots & evidence

6.	Tools
•	Test case writing / management: Google Sheets / Excel
•	Documentation: Word / Google Docs
•	Screenshots: Snipping Tool

