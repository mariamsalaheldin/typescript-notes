# React Note-Taking App

A modern, responsive note-taking application built with React, TypeScript, and Bootstrap. Features include tag management, local storage persistence, and a clean, intuitive user interface.

## Features

- ✏️ **Create, edit, and delete notes** with a simple, clean interface
- 🏷️ **Tag management** - Create, edit, and delete tags to organize your notes
- 🔍 **Search and filter** - Find notes by title or tags
- 💾 **Local storage** - Your notes persist across browser sessions
- 🎨 **Custom styling** - Purple theme with improved visual hierarchy
- 📱 **Responsive design** - Works great on desktop and mobile devices

## Technologies Used

- **React 18** - Modern React with hooks
- **TypeScript** - Type safety throughout the application
- **Bootstrap 5** - Responsive UI components
- **React Router** - Client-side routing
- **React Select** - Advanced select components for tags
- **Vite** - Fast development and build tool
- **CSS Modules** - Scoped styling

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/react-note-taking-app.git
   cd react-note-taking-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

## Usage

1. **Creating Notes**: Click "Create" to add a new note with title, content, and tags
2. **Managing Tags**: Click "Edit Tags" to create, edit, or delete tags
3. **Searching**: Use the search bar to filter notes by title or tags
4. **Editing**: Click on any note to view and edit its content
5. **Deleting**: Use the delete button to remove notes

## Project Structure

```
src/
├── App.tsx              # Main application component
├── NoteList.tsx         # Note list and search functionality
├── NoteForm.tsx         # Form for creating/editing notes
├── Note.tsx             # Individual note display
├── EditNote.tsx         # Edit note component
├── NewNote.tsx          # New note component
├── NoteLayout.tsx       # Layout wrapper for notes
├── useLocalStorage.ts   # Custom hook for local storage
├── custom.css           # Custom styling overrides
└── NoteList.module.css  # CSS modules for note cards
```

## Customization

The app uses a custom purple theme with the following color scheme:
- Primary buttons: Purple (#6f42c1)
- Badges: Purple background
- Secondary buttons: Transparent grey hover effects
- Note body: Light grey background for contrast

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [React](https://reactjs.org/)
- Styled with [Bootstrap](https://getbootstrap.com/)
- Icons from Unicode emoji set

- # Modified Project

This project is a modified version of the original work by [WebDevSimplified](https://github.com/WebDevSimplified). The original project is licensed under the MIT License, which permits free use, modification, and distribution under the terms outlined below.
