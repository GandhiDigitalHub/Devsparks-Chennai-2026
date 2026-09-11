# Hands-on Lab: Building a Modern To-Do Application with IBM Bob

## Lab Overview

In this hands-on lab, you will learn how to use IBM Bob as an AI-powered development assistant to design, generate, troubleshoot, and enhance a modern web-based To-Do application.

Using natural language prompts, you will interact with Bob to create a complete full-stack application consisting of:

- A Python Flask backend
- An HTML, CSS, and JavaScript frontend
- An in-memory database for storing tasks
- A modern and responsive user interface

Throughout the lab, you will explore how Bob can assist with application planning, code generation, debugging, and UI enhancement, significantly accelerating the software development lifecycle.

## Lab Objectives

By the end of this lab, you will be able to:

- Understand the IBM Bob development workflow
- Use Bob's Plan Mode to generate an implementation plan
- Use Bob's Agent Mode to generate application code
- Build a full-stack To-Do application using AI-assisted development
- Resolve common development issues using Bob
- Enhance the application's user experience through conversational prompts
- Run and test a Flask-based web application

## Prerequisites

Before starting the lab, ensure you have the following:

#### Software Requirements
- IBM Bob IDE
- Python 3.x installed

#### Knowledge Requirements

Basic understanding of:
- Python programming
- Web applications
- REST APIs
- HTML, CSS, and JavaScript





## Tech Stack

#### Frontend
- **Framework**: HTML, CSS, JavaScript

#### Backend
- **Language**: Python and Flask


## 1. Open the workspace in Bob IDE

1. Open the IBM Bob IDE

2. Click on **Open Folder**

<img src="images-lab1/img-12.png" >

3. Choose an folder for the workspace

<img src="images-lab1/img-13.png" >

The workspace is opened.

4. Click on **Restricted Mode** to make the workhop is trusted.

<img src="images-lab1/img-14.png" >

5. Click on **Trust** button.

<img src="images-lab1/img-15.png" >

6. Choose the **Plan** mode.

<img src="images-lab1/img-16.png" >


### 2. Start the app development

1. Enter the the below prompt in the chat window to kick start the process.

```
I want to create a simple To-Do application with a Python Flask backend, an HTML/CSS/JavaScript frontend, and an in-memory database for data storage. The user interface should be a modern, responsive, and visually appealing look and feel. 

Please help me with the plan.
```

<img src="images-lab1/img-17.png" >

Bob might ask questions related to **features** that you need in the app. The question might be like `What To-Do features should the app support? Select all that apply.` Also it may provide the list of possibel answers as like below.

2. Choose your answer similar to `Full-featured - All of the above plus task priorities pr due dates`

<img src="images-lab1/img-18.png" >


Bob might ask questions related to **REST API**. The question might be like `How should the frontend communicate with the Flask backend?` Also it may provide the list of possibel answers as like below.

3. Choose your answer similar to `REST API — JavaScript fetch calls to Flask JSON endpoints (no page reloads)`

<img src="images-lab1/img-19.png" >


Bob might ask questions related to **Visuals**. The question might be like `What visual style should the Ul follow?` Also it may provide the list of possibel answers as like below.

4. Choose your answer similar to `Minimal & clean - white/light grey background, subtle shadows, system fonts`

<img src="images-lab1/img-20.png" >


### 3. Approvals

Bob might ask approvals to create files and use tools.

1. Now bob wants to create plan md file. Click on **Approve Once** button.

<img src="images-lab1/img-21.png" >

2. Review the plan and if you are ok with the validation questions, give the prompt like this.

```
OK Proceed
```

<img src="images-lab1/img-22.png" >

3. Bob ask approvals to switch from **Plan** mode to **Agent** for code generation. Click on **Approve Once** button.

<img src="images-lab1/img-23.png" >

4. Bob ask approvals by showing the todo/task list. Click on **Approve Once** button.

<img src="images-lab1/img-24.png" >

5. Keep approving further whenever there is an ask from Bob.

<img src="images-lab1/img-25.png" >

<img src="images-lab1/img-26.png" >

Code generation is completed. You can review all the files.
<img src="images-lab1/img-27.png" >

### 4. Run the application

The steps to run the application is given above. 

1. You can ask bob to give the commands to run the applicaiton in virtual environemnt. Give the prompt like this.

```
To run the app, can you give me the commands to create venvTo run the app, can you give me the commands to create venv
```

<img src="images-lab1/img-28.png" >

Bob generated the commands.

<img src="images-lab1/img-29.png" >

1. Run the commands in the terminal.

<img src="images-lab1/img-30.png" >

<img src="images-lab1/img-31.png" >

<img src="images-lab1/img-32.png" >

3. Open the applicaiton URL http://127.0.0.1:5000 in the browser 

<img src="images-lab1/img-33.png" >

The Add task button is not working.
4. You can give the prompt like this in Bob to solve this problem.
```
Add Task button is not working
```
<img src="images-lab1/img-34.png" >

It is related to CORS issue and issue is fixed by Bob.

<img src="images-lab1/img-35.png" >

Still the Add task button is not working.
5. You can give the prompt like this in Bob to solve this problem.
```
Still it is not working. I am using http://127.0.0.1:5000/
```

<img src="images-lab1/img-36.png" >

It fixed the URL problem in the CORSs.
<img src="images-lab1/img-37.png" >

Enter some data in the app.
<img src="images-lab1/img-38.png" >


5. The screen looks very simple. Wanted to create header, left navigation and all. You can give the prompt like this in Bob to solve this problem.
```
Can you create a home page with header, title, and left navigation menu and all.
```
<img src="images-lab1/img-39.png" >

Bob updated the code.

<img src="images-lab1/img-40.png" >

5. Refresh the browser. The screen looks like this with header and navigation and all.
<img src="images-lab1/img-41.png" >

## Conclusion


