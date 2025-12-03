# ChatGPT React App

A simple and beautiful ChatGPT clone built with React and the OpenAI API.

## Features

- Clean, modern chat interface
- Real-time message streaming
- Typing indicator
- Responsive design
- Auto-scroll to latest messages

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- OpenAI API key

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd chatgpt-react-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up your OpenAI API key

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Then edit `.env` and add your OpenAI API key:

```
VITE_OPENAI_API_KEY=sk-your-api-key-here
```

**How to get an OpenAI API key:**
1. Go to [OpenAI Platform](https://platform.openai.com/)
2. Sign up or log in
3. Navigate to API keys section
4. Create a new API key
5. Copy and paste it into your `.env` file

### 4. Run the development server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

## Building for Production

```bash
npm run build
```

The production-ready files will be in the `dist` folder.

## Important Notes

**Security Warning:** This app uses the OpenAI API directly from the browser (`dangerouslyAllowBrowser: true`). This is fine for development and personal use, but for production applications, you should:

1. Create a backend server to handle API calls
2. Keep your API key secure on the server
3. Never expose your API key in client-side code

## Technology Stack

- React
- Vite
- OpenAI API
- CSS3

## License

MIT
