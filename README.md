# PROJECT 4

- **Project Name:** Bootcamp Buddy - to do list templates for bootcamp students
- **Project By:** Christine Wong
- [**LINK TO GITHUB**](https://github.com/cwon07/project4)
- [**LINK TO DEPLOYED WEBSITE**](https://ga-project-4-frontend.onrender.com)
- **List of Technologies used:** Django, React
- [**LINK TO TRELLO**](https://trello.com/b/oOg79Pqy/project-4)

## Description

This is my take on the popular Notion app for bootcamp students. The app features templates such as interview prep, interview tracker, notes, and journal. 

## Mock UP of UI
 ![Desktop View](https://imgur.com/a/F90pTn4) 


## List of Backend Endpoints
| ENDPOINT | METHOD | PURPOSE |
|----------|--------|---------|
| / | GET | landing page |
| /home | GET | personal home page |
| /journal | POST | add new journal, redirect to /journal
| /journal/new | GET | add one recipe |
| /journal/:id | GET | list one recipe |
| /journal/:id | PUT | form to edit recipe | 
| /journal/:id | DELETE | delete one recipe |
| /journal/:id/edit | GET | edit one recipe |
| /signup | POST | new user sign up page |
| /signup/success | GET | user sign up success, redirect to / |
| /signup/failure | GET | user sign up failure, redirect to /signup |
| /login | GET | login page |
| /login/failure | GET | fail to login, redirect to /login
| /logout | GET | logout page, redirect to / |

## ERD (ENTITY RELATIONSHIP DIAGRAM)

![PICTURE OF ERD](/public/images/ERDv1.png)
