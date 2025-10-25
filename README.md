The Royal Spoon Chatbot

Welcome to The Royal Spoon Chatbot, a smart interactive assistant designed for restaurant users to quickly get information, view the menu, and make reservations for tables or events. This project was developed for a hackathon and demonstrates a modern full-stack web-based chatbot experience.

Demo

Try the live demo here: https://theroyal-spoon.netlify.app/

Features

FAQ Assistance

The chatbot answers common FAQs about the restaurant, such as opening hours, menu items, and location.

Welcome Message & Options

When the chatbot opens, it greets the user with a welcome message along with two primary options:

Menu – View the restaurant menu.

Book a Table / Book an Event – Start the reservation process.

Table & Event Reservation

When the user selects Book a Table or Book an Event, the chatbot asks:

Name of the user

Type of event (if booking for an event)

Number of guests

Preferred date and time

Email address

After submission, the chatbot responds with a confirmation message:

🍽️ Your table awaits, [Name]. Reserved for [Number of Guests] on 📅 [Date] at ⏰ [Time]. We look forward to hosting you at The Royal Spoon ✨.


A confirmation email with a reservation card is automatically sent to the provided email using the backend service.

Technology Stack

Frontend:

HTML, CSS, JavaScript, TypeScript

React (for building interactive UI components)

Backend:

Node.js with Express.js (server-side handling)

Nodemailer (for sending reservation confirmation emails)

Deployment:

Frontend hosted on Netlify

Backend can be hosted on any Node.js compatible service (e.g., Render, Vercel, Heroku)

How to Use

Open the chatbot on The Royal Spoon

Interact with the chatbot by typing or clicking options.

Select Menu to view food options.

Select Book a Table or Book an Event to make a reservation.

Provide the required details to receive a confirmation message and email.
