# Coding Quiz

Coding Quiz is a web application designed to test your knowledge of various programming concepts through a series of random quiz questions. Built using the MERN stack, the app leverages modern web technologies for an engaging and interactive user experience.

## Features
- Dynamic quiz generation with random questions.
- A scoring system that displays your results at the end of the quiz.
- The ability to restart the quiz after completion.
- Fully tested using Cypress for robust and reliable functionality.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd quiz-test-app
   ```

3. Install dependencies:
   ```bash
   npm run install
   ```

4. Configure environment variables:
   - Rename the `.env.example` file to `.env` and update the variables as needed.

## Usage

To start the application, use the following commands:

1. Run the app in development mode:
   ```bash
   npm run start:dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

3. To build the application for production:
   ```bash
   npm run start
   ```

## Testing

The app is tested using **Cypress** to ensure reliability and robust functionality.

### Run Cypress Tests
1. Open Cypress in interactive mode:
   ```bash
   npm run cypress
   ```

2. Run all tests in headless mode:
   ```bash
   npm test
   ```

### Test Structure
- **Component Tests**: Located in `cypress/component/`, these tests validate the functionality of individual components.
- **End-to-End Tests**: Located in `cypress/e2e/`, these tests simulate user interactions across the app.

## Tech Stack
- **Frontend**: React with Vite for modern build tooling.
- **Backend**: Node.js and Express.js.
- **Database**: MongoDB for data persistence.
- **Testing**: Cypress for component and end-to-end testing.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the ISC License. See the `LICENSE` file for details.