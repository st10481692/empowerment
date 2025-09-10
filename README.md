Empowering the Nation – Training App
Overview
This project is an Android application developed in Kotlin using Android Studio. It was designed for Empowering the Nation, an SME that provides skills training for domestic workers and gardeners. The app helps advertise the business, showcase available training courses, allow customers to select multiple courses, and automatically calculate discounts based on the number of courses chosen. Users can also request a quote directly through the app.
The app is built with a user-centered design process, ensuring simplicity, accessibility, and a professional look that reflects the company’s mission of empowering the community.
Features
Welcome Screen
Displays the business logo and a "Get Started" button to enter the app.
Courses Screen
Lists all available training courses (six-month and six-week programs).
Each course is displayed in a card with course name, description, price, and an "Add Course" button.
Supports selection of multiple courses.
Quote Screen
Shows selected courses, applicable discounts, and total price.
Discounts are calculated as follows:
1 course: No discount
2 courses: 5% discount
3 courses: 10% discount
More than 3 courses: 15% discount
Users can submit a quote request.
Technologies Used
Kotlin for application logic.
XML with ConstraintLayout, CardView, and ScrollView for modern, responsive UI design.
Android Studio for development and testing.
Project Structure
MainActivity.kt – Handles the welcome screen.
CoursesActivity.kt – Displays available courses and allows selection.
QuoteActivity.kt – Shows discounts, total fees, and submits a quote request.
res/layout/
activity_main.xml – Welcome screen layout.
activity_courses.xml – Courses listing layout with CardViews.
activity_quote.xml – Quote display layout.
res/drawable/ – Contains logo and icons.
res/values/ – Colors, themes, and styles for consistent branding.
Installation
Clone the repository or download the source code.
Open the project in Android Studio.
Sync Gradle dependencies.
Run the app on an emulator or physical Android device.
Future Improvements
Implement a bottom navigation bar for seamless movement between screens.
Add user authentication (login/register).
Enable payment gateway integration for course enrollment.
Build a web companion app for the same functionality.
Acknowledgment
This project was developed as part of a milestone assignment to demonstrate the use of user-centered design in mobile application development for an SME.
screenshots of code##
<img width="1105" height="768" alt="Screenshot 2025-09-10 at 16 07 45" src="https://github.com/user-attachments/assets/0dfe1a79-1b20-4bef-8ff6-1df5ce3a189d" />
<img width="863" height="472" alt="Screenshot 2025-09-10 at 16 06 37" src="https://github.com/user-attachments/assets/dc6845ea-d5f4-4a26-ad10-0f943a762a3a" />
<img width="982" height="882" alt="Screenshot 2025-09-10 at 16 07 38" src="https://github.com/user-attachments/assets/25262534-3b76-42c5-aac6-8d632331fff4" />
<img width="931" height="982" alt="Screenshot 2025-09-10 at 16 06 09" src="https://github.com/user-attachments/assets/4a0195fe-cab7-4b20-be00-f527f8db1aff" />
<img width="584" height="427" alt="Screenshot 2025-09-10 at 16 06 50" src="https://github.com/user-attachments/assets/e52d9410-6e3c-4368-b332-cf8e06522d2d" />
<img width="992" height="921" alt="Screenshot 2025-09-10 at 16 06 42" src="https://github.com/user-attachments/assets/d39617d6-8185-4adc-ab94-67e9b8ee712f" />
