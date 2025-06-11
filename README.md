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
