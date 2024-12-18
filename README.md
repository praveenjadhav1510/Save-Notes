# Note App with Drag-and-Drop

A simple note-taking app built with React, allowing users to create, edit, drag, drop, and delete notes. Notes are stored in `localStorage` to persist across sessions, along with their position and content.

## Features

- **Create Notes**: Add new notes with a custom border color using the color picker.
- **Edit Notes**: Write and update the content of each note.
- **Drag-and-Drop**: Drag notes to any position on the screen, and their new position is saved.
- **Delete Notes**: Remove notes by clicking the "x" button.
- **Persistent Data**: All notes' content and positions are saved in `localStorage`, so they remain even after page reloads.

## Demo

[Insert demo link if available]

## Installation

### Prerequisites

Make sure you have `Node.js` and `npm` installed. If not, download and install them from [Node.js](https://nodejs.org/).

### Steps to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/praveenjadhav1510/Save-Notes
   ```

2. Navigate into the project directory:

   ```bash
   cd Save-Notes
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:3000`.

## Usage

- Use the color picker to set the border color of a new note.
- Click the "+" button to create a new note.
- Drag notes to reposition them.
- Click on the "x" button to delete a note.
- Edit the content of a note by typing into the text area.

## Technologies Used

- **React**: Front-end framework used for building the UI.
- **localStorage**: Used for saving notes and their positions.
- **CSS**: Styling for the app's user interface.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
