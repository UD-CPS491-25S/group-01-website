# Flyer Enterprises Scheduler
Welcome to the GitHub page for our capstone project.

## Team Introduction
Our team consists of Adam Tkach, Justin Butler, Philip Chagoyan, Zejian Chen. We are all senior computer science students
at the University of Dayton.

## Sponsor Information
Our sponsor for this project is Flyer Enterprises. It is the fourth largest student-run business in the nation. They are
notable in retail commerce and offer students real-world business experience. Here is the link to their website if you
want to learn more about them: https://www.flyerenterprises.org/

## Project Description
The goal of this project is to automate the process of creating work schedules. Currently, Flyer Enterprises manually
create their work schedules, which takes a lot of time and effort. It also incurs a financial cost for them. This project
will solve this problem and allow Flyer Enterprises to quickly generate work schedules.

## Design Overview
Here is our use case diagram for our system:

![alt text](/images/use-case-diagram.png)

Here is our sequence diagram for our system:

![alt text](/images/sequence-diagram.png)

## Technical Details
Here is our tech stack:
- fronend: JavaScript, HTML, CSS, React
- backend: Python, Flask
- data store: Google Sheets
- APIs: Google Calendar, Google Sheets, OR-Tools, Firebase

## Development Progress
During sprint 1, we got several things done. We set up our tools and technologies that we are going to use, we met with our sponsors to discuss the requirements for the project with them, we selected our tech stack and created a couple of diagrams as shown above, and we started development of the frontend and the backend.

During sprint 2, we got a lot of the code implementation done. For the frontend, we created all of the web pages that we discussed as a team. This includes a home page, a page to view/edit the shifts and the employees, and a page to view/edit and export the generated schedule. For the backend, we integrated all of the APIs listed above. This includes the Google Calendar API for scheduling integration, the Google Sheets API for importing data, and OR-Tools for scheduling optimization.

During sprint 3, we connected the frontend and the backend together. This was done using the Flask framework. Also, we added functionality for adding/removing a shift or an employee. Another feature we worked on was authentication with Firebase so that only authorized people have access to the web app.

## Demos
Here is the link to the demo from sprint 2: https://drive.google.com/file/d/1dzF8VBiCae0dAwoimjt2QOVJ0p3KjdNe/view?usp=sharing
