# Survey Project

This project is a full-stack web application developed using Laravel, React, and Tailwind CSS. It provides a platform for creating and conducting surveys, allowing users to design custom surveys, distribute them, and collect responses. The application leverages the power of Laravel for backend logic, React for dynamic frontend interactions, and Tailwind CSS for styling.

## Features

- **Survey Creation:** Users can create custom surveys by adding questions with various types of input fields such as multiple choice, text, checkbox, etc.
- **Survey Distribution:** Surveys can be shared via unique URLs or embedded in other websites.
- **Response Collection:** Responses to surveys are collected and stored securely in the database.
- **User Authentication:** Secure user authentication system is implemented to ensure that only authorized users can create surveys and view responses.
- **Dashboard:** Users have access to a dashboard where they can manage their surveys, view response analytics, and export response data.
- **Responsive Design:** The application is designed to be responsive and work seamlessly across different devices and screen sizes.

## Technologies Used

- **Laravel:** Laravel is used for the backend logic of the application, handling routes, controllers, models, database migrations, and authentication.
- **React:** React is utilized for building the dynamic and interactive frontend components of the application, providing a smooth user experience.
- **Tailwind CSS:** Tailwind CSS is used for styling the user interface, enabling rapid development and easy customization of UI components.
- **MySQL:** MySQL database is used for storing survey data, user information, and response records.

## Setup Instructions

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install PHP dependencies by running `composer install`.
4. Install Node.js dependencies by running `npm install` or `yarn install`.
5. Copy the `.env.example` file to `.env` and configure your database connection settings.
6. Generate an application key by running `php artisan key:generate`.
7. Run migrations to create the necessary database tables: `php artisan migrate`.
8. Start the Laravel development server: `php artisan serve`.
9. In another terminal, navigate to the `resources/client` directory.
10. Start the React development server: `npm start` or `yarn start`.
11. Access the application in your web browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes. Make sure to follow the project's coding standards and guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, feel free to contact the project maintainer:

Bazirakye Tonny  
bazirakyetonny15@gmail.com  

