# Assignment-3
Business Card OCR and Database Integration with Stream lit Project
A user-friendly application to digitize business card data using OCR and manage it in a database.
Table of Contents
Overview
Problem Statement
Prerequisites
Testing the Application Locally
Demo/Presentation Video
Conclusion
Contact
Overview:
This project simplifies the process of extracting and managing information from business cards using optical character recognition (OCR) and a user-friendly Streamlit interface. It empowers users to:

Upload business card images
Extract relevant information using easyOCR
View extracted information in a clear format
Save information to a database (SQLite or MySQL)
Read, update, and delete stored data through the Streamlit UI
Problem Statement:
Develop a Streamlit application that allows users to upload a business card image, extract relevant information using easyOCR, and store it in a database. The extracted details include company name, card holder name, designation, mobile number, email, website, area, city, state, and pin code. Users should be able to manage data through the Streamlit UI, including reading, updating, and deleting entries.

Design User Interface: Use Streamlit to create an intuitive UI. Include widgets like file uploader, buttons, and text boxes for interaction.
Implement Image Processing and OCR: Utilize easyOCR to extract information from uploaded business card images.Apply image processing techniques for quality enhancement.
Display Extracted Information: Present extracted details in an organized manner within the Streamlit GUI. Utilize widgets like tables, text boxes, and labels for effective display.
Implement Database Integration: Use a chosen database management system (SQLite or MySQL). Execute SQL queries for creating tables, inserting data, and managing CRUD operations through the Streamlit UI.
Test the Application: Thoroughly test the application functionality locally using streamlit run app.py.
Continuous Improvement: Enhance the application by adding new features. Optimize code and address bugs. Consider adding user authentication and authorization for security.
Prerequisites:
Before you begin, ensure you have met the following requirements:

Python: Version 3.11.0 or higher. Download Python
Required packages : Static Badge
Database Management System: SQLite or MySQL. SQLite Installation Guide | MySQL Installation Guide
Git: Version control tool. Download Git
Install dependencies: pip install -r requirements.txt
Testing the Application Locally:
To clone and run this application, you'll need Git Badge installed on your computer.

Clone the repository:

  git clone https://github.com/Santhosh-Analytics/BizCardX-Extracting-Business-Card-Data-with-OCR
Navigate to the project directory:

cd BizCardX-Extracting-Business-Card-Data-with-OCR
Install dependencies:

pip install -r requirements.txt
Run the application:

streamlit run BizCard_main.py
Ensure you use your SQL user credentials in the SQL Root Config file.

Conclusion:
In conclusion, this Streamlit application addresses the challenge of efficiently extracting and managing business card information. By leveraging Python, Streamlit, easyOCR, and a chosen database system, it provides a seamless user experience. The project not only showcases adeptness in image processing, OCR, and GUI development but also emphasizes scalability, maintainability, and extensibility. Continuous improvements, such as feature additions and security enhancements, underscore the commitment to delivering a robust and user-friendly solution, making it a valuable asset for those seeking an effective business card data extraction and management tool.
