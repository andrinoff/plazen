# Plazen

<p align="center">
  <img src = "src/app/favicon.ico" height=100 width=100>
</p>

<h2 align="center">Let your schedule build itself.</h2>

Plazen is a modern, open-source task manager that randomly plans your day for you. Add your flexible to-dos, and it automatically finds the perfect spot in your daily timetable. For crucial, time-sensitive appointments, you can pin them to a specific time. Reclaim your focus and reduce the mental load of planning.

<div align="center">

[![CLA assistant](https://cla-assistant.io/readme/badge/plazen/plazen)](https://cla-assistant.io/plazen/plazen)
[![MIT License](https://img.shields.io/github/license/plazen/plazen)](https://github.com/plazen/plazen/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/plazen/plazen)](https://github.com/plazen/plazen/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/plazen/plazen)](https://github.com/plazen/plazen/issues)
[![GitHub forks](https://img.shields.io/github/forks/plazen/plazen)](https://github.com/plazen/plazen/network)
[![GitHub stars](https://img.shields.io/github/stars/plazen/plazen)](https://github.com/plazen/plazen/stargazers)

</div>

## ✨ Key Features

- **Automatic Scheduling**: Add tasks with an estimated duration, and Plazen will find an open slot in your schedule.
- **Time-Sensitive Tasks**: Pin important tasks or appointments to a fixed time.
- **Visual Timetable**: View your entire day at a glance with a clean, intuitive timetable interface.
- **Task Management**: Mark tasks as complete, reschedule them with a simple right-click, and delete them when no longer needed.
- **Responsive Design**: Fully functional on both desktop and mobile devices.
- **Secure Storage**: All your tasks and settings are encrypted using AES-256-GCM and stored in a PostgreSQL database via Supabase.
- **Customizable View**: Adjust your timetable's start and end hours to match your day.
- **Real-time Indicator**: A "time needle" shows you the current time, helping you stay on track.
- **Secure Authentication**: User accounts are securely managed with Supabase Auth.
- **Other Calendars**: Import tasks from Google Calendar or iCal using the iCal URL.
- **Notifications**: Get notified 30 minutes before the task in Telegram.
- **Share your calendar**: Share your calendar, or pin it in your profile README, using [`plazen/images`](https://github.com/plazen/images)

## 🚀 Getting Started

Follow these instructions to get a local copy up and running for development and testing purposes.

### Prerequisites

- Node.js (v24 or later)
- npm, yarn, or pnpm

### 1. Clone the Repository

```bash
git clone https://github.com/plazen/plazen.git
cd plazen.org
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3. Create development environment

```bash
make dev
```

### 4. Start developing!

Open [http://localhost
:3000](http://localhost:3000) with your browser to see the result. You can now sign up and start using the application.

> [!NOTE]
> This is a limited Plazen development quickstart, for the full version, read the [documentation](https://docs.plazen.org/dev/full-setup)

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Please, see [`CONTRIBUTING.md`](CONTRIBUTING.md) for more information

## 📄 License

This project is distributed under the MIT License. See [our license](https://plazen.org/license) for more information.
