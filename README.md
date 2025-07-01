### **ELAGI API Testing Project**
Objective:

**Testing the APIs of the ELAGI website using Postman to ensure functionality, reliability, and security.**

## 1.	Authentication:
	•	User Registration: POST requests to register users and verify emails.
	•	User Login: Authenticate users with credentials.
	•	Password Reset: Handle password reset processes.
	•	User Profile: Retrieve and update user profile details.

## 2.	Categories:
	•	Retrieve product listings by category and sort by price.
	•	Request rare medicines and manage the user’s Wishlist.

## 3.	Purchase:
	•	Add, update, and remove items in the cart.
	•	Proceed with checkout and retrieve order history.

## 4.	Homepage Interactions:
	•	Retrieve and submit feedback.
	•	Handle “Contact Us” form submissions.
 
## **Tools and Techniques**

	•	Postman: Dynamic variable management, collection runner, and API documentation exploration.
	•	Dynamic Variables: Used for handling authentication tokens and email automation.
	•	Exporting: Documenting and exporting collections and environment variables.
 
## **Key Endpoints**
	•	Authentication: /register, /login, /password-reset
	•	Categories: /medicines, /categories
	•	Cart and Checkout: /cart, /checkout
	•	Feedback: /user/profile/feedback, /homepage/contact-us.
 
## **Results**

	•	Successfully tested all endpoints with automated validation.
	•	Documented the API functionality for further development.