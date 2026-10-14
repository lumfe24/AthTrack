# AthTrack

1. Main Goal

Learn how to develop a web application from scratch.

**AthTrack — Athletics Reservation System**

A web application that allows users to check track availability, reserve a time slot, and view the weather forecast to decide whether it is worth training on a given day.

## 2. Lessons

1. **Frontend — what the user sees**  
   HTML · CSS · JavaScript  
   Login screens, calendar, reservation forms, buttons, error messages, and confirmation notifications.

2. **Backend — the application's logic**  
   C# · ASP.NET Core  
   Check whether a track is available, validate schedules, manage users, and prevent duplicate reservations.

3. **Database**  
   SQL · SQLite  
   Store users and reservations so that information is not lost when the application is closed.

4. **API and JSON**  
   HTTP · REST · JSON  
   Allow the frontend to communicate with the backend and exchange structured information.

5. **External Services**  
   Weather API  
   Retrieve weather forecasts for training days and display them within the application.

6. **Development Tools**  
   Git · GitHub · Docker · Swagger  
   Manage version control, test APIs, configure the development environment, and learn how to run the application outside the development environment.

## 3. Features (v1.0)

1. **User Registration and Login**  
   Create an account, sign in, and sign out. Each user will only be able to manage their own reservations.

2. **Reserve a Track**  
   Choose a date and time, check available time slots, and confirm a reservation. Occupied slots cannot be booked.

3. **Check the Weather**  
   Display temperature, probability of precipitation, and forecast for the selected date whenever the weather API provides this information.

4. **My Reservations**  
   View upcoming reservations and cancel your own reservations.

5. **Activity History**  
   View past reservations. This will help us practice SQL queries and display data retrieved from the server.

## 4. Connections

**AthTrack General Architecture.png**

## 5. Development Roadmap

1. **Stage 1. Design Before Coding**  
   Define the screens, features, required data, and reservation workflow. Learn how to translate an idea into requirements.

2. **Stage 2. Build the User Interface**  
   Create a first version using HTML, CSS, and JavaScript. Learn how to organize folders and separate structure, styling, and behavior.

3. **Stage 3. Build the Backend**  
   Create an ASP.NET Core project, develop endpoints, and test them with Swagger. Understand what requests, responses, HTTP status codes, and REST APIs are.

4. **Stage 4. Connect the Database**  
   Create tables, define relationships, perform queries, and persist users and reservations.

5. **Stage 5. Integrate Frontend and Backend**  
   Send data through HTTP, process JSON, and display real responses in the user interface.

6. **Stage 6. Add User Accounts**  
   Implement secure authentication and verify user permissions.

7. **Stage 7. Integrate Weather Forecasts**  
   Connect to an external API, interpret JSON responses, and handle errors or missing data.

8. **Stage 8. Test and Prepare the Application**  
   Validate edge cases, handle errors, use Git, and finally learn how to containerize the services with Docker if appropriate.
