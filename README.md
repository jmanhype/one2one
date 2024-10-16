# One2One AI

One2One AI is an innovative project that combines a React-based frontend with a Python backend to create an interactive AI-driven experience.

## Project Structure

The project is organized into two main directories:
- `voice`: Contains the frontend React application
- `metahuman-stream`: Contains the backend Python server

## Getting Started

To get started with One2One AI, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/DagimN/one2one.git
   cd one2one
   ```

2. Set up the frontend:
   ```
   cd voice
   npm install
   ```

3. Set up the backend:
   ```
   cd ../metahuman-stream
   pip install -r requirements.txt
   ```

4. Start the frontend development server:
   ```
   cd ../voice
   npm run dev
   ```

5. Start the backend server:
   ```
   cd ../metahuman-stream
   python app.py
   ```

Note: Ensure you have both Node.js and Python installed on your system before starting.

## Frontend (voice)

The frontend is a React application built with Vite. It uses TypeScript and includes various dependencies for UI components, routing, and API interactions.

Key dependencies include:
- React
- React Router
- Axios
- Formik
- React Player
- Video.js

For a full list of dependencies and development tools, refer to the `package.json` file in the `voice` directory.

## Backend (metahuman-stream)

The backend is a Python server, with `app.py` as the main entry point. It handles the server-side logic and AI interactions.

## Development

For frontend development, you can use the following npm scripts:
- `npm run dev`: Start the development server
- `npm run build`: Build the production-ready application
- `npm run lint`: Run ESLint for code quality checks

For backend development, ensure you have all the required Python packages installed and run the `app.py` file.

## Contributing

Contributions to One2One AI are welcome. Please ensure you follow the existing code style and structure when submitting pull requests.

## License

[Include license information here]

## Contact

For any queries or support, please contact:
Straughter Guthrie - [GitHub Profile](https://github.com/jmanhype)
