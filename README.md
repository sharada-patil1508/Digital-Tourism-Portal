The Digital Tourism Port is a Java Swing-based desktop application designed to simplify trip planning by enabling users to book hotels and travel packages seamlessly. The application provides a user-friendly interface where travelers can browse and choose from various tour packages tailored to different destinations and budgets. Users can select hotel options, finalize their bookings, and make payments using multiple modes such as credit/debit cards, UPI, or net banking. All booking and user information is securely stored in a MySQL database, ensuring efficient data management. Additionally, the system includes functionality to delete existing records, such as user bookings or personal details, offering flexibility and control over the data. This project combines the robustness of Java Swing for the frontend with the reliability of MySQL for the backend, making it a comprehensive solution for digital tourism management.


![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/e6cd7cf0073745a370ea9d3c9bc84d99bbf0b5b5/Login%20Page.png)

🔐 Login Page

The Login Page serves as the secure entry point to the Digital Tourism Port application. Designed using Java Swing, it features input fields for:

Username

Password

Along with three key buttons:

✅ Submit – Authenticates user credentials and grants access to the main dashboard

🔄 Reset – Clears the input fields for fresh entry

❌ Close – Exits the application safely

This login mechanism ensures that only authorized users can access the tourism management system, helping maintain security and user-specific access control. All login credentials are validated against records stored in the MySQL backend.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/2fd53bea3e557ca15c870555cef2541d692a8aaa/Loading%20Page.png)

⏳ Loading Page

The Loading Page is the initial screen that appears when the Digital Tourism Port application is launched. Created using Java Swing, this screen simulates a startup animation or progress bar to indicate that the system is loading the necessary resources in the background.


![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/04e224ef3699e65df8bb64ff2cfe193dcf47abd8/Dash%20Board.png)

🖥️ Dashboard Features

The Dashboard provides easy access to all major functionalities of the Digital Tourism Port. Below are the features available:

👤 Add Personal Details – Enter your basic information like name, contact, and address.

✏️ Update Personal Details – Modify your existing personal data.

📋 View Customers – See a list of all registered users.

📦 Check Packages – Browse different travel packages available.

✅ Book Package – Choose and book your preferred package.

🔍 View Booked Packages – Check your existing package bookings.

🏨 Check Hotels – Explore available hotels for your trip.

🛏️ Book Hotel – Make a hotel reservation.

📄 View Booked Hotels – View your hotel booking history.

🌍 Destination – Get details about popular travel destinations.

💳 Payment Gateway – Pay securely using UPI, cards, or net banking.

🗑️ Delete All Details – Option to clear all saved information.

ℹ️ About Us – Learn more about the application.

🔒 Logout – Safely exit the application.


![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/832b5a2c3fc4f791bbe6403e074a380410234238/Personal%20Details.png)

👥 Personal Details Form
The Personal Details section allows users to enter and update their basic information, which is stored securely in the MySQL database. This information is essential for booking and identification purposes.

Fields included:

🧑 Username – Unique login name of the user

🆔 User ID – System-generated unique identifier

🔢 ID Number – A government ID number (e.g., passport or Aadhaar)

📛 Name – Full name of the user

🚻 Gender – Male, Female, or Other

🌍 Country – User’s nationality

🏠 Address – Full residential address

📞 Phone Number – Valid contact number

📧 Email Address – User’s email for communication

This form ensures that all essential details are collected for a smooth travel and booking experience.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/eabf775589df8bee5bcd3965bb3ebec72d4d425a/Update%20Customer%20Page.png)

🛠️ Update Customer Details Page

The Update Customer Details page allows users to modify or correct their previously entered personal information. This ensures that all user records remain accurate and up to date in the system.

Fields available for update:

🧑 Username – Unique login name of the user

🆔 User ID – System-generated unique identifier

🔢 ID Number – Government-issued ID (e.g., Passport or Aadhaar)

📛 Name – Full name of the customer

🚻 Gender – Choose between Male, Female, or Other

🌍 Country – User's nationality or country of residence

🏠 Address – Complete residential address

📞 Phone Number – Mobile or landline contact number

📧 Email Address – Email used for updates and communication

This page helps maintain clean and correct data for all users in the system.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/1a3f3f239910ca363da73f70d5ba1f22a7088752/View%20Customer%20Page.png)

📋 View Customer Details Page

The View Customer Details page displays all saved user information in a structured format. It helps administrators or users to review their data at a glance without making any changes.

Displayed fields:

🧑 Username – Unique login name of the user

🆔 User ID – System-generated unique identifier

🔢 ID Number – Government-issued ID (e.g., Passport or Aadhaar)

📛 Name – Full name of the customer

🚻 Gender – Male, Female, or Other

🌍 Country – Nationality of the user

🏠 Address – Registered residential address

📞 Phone Number – Contact number of the user

📧 Email Address – Registered email for communication

This page ensures easy access to customer information for quick reference or verification.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/7f55aa270d93b42bf899592d80cebe1b9dc2f69f/Package%20Page.png)

