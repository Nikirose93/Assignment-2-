VOCATIONAL TRAINING DEVELOPMENT INSTITUTE
Dynamic Websites & Applications | Module 2 – Assignment 2
Due: November 14, 2026 | Lecturer: Trevoir Williams

GROUP MEMBERS 
1. Name: Nikoi Cole Student ID: 2201010133


FILES
question1.html    JSON.parse() and employee list (10 marks)
question2.html    Billing / shipping / payment validation form (30 marks)
question3.html    DataTables Ajax employee directory (20 marks)
MOCK_DATA.json    Original supplied employee dataset (100 records)
styles.css        Shared layout and styling
README.txt        Setup and submission instructions

HOW TO RUN
1. Keep all files together in this folder.
2. You need an internet connection for the jQuery, jQuery Validate and DataTables libraries (loaded via CDN).
3. Recommended: serve the folder over HTTP for the actual DataTables Ajax request.
   Double-clicking question3.html will also display all 100 employees using its bundled fallback,
   but a local web server is preferred to demonstrate that MOCK_DATA.json loads via Ajax.
   Option A: In VS Code, use the Live Server extension on the project folder.
   Option B: With Python installed, open a terminal in this folder and run:
             python -m http.server 8000
             Then open http://localhost:8000/question1.html
4. Follow the top navigation to each question. Try the form and DataTables search/sort.


QUESTION 2 FUNCTIONAL TESTS
- Click Validate Form on an empty form: custom messages should appear.
- Try an invalid email: a validation message should appear.
- PayPal: card input fields are grey and disabled.
- Visa/MasterCard: card number and expiry become required and editable.
- Uncheck Same as billing: shipping fields show and become required.
- Check Same as billing: shipping fields hide and aren't required.
- On valid submission, see confirmation; this is a demonstration and DOES NOT charge a card.

TECHNICAL NOTES
- jQuery Validate plugin: https://jqueryvalidation.org/
- jQuery DataTables Ajax guide: https://datatables.net/manual/ajax#JSON-data-source
- This example keeps all data client-side and sends no information to a server.
