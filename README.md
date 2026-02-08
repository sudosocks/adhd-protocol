# ADHD Protocol Dashboard

> A local HTML dashboard for Obsidian designed to help ADHD brains stay focused. Features a built-in timer, automated daily logs, structured weekly/monthly reviews, and status reports. Connects directly to your vault via Obsidian Advanced URI.

## 🎯 Features

*   **Focus Timer**: Built-in Pomodoro-style timer with flashing visual alerts when time is up to grab your attention.
*   **Hyperfocus Tracking**: A persistent "Current Hyperfocus" input to keep your main goal front and center.
*   **Automated Workflows**: One-click buttons to create and open specific note types in Obsidian:
    *   **Daily Notes**: automatically linked to yesterday/tomorrow, with sections for tasks and inbox.
    *   **Reviews**: Templated Weekly and Monthly reviews to track progress.
    *   **Status Reports**: Generate Weekly and Monthly status reports aggregating completed tasks and meetings.
    *   **Quick Capture**: Instantly append tasks to your Inbox.
    *   **Meeting Notes**: Prompts for a title and creates a structured meeting note.
    *   **Relationship Management**: Create profiles for people and view team directories.
*   **Local & Secure**: Runs entirely locally in your browser. Data works directly with your local Obsidian notes.

## 🔌 Prerequisites

To use this dashboard, you need [Obsidian](https://obsidian.md/) installed with the following community plugins:

1.  **[Advanced URI](https://github.com/Vinzent03/obsidian-advanced-uri)** (Essential): Enhances Obsidian's URI scheme to allow file creation and complex opening commands.
2.  **[Dataview](https://github.com/blacksmithgu/obsidian-dataview)** (Required): Powers the dynamic tables in the generated notes (e.g., listing completed tasks, finding meetings).
3.  **[Tasks](https://github.com/schemar/obsidian-tasks)** (Required): Used in Daily/Weekly notes to filter and manage tasks.

## 🚀 Setup

1.  **Clone or Download** this repository to your local machine.
2.  **Configure Obsidian**: Ensure your Obsidian vault is open and the required plugins are installed and enabled.
3.  **Launch the Dashboard**: Open `adhd-protocol.html` in your web browser.
4.  **Connect Vault**: Scroll down to the "Settings" area in the dashboard. Enter the exact name of your Obsidian Vault in the "Vault Name" field.
    *   *Note: This is stored in your browser's local storage.*

## 📂 Usage

The dashboard is divided into three main sections:

### 1. Focus
*   **Current Hyperfocus**: Type your single most important task here. It stays until you change it.
*   **Timer**: Click `Start` for a 25-minute focus session. The tab title updates with the time remaining. When finished, the screen flashes red. Click the timer display to edit the duration.

### 2. Routine & Reviews
*   **Start Day**: Creates/Opens today's Daily Note.
*   **Quick Capture**: Fast way to dump a task into your inbox.
*   **Weekly/Monthly Review**: Creates review notes to plan ahead and reflect on the past period.

### 3. Work & Output
*   **Status Reports**: Generates summary reports pulling data from your daily/weekly notes. perfect for sending updates to managers.
*   **Meeting Notes**: Quickly spins up a note for a new meeting.
*   **Suggestions/People**: Manage ideas and CRM-like contact cards.

## 🛠️ Security

This project has been audited for basic web security:
*   **Input Sanitization**: User inputs are stripped of dangerous characters to prevent injection attacks into your notes.
*   **CSP**: A strict Content Security Policy is enforced.
*   **Privacy**: All data stays on your machine. No external analytics or tracking.

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.
Free & Open-Source Software. Developed by [sudosocks](https://github.com/sudosocks).
