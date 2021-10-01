# Proposal for HAND-IN HAND-OUT
## Statement Of Purpose:
- Every university tend to hand out books to students based on their respective courses and intrests. If in case of books shortage or damaged books or other reasons the university tend to ask students to buy textbooks from other sources. After the year is done most of these books are either sold on other websites or students tend to recycle them. We intend to create an application to allow students to sell these books to the university on a certain percentage of the actual price so these books can be again issued by the university for new students.

 ## Overview:
 - We would like to develop an application that allows students to search for books they want to buy, rent, or check out, as well as sell them to the university. They will be given an appointment at their university library after filling out a form, where they can bring their book and sell it, which the admin will accept or reject depending on the book's availability.
 - Students can rent for books on certain price per day and for certain days based on the book that they select.
 - By this application even university can get benifits such as, students sell their books which may be advanced editions and with low price which is saving time and money.
 
 ## Benefits:
- This application would make it easy for students to check the availability of books that they would wish to check out or rent.
- Students can easily sell their books to the university.
- University can easily get more books, sometimes advanced editions from the students without spending more time to buy.

## Epics / User Stories / Tasks:

- As a user, i want register and then login to the application to view different ty[es of books available.
    - develop UI pages for both login and register
    - create tables based on the components in it
    - create rest APIs for both of them
- As a user, i want to be able to make an appointment to sell my book to the library.
- As an admin,I must be able to manage appointments which may be accepted or rejected based on the books availbility.
 
## Acceptance criteria checklist:
- User must be authorized in order to login to the Application
- This application must be easily understandable and easily accessable to students.
- while accepting to appointments students must provide valid information about books.

## Contract scope / budget / schedule (2 semesters):


## Schedule:

- **Sprint-1** (Start Date: 11th October 2021 - 25th October 2021)
   - In the intial sprint we work with plan and all the basic reqirements gathering. 

- **Sprint-2** (Start Date: 25th October 2021 - 8th November 2021)
   - Enhancing and modifing the requirements and break them into functional requirements.

- **Sprint-3** (Start Date: 8th November 2021 - 22nd November 2021)
   - Building mockups and basic UI pages using Angular.


 End of semester GDP-1

 GDP-2 
 
 - **Sprint-4**  (Start Date: 12th January 2022 - 26th January 2022)
    - Create Database models and schema

 - **Sprint-5** (Start Date: 26th January 2022 - 9th february 2022)
    - Working with login and Authentication pages.Design web APIs

 - **Sprint-6** (Start Date: 9th February 2022 - 23rd February 2022)
    - Create APIs to fetch data from DB

 - **Sprint-7** (Start Date: 23rd February 2022 - 9th March 2022)
    - Design all the UI pages based on requirements

 - **Sprint-8** (Start Date: 9th March 2022 - 23rd March 2022)
    - Integration with both UI and backend.

 - **Sprint-9** (Start Date: 23rd march 2022 - 6th April 2022)
    - Testing and fixing issues

 - **Sprint-10** (Start Date: 6th April 2022 - 20th April 2022)
    - Deployment of the application.
 

## User interface sketches:
![](Images/LoginPage.png "loginpage")
![](Images/Register.png "RegisterPage ")
![](Images/submitimage.jpg "hand in hand out")
![](Images/Rentbooks.jpg "rent book page")
![](Images/sellbooks.jpg "sell book page")

## Technology stack descriptions:


### Backend language + framework 
- The backend language and framework we are using for our project would be **JAVA / Spring**
- It is a fully optimized frame work which helps to maintain and modify requirements.

### Backend free app host 
- The Backend app host for our project would be **HEROKU**
### Data host 
- The data host we are planning to use is **PostgreSQL**
### Front-end page plan 
- The front end page we have planned for our project is Build with **Angular**
- which is used to build single page applications which maintains the same view while navigating to other pages.  
### Front-end responsive design 
- The Front-end responsive design would be **Bootstrap**


## E-R diagram displayed and described:
![](ERDiagram.png "ERDiagram")

## Consistent set of sample data in Excel, use one sheet for each entity:
![](Images/Registersheet.png " Register records")
![](Images/BookReturns.png "book return records ")
![](Images/Books.png " books records")
![](Images/RentRecords.png "rent records ")
![](Images/Appointment.png " appointemnt records")
## Risks and assumptions:
### Risks
- Univeristy may not have all the books that are required for students.
- Books may not be returned back from students on time.
- Students may return damaged books to the library.
### Assumptions
- Students can easily access all the information about books.
- Students have the option to sell there books to library.
- Students can borrow books from library.
- Opportunity to improve end-user experience.





