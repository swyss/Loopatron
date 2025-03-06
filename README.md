# Loopatron

Loopatron is a **cross-platform** desktop application built with **ElectronJS** to manage periodic tasks like cleaning schedules, maintenance reminders, and recurring household chores.

## Features
- **Task Management**: Create and track recurring tasks (e.g., changing bed sheets, taking out trash).
- **Calendar Integration**: Sync tasks with Google Calendar and Outlook.
- **Windows Notifications**: Get popup reminders for upcoming tasks.
- **Data Persistence**: Uses **Redis** for local task storage.
- **Electron Tray App**: Quick access from the system tray.
- **Customizable Intervals**: Daily, weekly, monthly, or custom schedules.

## Roadmap
### Phase 1 (Initial Release)
- Task creation and management
- Calendar synchronization (Google, Outlook)
- Windows toast notifications
- ElectronJS desktop app with Vue 3
- Redis for local task storage

### Phase 2 (Future Enhancements)
- Cross-device synchronization
- Android companion app
- Smart scheduling suggestions

## Tech Stack
- **Main Technology**: ElectronJS
- **Frontend**: Vue 3
- **Backend/Storage**: Redis
- **Platform**: Windows 10/11
- **Notifications**: Windows toast popups
- **Calendar API**: Google Calendar API, Microsoft Graph API

## Setup & Installation
### Prerequisites
- Node.js (>= 16)
- Redis (local instance for task storage)

### Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/loopatron.git
   cd loopatron
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the app in development mode:
   ```sh
   npm run dev
   ```
4. Build for production:
   ```sh
   npm run build
   ```

## Contributing
Contributions are welcome! Please fork the repo and submit a pull request with improvements or bug fixes.

## License
MIT License

