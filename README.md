# <p align="center"> Vem Ser Tech Course - Final Project of Module 1 - Car Dealership </p>

<p align="center">
<img src="images/VemSerTech.jpg"  alt="VemSerTech" height="200px align="left" />
<img src="images/cardealership.jpg"  alt="cardealership" height="200px align="right"/>
</p>

## Vem Ser Tech

Vem Ser Tech was a course offered by a partnership between the companies Ada Tech and iFood. Each student was offered one subject among 4 possibilities: Front-End, Back-End, DevOps and Data. I chose the Back-End technology track, which aimed to study the JavaScript language divided into 6 modules:

Module 1: Programming Logic

Module 2: Object-Oriented Programming

Module 3: Database

Module 4: Node.js with Express (intermediate level)

Module 5: Node.js with Express (advanced level)

Module 6: Automated Testing

The course lasted 324 hours with synchronous classes every Monday, Wednesday and Friday, from 7pm to 10pm, between October 6, 2023 and March 15, 2024. You can find more information about this course here: <a href="https://ada.tech/sou-aluno/programas/ifood-vem-ser-tech">Vem Ser Tech</a>

## Purpose 

This was the first project carried out at the end of the first module. My role in this project was to be a programmer hired by a large chain of car dealerships. The objective of this project was essentially to code a functionality that would send an email every Monday to customers who visited the stores during the last month informing them about the new available vehicles as well as payment conditions. As main skills required for this first project, students were challenged to exercise programming logic and essential features of the JavaScript language such as scope of variables, functions, arrays, and modules.
More about the specified requirements for this project can be read in the document below written by the module professor.

## Requirements

You were hired as a programmer for a large chain of automobile stores (CarStore) and your first challenge is to build the functionality to send an email, every Monday, to customers who visited the stores in the last month, informing tell them about new and best-selling vehicles, as well as the conditions for acquisition (be creative).

     - As there will be no access to a database, an email list (array) must be created, where customer emails will be stored.

     - The email list will store, in addition to each customer's email, a flag with the customer's decision on whether or not to receive marketing communications.

     - A function will be provided in the "envia-email.js" file, which will send a "fake" email to a customer.

Given the global scope of the application, each subtask is required to be developed aiming, in the end, to complete the delivery of the functionality:

     1. Create a function to check the current day of the week, which will be taken into account when sending emails.

     2. Create a function to assemble the body of the email to be sent.

     3. Create a function to send the email to each of the customers on the list, taking into account their decision about receiving marketing communications.

     4. Handle error or success returns from the "sendEmail" function, in order to display a user-friendly message in the console.

---

#### Comments

     - The steps above are a guide, but not mandatory. They can develop a different logic that meets what is requested.

     - You can separate functionalities into files, according to your needs.

     - Use the send-email file as a library that "simulates" the actual sending of an email.
