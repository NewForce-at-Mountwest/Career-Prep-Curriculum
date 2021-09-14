# Technical Interviews

Technical interviews can vary a lot from company to company, so it can be hard to know how to prepare. [Here’s a good rundown of the four main types of technical interview questions.](https://medium.com/@sax1johno/the-four-categories-of-technical-interview-question-and-how-to-ace-them-2c96678cdf79) 

Generally, the technical interview questions our grads have been ask fall into three buckets: <br>	1. Questions about your resume <br>	2. Questions about technical concepts <br>	3. Whiteboard/ coding questions

**Step One: Know your resume backward and forward**<br>At a bare minimum, you should be able to talk about everything on your resume in detail, and give examples of times when you use it. You should prioritize this and practice talking about each bullet point until you’re comfortable with all of them. If there’s a bullet point you’re consistently uncomfortable with, you should talk to your instructors about removing it from your resume. We cannot stress enough the importance of this stuff. **Not being able to explain the stuff on your resume will get you an automatic no from most employers.** 

If someone asks you a general question about NewForce (“What did you learn there?” “What the hell is NewForce?” “Was it a pyramid scheme?”) here are some highlights to hit in your answer to give yourself full credit:<br>	- NewForce is six months, full time, all day-- like a job <br>	- We learned front-end web development for the first three months (HTML, CSS, JavaScript, React)<br>	- We learned server-side development in C#/.NET for the last three months<br>	- Lots of group projects! We focused on practical application vs. theory. <br>	- Mock company environment, sprints, Agile methodology (Bangazon)<br>	- Remote work-- zoom and slack

Here is the text we’ve asked you to put on your resume under the NewForce description, along with how you might talk about each bullet point if someone asked about it. (**Please don’t copy and paste all this onto your resume-- these are talking points.**)

**Junior Full Stack Software Developer*** NewForce, Jan. 2021 - Present*

Intensive full-time 6-month software development immersive training program focusing on full stack (C#/.NET) development fundamentals and problem solving. The final half of the program executed in a simulated company environment with Scrum methodology. 

- Applied object-oriented programming fundamentals through team-based projects that reflect real world business problems
  - “We really focused on object oriented programming fundamentals in the second half, when we learned C#/.NET.”
  - Project to mention: Trestlebridge Farm
  - If you want to knock this question out of the park, go back through Trestlebridge farm and try to find examples of inheritance, encapsulation, polymorphism, and abstraction. Ask for help if you can’t find them. 
- Managed source code version control with Git/ GitHub
  - “Git is a version control system for tracking changes across your file tree. We used Git and GitHub to manage our source code on all our individual assignments, but it really came into play on group projects. I got really comfortable at branching off, making pull requests, and resolving merge conflicts.
  - ”Project to mention: think about one where you ran into a problem with Git/GitHub and talk about how you resolved that problem
  - If you want to knock this question out of the park, mention how you pulled down other people’s pull requests and tested them thoroughly before giving them your approval. 
- Applied JavaScript fundamentals leveraging DRY, modular, readable code and reusable components
  - *DRY* means “do not repeat yourself”-- you worked writing reusable functions
  - *Modular* refers to how we had files that served a specific purpose-- a file to print to the DOM, a file for fetch calls, etc
  - *Readable* just means we talked about the importance of writing code for other developers, not just ourselves-- clear variable names, comments, etc
  - *Reusable components* mainly refers to React! Remember how we built the AnimalCard component that could be used in multiple places in the app?
  - Project to mention: Nutshell
  - If you want to knock this question out of the park, talk about *why* “dry, modular, readable” code is important (i.e. because you want to write code that the rest of your team can read and build off of)
- Built single-page applications with HTML, CSS, and React
  - Projects to mention: Nutshell or your capstone 
- Styled applications with CSS Frameworks Bootstrap, Bulma, and Materialize and wrote custom styles
  - CSS frameworks do a lot of the work for you-- you just install them via CDN or download them and then use their class system. And boom! Nice looking website right out of the box. This should only be on your resume if you used them. And you should just mention a project when you used them. 
- Designed applications through white boarding dependencies and building ERD’s
  - This basically means sprint planning
  - “White boarding dependencies”-- you did this on every group project when you went through the tickets and decided what needed to be done first, i.e. what was dependent on what. Remember in Trestlebridge Farm when you had to figure out as a group that you had to build the functionality to add duck houses before you could build the functionality to purchase ducks? That’s an example of a dependency-- ducks are dependent on duck houses. 
  - ERDs are about designing data structures. ERD stands for Entity Relationship Diagram. If you built an ERD for your capstone, talk about that and what challenges you ran into. 
- Developed a HR tracking app and an e-commerce platform using ASP.NET, MVC, and Razor templates in Visual Studio 2019
  - Razor is our templating syntax in ASP.NET. It allows us to build web pages with C#/.NET.
  - MVC stands for model, view, controller. Here’s the super cliff notes version:
    - Models represent the tables in the database
    - Controllers contain the main application logic
    - Views represent what the end user will seeIf you want to knock this question out of the park, google the pros and cons of MVC as a design pattern
- Built and interacted with databases using SQL, ADO.NET and Entity Framework with migrations
  - Projects to talk about: Bangazon API
  - ADO.NET allows us to interact with the database in C#/.NET using SQL
  - SQL queries the database directly
  - If you want to knock this question out of the park, talk about *why* we chose ADO.NET-- because it’s very performant (fast), because it does no magic for (so we have very fine grained control), and because we wanted to practice writing SQL 
- Created a C#/.NETCore RESTful API to track resources at an e-commerce company
  - API stands for Application Programming Interface. An API is the middleman between an application and the database. An API intercepts HTTP requests from a client, asks the database for information, and then sends a response back to the client. 
  - Projects to talk about: Bangazon API
  - If you want to knock this question out of the park, [talk about what RESTful means ](https://medium.com/extend/what-is-rest-a-simple-explanation-for-beginners-part-1-introduction-b4a072f8740f)
- Built and maintained integration tests for APIs in ASP.NET Core
  - Project to talk about: Bangazon API
  - You wrote integration tests to test the endpoints of your API. Your tests basically imitated a human user-- they made HTTP requests to your API (for example, the test for getting a list of customers sent a GET request to your API url) and then checked to make sure you got the right data back. 
  - If you want to knock this question out of the park, talk about *why* it’s worth the time to build integration tests-- to make our code more maintainable, and to make it easier for other developers to tell when they may have accidentally introduced a breaking change to the code base. 

**Step Two: Prep for other types of questions**<br>Once you feel comfortable talking about your resume, you should move onto preparing for other types of questions that might show up in a technical interview. 

**Questions about technical concepts**<br>These are questions where an interviewer might ask you to explain a concept in a language you know, or ask about a vocabulary term that may or may not be on your resume.<br>	- Interviewers usually use these to gauge what you know beyond what’s on your resume<br>	- If you know the answer, say *everything you know.* Talk their ear off! Be proud! <br>	- If you don’t, admit that you don’t know it and talk about something that sounds similar, or ask clarifying questions until you can find something similar to talk about. <br>	- Before an interview, google “Junior Developer interview questions [insert tech stack for the job you’re applying for here]”. You can bet that your interviewer is going to do the same thing. <br>	- [Here is a bank of conceptual questions that grads have been asked.](https://docs.google.com/document/d/1cWyaOhim1_ZcSAoXibMrDUey7_jdDb-dcfgMuOCpsX4/edit) You should know some of them, but not all. When we do mock technical interviews, I’ll pull from this bank of questions and ask you a couple from each category, plus a couple curve 			balls. 

**Coding/ whiteboard questions**<br>	- These are questions where the interviewer asks you to solve a particular problem either by talking it through, writing code, or writing or pseudo-code<br>	- Think out loud! Ask a million clarifying questions, make sure you understand the problem. Talk through your process with them and ask for feedback. Make it a conversation. If they can see where you’re going, they can course correct you. The worst thing you can do here is just start writing code-- they want to see how you think.<br>- We like [Edabit](https://edabit.com/) to practice because they start out easy and get harder. Most folks are good working their way up to Medium with these. <br>[Codewars](https://www.codewars.com/) and[ LeetCode](https://leetcode.com/problemset/all/) are also a great resource for practicing, although they start out harder.



