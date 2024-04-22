This project is the front end component of a full stack application designed to manage student records. The front end is developed using Angular, providing a user-friendly and intuitive student website interface that interacts with the backend API to perform CRUD operations on student records. 



## Features

- Full CRUD functionality for managing student records.
- Clean and organized dashboard interface for administrators.
- Create new student records with all relevant information fields.
- View a list of all students with options to edit or delete each record.
- Display student details in an editable form for updating.
- Ensure administrators have access to all fields when creating or editing student records.



## Technologies Used

- Angular 17 
- TypeScript
- HTML/CSS
- Bootstrap or Material Design for UI components
- RESTful API integration with backend (Java, Spring Boot, Spring Data JPA)



## Getting Started

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Configure the API base URL in the environment file (`src/environments/environment.ts`) to point to your backend API (e.g., `apiBaseUrl: 'http://localhost:8080/api'`).
5. Run the development server using `ng serve` or `npm start`.
6. Open your browser and navigate to `http://localhost:4200` to view the application.



<img src="./images/StudentRecordsPreview.png" alt="Student Records Manager Preview">



## Project Structure

The project structure follows Angular's recommended architecture:

- `src/app/components`: Contains reusable UI components.
- `src/app/services`: Includes services for API communication.
- `src/app/models`: Defines TypeScript models for data structures.
- `src/app/pages`: Defines components/pages for different views (e.g., student list, student details, etc.).
- `src/assets`: Stores static assets such as images, stylesheets, etc.



### Links
* User Stories - https://docs.google.com/document/d/14Uo-IgHvJab1L4-r9mHf7T20wOMQ834O4_MWG7Bykiw/edit?usp=sharing 

* HTTP requests/endpoints spreadsheet - https://docs.google.com/spreadsheets/d/18kHZpWV__r9cRTKkT8xmkjtEG8_sPdnL_pWVzjmNHp8/edit?usp=sharing 



## Author

:woman_technologist: Erica Ayala

- [LinkedIn](https://www.linkedin.com/in/ayalavirtual)
- [GitHub](https://www.github.com/AyalaVirtual) 