🏆 Gold Package – Premium Travel Experience
The Gold Package is designed for travelers who seek comfort, convenience, and a touch of luxury. It includes exclusive features that make your journey truly unforgettable.

✨ Key Features:
✈️ Round-Trip Flights – Includes economy or premium class air travel

🏨 4-Star Hotel Stay – Comfortable accommodation with breakfast included

🍽️ Free Meals – Breakfast and dinner provided daily

🚗 Local Transport – Free airport pickup, drop, and sightseeing cab

🎟️ Guided Tours – Entry tickets to popular attractions and guided tours included

📸 Complimentary Photoshoot – One travel photoshoot session at a scenic location

🌐 Free Travel Insurance – Coverage for the entire trip duration

🎁 Welcome Kit – Includes travel essentials and a souvenir

📱 24/7 Travel Support – Dedicated customer support throughout the journey

This package offers a perfect balance between affordability and luxury, making it ideal for couples, families, and solo travelers who want a hassle-free, memorable vacation.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/98b76bc768567d36c9ef64405d0386514821b063/Book%20Package.png)

📦 Book Package Page

The Book Package page allows users to select and confirm their travel package based on their preferences. The user fills in important booking details which are then stored in the MySQL database.

📝 Fields in the Booking Form:
🧑 Username – Name of the user booking the package

📦 Select Package – Choose from available packages (e.g., Silver, Gold, Platinum)

👥 Total Persons – Number of people included in the booking

🆔 User ID – Unique ID associated with the user

🔢 ID Number – Government-issued ID (e.g., Aadhaar or Passport)

📞 Phone Number – User's contact number for confirmation and updates

💰 Total Price – Auto-calculated based on selected package and number of persons

Once the form is submitted, the selected package is confirmed, and all data is securely saved for further processing like hotel booking and payment.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/fcf0169afdb1d33b3a288ec9a7c6825dc2de19b2/View%20Package.png)

📄 View Booked Package Details Page

The View Booked Package Details page displays the details of travel packages that a user has already booked. This page helps users verify their booking information quickly and accurately.

📋 Displayed Fields:
🧑 Username – Name of the user who booked the package

📦 Package Name – The selected travel package (e.g., Gold, Silver)

🆔 User ID – Unique identifier assigned to the user

🔢 ID Number – Government-issued ID used for booking (e.g., Aadhaar, Passport)

📞 Phone Number – Contact number provided at the time of booking

💰 Total Price – Final price based on selected package and number of persons

This section ensures users can view and verify their package booking details anytime after confirmation.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/ff3dec23b9b89222626ca2a4d040adf69ad34617/Hotel%20Page.png)

Hotel

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/ff89d386ce0e2275f03bd0aa68b4223122110c3a/Book%20Hotel.png)

🏨 Book Hotel Page

The Book Hotel page allows users to reserve hotel rooms as part of their travel plan. The form collects all necessary information to calculate the total cost and confirm the booking.

📋 Fields in the Booking Form:
🏨 Select Hotel – Choose from available hotel options

👥 Total Persons – Number of people staying in the room

📅 Number of Days – Duration of the hotel stay

❄️ AC / Non-AC – Select room type (Air-conditioned or Non-AC)

🍽️ Food – Include food services (Yes/No)

🆔 User ID – Unique identifier of the user

🔢 ID Number – Government-issued ID used for verification

📞 Phone Number – Contact number of the person booking

💰 Total Price – Auto-calculated based on room type, days, food, and number of persons

Once submitted, the booking is saved in the database, and users can view or manage their hotel reservation through the dashboard.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/e2e00094205e1c449698c1a533a8694a2a19e014/Destination%20Page.png)

Destination


![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/969575643d3eb531cafc881680efe5bea2550e22/Payment.png)

💳 Payment Page

The Payment Page allows users to complete their booking by securely paying for packages or hotel reservations through multiple digital payment options.

🧾 Available Payment Options:
💰 General Payment – Manual entry of payment amount and confirmation

📱 PhonePe – UPI-based digital payment through the PhonePe app

🟢 Google Pay – Fast and secure UPI transaction using Google Pay

🧾 Additional Fields:
🧑 User ID / Username – For identifying the user making the payment

🔢 Booking ID or Reference – To link the payment with a specific booking

📞 Phone Number – Contact number used during the transaction

💵 Total Amount – Final payable amount calculated from booking details

After a successful transaction, a confirmation is shown and stored in the database, ensuring traceability and security.

![alt image](https://github.com/sharada-patil1508/Digital-Tourism-Portal/blob/1dcd2eb11407fcf7a9feee57f3c1904f1e5ec3c8/Delete%20All.png)

🗑️ Delete All Details

The Delete All Details feature allows users or administrators to permanently remove all stored information related to a specific user or booking from the system.

🧹 Data That Can Be Deleted:
👤 Personal Details – Username, contact info, ID details

📦 Booked Packages – Package selection, price, and travel data

🏨 Hotel Bookings – Room type, hotel name, number of days

💳 Payment Records – Payment method, amount, transaction info

This option ensures that users have full control over their data. Once deleted, the records are completely removed from the MySQL database and cannot be recovered.
