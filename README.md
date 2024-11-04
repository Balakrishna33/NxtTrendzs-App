#Nxt Trendz E-commerrce App
Keywords: React, E-commerce Functionality

Developed the frontend part of the Nxt Trendz online shopping application, which is similar to Amazon.
This application allows users to log in, search, sort, filter, select products, and add them to the shopping cart
Concepts such as authentication, state management, context, page navigation, media queries and flexbox concepts in the code by following the clean code guidelines.
###Technical Aspects
Keywords: Authentication, Validation, Cookies

Implemented a basic authentication flow and handled common errors such as invalid username and invalid password.
Used cookies to persist user credentials across page reloads.
###State Management and Navigation:
Keywords: State management, Navigation, Protected Route Used

Context for state management for creating a global state to manage cart state across routes.Used React Router for navigation within the application.
Additionally, implemented protected routes to control access based on user roles.`
###API Integration:
Keywords: API Integration

####Integrated mock APIs for displaying data
Clean Code Guidelines:
Keywords: Clean code guidelines

Followed clean code guidelines by maintaining a consistent folder structure and used meaningful naming conventions, such as prefixing event handlers with on and creating reusable components throughout the application.
####Responsiveness:
Keywords: Responsiveness,

####Flexbox To ensure a responsive design, used media queries and flexbox for layouting.
Design Files
Click to view
Refer to the video below:
Video
Set Up Instructions
Click to view
Functionalities
When an unauthenticated user tries to access the Cart Route, then the page navigates to Login Route

Following are the features implemented

Feature 1

When an authenticated user tries to add the same product multiple times
The quantity of the product updates accordingly, and the count of the cart items in the header remaines same.
Feature 2

The total amount and number of items in the cart are displayed in the Cart Route
Feature 3

In each cart item in the cart
When the plus icon is clicked, then the quantity of the product is incremented by one
When the minus icon is clicked, then the quantity of the product is decremented by one
When the quantity of the product is one and the minus icon is clicked, then the respective product is removed from the cart
Based on the quantity of the product, the product price and the Cart Summary, i.e the total cost is updated accordingly
Feature 4

When an authenticated user clicks on the remove button, cart item is removed from the cart list
Feature 5

When an authenticated user clicks on the Remove All button, all the cart items are removed from the cart and Empty Cart View is displayed
Feature 6

When the user clicks on checkout button the payment popup opens and lets the user to input payment details/methods and ables to place order successfully.
The goal of this enhancement project is to understand the existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> code, and add the given functionalities within the existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> code.

Your existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> app, which you have developed, allows users to log in, search for your products, sort, filter, and add products to the cart.

### Enhancement Functionality

<details>
<summary>Functionalities to be added</summary>

- Add a `Payment Popup` feature to the application. A Popup should be displayed when a user clicks the `Checkout` button from the cart page.
  - The Popup should include fields for the user to select one of the payment methods like Card, Net Banking, UPI, Wallet, and Cash on Delivery. Ensure all the options, except for Cash on Delivery, are disabled.
  - The Popup should also include a summary, which displays the number of items and the total price the user will pay.
  - The Popup should also have a `Confirm Order` button. If the `Cash on Delivery` payment option is not selected, the `Confirm Order` button must be disabled.
  - Clicking this button will display a success message stating **"Your order has been placed successfully"**.
- Ensure your application maintains good CSS styling.

<MultiLineNote>
- For Popup Component, use <a href="https://react-popup.elazizi.com/component-api" target="_blank_">React Popup</a>
- Use modal prop in Popup Component 
</MultiLineNote>

</details>

### Setup Instructions

<details>
<summary>Follow these steps before starting to code for this project. (**Important**)</summary>

- After setting up this project delete the `README.md` file in the CCBP IDE.
- Clone the existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> code from your GitHub account to add new functionalities to it.
  - If the existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> code is not available in your git, push your code to git.
    - <a href="https://learning.ccbp.in/3da6f1a6-0892/course?c_id=ade6e642-cd5c-4896-9edd-3f06d3dc2069&s_id=49896a46-f484-4b42-b459-2626f77e6796&t_id=9f27b553-4bbe-400f-9025-9044f79acda0" target="_blank_">Click here to learn how to push your code to git</a>
  - Once the code is pushed to git, clone it into this project using the below command.

```cmd
git clone {git repository URL} /home/workspace/reactjs/coding-practices/enhancementOfNxtTrendzPayment
```

<MultiLineNote>
In the above command, replace this `{git repository URL}` with your actual Git URL.
</MultiLineNote>
- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

<MultiLineNote>

- Cloning the existing <a href="https://learning.ccbp.in/question/d595dd02-c5d0-4330-bd3d-ac0275b02d8a" target="_blank_">Nxt Trendz</a> repo is mandatory, as test cases are added for both the existing NxtTrendz App and the new functionality.
- These projects are introduced to help you prepare well for similar questions asked during interviews. </MultiLineNote>

### Submission Form:

<center>Click the below button and submit your git URL and published URL of the current project</center>
<br>
<a href="https://forms.ccbp.in/nxt-tendz-enhancement-project-submission-form" target="_blank_">
  <center><button style="color: #fff; border: none; cursor: pointer; width: 218px; height: 34px; background-color: rgb(22, 101, 216); border-radius: 5.4px; box-shadow: rgb(0 0 0 / 36%) 0px 2px 4px 0px;font-family: Inter;font-size: 14px;color: rgb(255, 255, 255);font-weight: 500;letter-spacing: 0.5px;text-transform: uppercase;">
    SUBMIT
  </button>
  </center>
</a>

<br/>
<center>**Follow the clean code guidelines**</center>
