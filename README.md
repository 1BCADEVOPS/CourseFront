1. Project Overview:
   
    This section summarizes the successful completion of the Course Enrollment System full-stack project. The system was designed to provide an efficient and user-friendly      solution for managing courses and student enrollments in a full-stack environment.

3. Development – Frontend:

   The frontend of the Course Enrollment System was successfully developed using React.js. It provides a clean, responsive, and user-friendly interface that allows users to    view available courses, create and edit course details, and enroll students into courses.

Key Frontend Features:

    View list of available courses
    
    Create new courses
    
    Edit existing course details
    
    Enroll students in courses
    
    Dynamic data loading from backend APIs.

3. Development – Backend:

    The backend of the application was successfully developed using Spring Boot. It handles RESTful API requests, implements business logic, and manages database           interactions required for course and enrollment management.
    The backend provides well-structured API endpoints that allow the frontend to perform CRUD operations securely and efficiently.

Example API Endpoints:

    GET /api/courses – Fetch all available courses
    POST /api/courses – Create a new course
    PUT /api/courses/{id} – Update course details
    POST /api/enrollments – Enroll a student in a course    
    
4. Sonar Analysis:
  SonarQube used for static code analysis

Checked for:

Bugs
Code smells
Maintainability
Quality gate verified before proceeding further
<img width="1920" height="1200" alt="Screenshot 2026-02-06 145900" src="https://github.com/user-attachments/assets/27d0d574-0d9d-4fea-8a0c-1c36c52efc4a" />
Issue Description: SonarQube analysis indicates a FAILED status for the frontend module due to code coverage requirements.

Reason: Frontend automated test cases have not yet been implemented, which results in low/zero test coverage and causes the Quality Gate to fail.

Actions Taken: All identified bugs and code smells were reviewed and addressed. Security Hotspots were reviewed and marked as Safe. The remaining failure is only related to test coverage metrics.

Conclusion: The SonarQube failure is limited to coverage constraints and does not reflect issues in code functionality or security. Frontend test cases are planned to be added in a future phase to improve coverage and meet Quality Gate requirements.


Frontend Sonar Analysis:
<img width="1920" height="1200" alt="Screenshot 2026-02-06 150134" src="https://github.com/user-attachments/assets/f0586326-50e0-4005-84fa-ffd4a5d80506" />
Backend Sonar Analysis :
<img width="1920" height="1200" alt="Screenshot 2026-02-06 150159" src="https://github.com/user-attachments/assets/cb0572e6-21fd-4fdf-bd6d-0de51da88786" />

5. Proper Pull Request:
   
  A proper pull request workflow was followed for both frontend and backend repositories.

  Pull requests were successfully created.

  The pull requests were reviewed and merged successfully.

  This demonstrates correct GitHub collaboration and version control practices.

6. Docker Image Creation:
   
  Dockerfile created for backend application

  Backend application containerized using Docker

  Docker image built successfully
<img width="1919" height="1131" alt="Screenshot 2026-02-06 222758" src="https://github.com/user-attachments/assets/9a4e5fec-3c4d-44ba-aa96-c1d4dad2a143" />


7. Deployment:
   
  Backend Deployment (Render)
  
  Docker image deployed to Render
  
  Backend API exposed publicly
  
  API tested using browser / Postman
  
  Backend URL: https://courseback-nsua.onrender.com

8. Frontend Deployment (Vercel):
   
  React frontend deployed using Vercel
  
  Environment variable configured for backend API URL
  
  Build command configured properly

  Build Command:
    npm run build

  Output Directory:
    build successfully
    
  Frontend Build:
<img width="1920" height="1200" alt="Screenshot 2026-02-06 144800" src="https://github.com/user-attachments/assets/20a74235-28a0-45be-9aae-c1abd5b9bfb7" />
  Backend Build:
<img width="1920" height="1200" alt="Screenshot 2026-02-06 144716" src="https://github.com/user-attachments/assets/ce5030a2-b212-4e6a-a22a-18a4fb5b7264" />

9. Custom Domain Configuration:
    
  Free domain obtained using GitHub Student Developer Pack (Namecheap)

  Domain connected to Vercel project

  DNS configured using:

  A Record for root domain
  
  CNAME for www
  
  Custom Domain: https://coursemanagement-hemavathy.me

10. Final Live Links
    
  Frontend (Custom Domain):

  https://coursemanagement-hemavathy.me

  Frontend (Vercel Default):

  https://course-front-8mp8.vercel.app

  Backend API:

  https://courseback-nsua.onrender.com

11. Project Readiness & Demo Preparation:

  Fully prepared to demonstrate the complete working project during the DevOps class.

  Ready to present the project in English, explaining architecture, development, and deployment clearly.

  Successfully used GitHub Student Developer Pack to configure a custom domain and integrate it with Vercel.

  Prepared to explain challenges faced during development, deployment, Dockerization, and domain configuration.
    








    
