# Healthcare Dashboard

This is a React-based healthcare dashboard application designed to provide users with a comprehensive overview of health data, anatomical illustrations, and appointment scheduling.

## Project Structure

```
healthcare-dashboard
├── public
│   └── index.html          # Main HTML file for the application
├── src
│   ├── components          # Contains all React components
│   │   ├── Header.tsx      # Header component with logo, search, and user profile
│   │   ├── Sidebar.tsx     # Fixed navigation sidebar with links
│   │   ├── MainContent.tsx  # Main content area for displaying health data and illustrations
│   │   ├── HealthData.tsx  # Component for displaying health status indicators
│   │   ├── AnatomyIllustrations.tsx # Component for anatomical illustrations
│   │   └── AppointmentOverview.tsx  # Component for appointment overview
│   ├── data                # Contains static data for the application
│   │   └── staticHealthData.ts # Mock data for health indicators and appointments
│   ├── styles              # Contains CSS modules for styling components
│   │   ├── Header.module.css
│   │   ├── Sidebar.module.css
│   │   ├── MainContent.module.css
│   │   └── global.css
│   ├── App.tsx             # Root component of the application
│   ├── index.tsx           # Entry point for the React application
├── package.json            # npm configuration file
├── tsconfig.json           # TypeScript configuration file
└── README.md               # Project documentation
```

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd healthcare-dashboard
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Navigate to `http://localhost:3000` to view the application.

## Features

- **Header:** Includes app logo, search functionality, notifications, user profile, and an "Add" button.
- **Sidebar:** Fixed navigation with links to various sections such as Dashboard, History, Calendar, Appointments, Statistics, Tests, Chat, Support, and Settings.
- **Main Content Area:** Displays health data, anatomical illustrations, and an overview of appointments.
- **Static Health Data:** Visual indicators for health status across different anatomical sections.
- **Anatomical Illustrations:** Static illustrations of the human body with health indicators.
- **Appointment Overview:** Calendar view and upcoming appointment schedule.

## Technologies Used

- React
- TypeScript
- CSS Modules
- npm

## License

This project is licensed under the MIT License.