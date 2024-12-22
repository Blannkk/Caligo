# Caligo
# Student Dashboard

A modern, responsive student dashboard built with React, TypeScript, and Material-UI. Features internationalization support and a clean, intuitive interface.

## Features

- 🎨 Modern UI with Material-UI components
- 🌐 Internationalization (i10n) with Arabic and English support
- 📱 Fully responsive design
- 🔐 Authentication with Redux state management
- 📊 Dashboard with announcements and quizzes
- 🎯 Real-time quiz tracking
- 📅 Exam schedule management

## Tech Stack

- React 18
- TypeScript
- Material-UI
- Redux Toolkit
- Vite (Build tool)
- Tailwind CSS
- i10n (Internationalization)

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd student-dashboard
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

## Project Structure

```
src/
├── components/        # Reusable UI components
├── pages/            # Page components
├── services/         # API and external service integrations
├── store/            # Redux store configuration
├── types/            # TypeScript type definitions
├── utils/            # Utility functions
├── i10n/             # Internationalization files
└── theme.ts          # Material-UI theme configuration
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Environment Variables

Create a `.env` file in the root directory:

```env
VITE_SUPABASE_URL=Database_URl
VITE_SUPABASE_ANON_KEY=Database_key
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
