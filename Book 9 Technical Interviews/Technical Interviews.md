# Technical Interviews

Technical interviews can vary a lot from company to company, so it can be hard to know how to prepare. [Here’s a good rundown of the four main types of technical interview questions.](https://medium.com/@sax1johno/the-four-categories-of-technical-interview-question-and-how-to-ace-them-2c96678cdf79) 

Generally, the technical interview questions our grads have been ask fall into three buckets: <br>	1. Questions about your resume <br>	2. Questions about technical concepts <br>	3. Whiteboard/ coding questions

## Step One: Know Your Resume
At a minimum, you should be able to talk about everything on your resume at at least a high level and give examples of times when you use it. You should prioritize this and practice talking about each bullet point until you’re comfortable with all of them. If there’s a bullet point you’re consistently uncomfortable with, you should talk to your instructors about removing it from your resume. We cannot stress enough the importance of this stuff. **Not being able to explain the stuff on your resume will get you an automatic no from most employers.** 

If someone asks you a general question about NewForce (“What did you learn there?” “What the hell is NewForce?” “Was it a pyramid scheme?”) here are some highlights to hit in your answer to give yourself full credit:<br>	
- NewForce is six months, full time, all day-- like a job 
- We learned front-end web development for the first three months (HTML, CSS, JavaScript, React)<br>	
- We learned server-side development in C#/.NET for the last three months<br>	
- Lots of group projects! We focused on practical application vs. theory. <br>	
-  Mock company environment, sprints, Agile methodology (Tabloid)
-  Remote work-- zoom and slack

Here is the text we’ve asked you to put on your resume under the NewForce description, along with how you might talk about each bullet point if someone asked about it. (**Please don’t copy and paste all this onto your resume-- these are talking points.**)

### Junior Full Stack Software Developer 
NewForce, October 2021 - Present

Intensive full-time 6-month software development immersive training program focusing on full stack (C#/.NET) development fundamentals and problem solving. The final half of the program executed in a simulated company environment with Scrum methodology.

**Applied object-oriented programming fundamentals through team-based projects that reflect real world business problems**
- “We really focused on object oriented programming fundamentals in the second half, when we learned C#/.NET.”
- Project to mention: Trestlebridge Farm
- If you want to knock this question out of the park, go back through a group project and try to find examples of inheritance, encapsulation, polymorphism, and abstraction. Ask for help if you can’t find them. 

**Collaborated remotely on projects using Slack and Zoom**
- Talk about working remotely-- what was hard about it, what you liked about it, what you learned about how to stay productive when working from home

**Managed source code version control with Git/ GitHub**
- “Git is a version control system for tracking changes across your file tree. We used Git and GitHub to manage our source code on all our individual assignments, but it really came into play on group projects. I got really comfortable at branching off, making pull requests, and resolving merge conflicts.”
- Project to mention: think about one where you ran into a problem with Git/GitHub and talk about how you resolved that problem
- If you want to knock this question out of the park, mention how you pulled down other people’s pull requests and tested them thoroughly before giving them your approval. 

**Applied JavaScript, HTML, and CSS fundamentals to build a feature-rich social media dashboard**
- This is in reference to Nutshell
- Talk about your experience on Nutshell with vanilla JS

**Leveraged native ES6 module bundling to build DRY, reusable components**
- Native ES6 module bundling are when we used imports and exports in JavaScript. Under the hood, JavaScript "bundled" all of those files together into one file and sent it to the browser.
- DRY means "do not repeat yourself" -- we worked on writing reusable functions (for example, a function that could print an animal card 100 times rather than 100 functions that would print one single animal card each)
- Reusable basically means the same thing as dry-- we write reusable code so that we don't have to write the same code over and over :) 


**Designed and built single-page kennel management application with React using Hooks**
  - This was Kennel, which you built in class!
  - The main hooks you used were useState() and useEffect(). They're in your flashcards. You should be able to speak, at least on a high level, to what each of those hooks do 


**Designed applications through white boarding dependencies and building ERD’s**
- This basically means sprint planning
- “White boarding dependencies”-- you did this on every group project when you went through the tickets and decided what needed to be done first, i.e. what was dependent on what.
- ERDs are about designing data structures. ERD stands for Entity Relationship Diagram. You built one for your capstone. Typically we gave you one for group projects.


**Built and interacted with databases using SQL and ADO.NET**
- SQL is the synax that we use to build, read, and modify databases. (`SELECT * FROM Customer`, etc). SQL is relevant in pretty much every coding language, not just C#. You learned a particular flavor of SQL called T-SQL (Transact-SQL) that's specific to Microsoft's SQL Server, but generally it's the same across the board
- ADO.NET was the database interface tool we used to run SQL commands from our C# apps and read the data back to the end user. ADO.NET gave us tools like `reader.Read()` and `reader.getInt32()`. Most of the code in your repositories uses ADO.NET. 


**Developed a blog management platform in ASP.NET, MVC, and Razor templates in Visual Studio 2022**
- This was your Tabloid MVC sprint.
- ASP.NET means that it's a web app-- you viewed it in the browser. (This is different from the command line applications we built, which didn't show up in the browser at all--they ran locally on your computer.)
- MVC stands for Model View Controller and refers to the design pattern we used for this app-- Models to represent the data in the database, Views to show the data for the users, and Controllers to act as the "command centers" that determined which views we should show and which data we should send to those views. 


**Created RESTful Web API with C#/ .NET Core and connected it to a React front-end**
- API stands for Application Programming Interface. An API is the middleman between an application and the database. An API intercepts HTTP requests from a client, asks the database for information, and then sends a response (usually JSON) back to the client. 
- Projects to talk about: Full Stack Tabloid or your server-side capstone
- If you want to knock this question out of the park, talk about what [RESTful means ](https://medium.com/extend/what-is-rest-a-simple-explanation-for-beginners-part-1-introduction-b4a072f8740f)


**Built and maintained unit tests for a .NET Web API**
- We do this briefly for APIs
- Unit tests involve testing discrete unit of functionality in your code-- i.e testing each individual method to make sure it works (rather than making sure that an entire feature works, which is called integration testing)
- Generally, this falls under the umbrella of automated testing, which means writing code to test your code (vs. manual testing which means having a human click through your app and test your code). 

## Step Two: Prep for other types of questions
Once you feel comfortable talking about your resume, you should move onto preparing for other types of questions that might show up in a technical interview. 

### Questions about technical concepts
<br>These are questions where an interviewer might ask you to explain a concept in a language you know, or ask about a vocabulary term that may or may not be on your resume.<br>	
- Interviewers usually use these to gauge what you know beyond what’s on your resume<br>	
- If you know the answer, say *everything you know.* Talk their ear off! Be proud! <br>	
- If you don’t, admit that you don’t know it and talk about something that sounds similar, or ask clarifying questions until you can find something similar to talk about. <br>	- Before an interview, google “Junior Developer interview questions [insert tech stack for the job you’re applying for here]”. You can bet that your interviewer is going to do the same thing. <br>	
- [Here is a bank of conceptual questions that grads have been asked.](https://docs.google.com/document/d/1cWyaOhim1_ZcSAoXibMrDUey7_jdDb-dcfgMuOCpsX4/edit) You should know some of them, but not all. When we do mock technical interviews, I’ll pull from this bank of questions and ask you a couple from each category, plus a couple curve 			balls. 

### Coding/ whiteboard questions
These are questions where the interviewer asks you to solve a particular problem either by talking it through, writing code, or writing or pseudo-code<br>	
- Think out loud! Ask a million clarifying questions, make sure you understand the problem. Talk through your process with them and ask for feedback. Make it a conversation. If they can see where you’re going, they can course correct you. The worst thing you can do here is just start writing code-- they want to see how you think.<br>
-  We like [Edabit](https://edabit.com/) to practice because they start out easy and get harder. Most folks are good working their way up to Medium with these. <br>[Codewars](https://www.codewars.com/) and[ LeetCode](https://leetcode.com/problemset/all/) are also a great resource for practicing, although they start out harder.



