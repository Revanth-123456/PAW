# PawFinds: A Pet Adoption System | MERN Stack Portfolio with Admin Panel JWT Auth, OTP Verification & Admin Panel
"PawFinds" is a website where you can either give a pet up for adoption or adopt one. If you have a pet you can't care for anymore, you fill out a form. The admin then decides if they can put your pet on PawFinds. If they approve, they'll ask you to bring the pet to an adoption center.It includes includes JWT authentication, OTP verification, user profiles, and an enhanced admin dashboard with data visualization.

If you want to adopt a pet, you fill out a form with your details. The admin gets a lot of requests and picks the best one. If they choose you, they'll delete the other requests and take the pet off PawFinds. They'll keep a record of the pet and your contact info.

So, PawFinds makes it easy to find new homes for pets and connect them with people who want to adopt.


# 🌐 Deployed Version:
[Click to visit the deployed version](https://whimsical-capybara-946a38.netlify.app/auth)


## Introduction
PawFinds is a web application that connects pet lovers with pets in need of a home. Our platform simplifies the process of pet adoption by providing a seamless user experience.

## Features
- Users can submit a pet for adoption by filling out a form.
- Admin reviews adoption submissions and can approve or reject them.
- Approved pets are listed on PawFinds for potential adopters to view.
- Users interested in adopting a pet fill out an application form.
- Admin evaluates adoption applications to select the most suitable adopter.
- Admin maintains a history of adopted pets and their new owners.
- User can browse and search for available pets for adoption.
- They can filter pets based on pet type i.e. dog, cat, fish, etc.
- PawFinds offer detailed pet profiles with photos and descriptions.
- JWT Authentication: Users are securely authenticated with JSON Web Tokens (JWT).
- OTP Verification: Added extra security for users with one-time password (OTP) verification.
- User Profiles: Each user now has a personalized profile where they can manage their information.
- Admin Dashboard: A comprehensive dashboard with graphs showing the number of users registered and a pie chart displaying different types of pets available for adoption.


## Technology Stack
PawFinds is built using the MERN stack (MongoDB, Express.js, React, Node.js).

## **Please Note: This Project Is Designed for Laptop Screens**
Kindly be aware that this project is optimized for laptop screens and is not responsive for mobile or tablet devices. The development of this project was carried out during an internship, and as the internship period has come to an end, further enhancements may not be applied.
Follow these steps to set up the project locally:

## Installation
Follow these steps to set up the project locally:

1. Clone the repository: `git clone https://github.com/Revanth-123456/PAW.git`
2. Install dependencies: `npm install`
3. Create a .env file in the server directory with the following variables:
   - mongooseURL=mongodb+srv://username:password@cluster-url.mongodb.net/?retryWrites=true&w=majority&appName=pawfinds-pet-adoption-system
   - SECRET=your_jwt_secret_key (Any random string of any length)
   - EMAIL_USER=your_email@example.com
   - EMAIL_APP_PASS=your_email_app_password
5. Create a .env file in the client directory with the following variable
   - For localhost deployed backend (REACT_APP_API_URL=http://localhost:4000)
   - Or, if using backend deployment (replace with your actual Render backend URL): (REACT_APP_API_URL=https://your-backend-service)
7. Run the server: `nodemon server` runs the server using nodemon, a tool that enhances the development experience by automatically restarting the server on file changes.
8. `npm start` to start front end.

## Guide for Setting Up an EMAIL_APP_PASS (for emails)
To enable your app to send emails through your Gmail account, you’ll need to generate an App Password. Follow the steps below:

1. Go to the Google Account Security Page:
   - Visit Google Account Security and make sure 2-Step Verification is enabled.
2. Generate an App Password:
    - Scroll down to the "Signing in to Google" section.
    - Click on App Passwords.
    - Select the app (e.g., "Mail") and the device (e.g., "Other") for which you are generating the password.
    - Google will provide a App Password.
4. Use the Generated App Password:
    - Copy the App Password and paste it into the .env file under the EMAIL_APP_PASS field:
    - EMAIL_APP_PASS=your_generated_app_password

### Additional Notes
- Ensure you have Node.js and npm installed on your machine.

## Contributing
We welcome contributions to improve PawFinds! To contribute, follow these steps:
- Fork the repository.
- Create a new branch: git checkout -b feature-new-feature
- Make your changes and commit them: git commit -m 'Add new feature'
- Push to the branch: git push origin feature-new-feature
- Create a pull request explaining your changes.

## Contact Information
For questions, please contact 
- [GitHub](https://github.com/Revanth-123456)
- [LinkedIn](https://www.linkedin.com/in/revanth-v-s-a30907282)

