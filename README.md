# AI_summarizer_React_RapidAPI

Summize is a web app that uses natural language processing to generate summaries of articles or documents. It simplifies your reading with clear and concise summaries that capture the main points of the original text.

## Features

- Paste an article link and get a summary in seconds
- Choose between extractive or abstractive summarization methods
- See the word count and the reduction percentage of the summary
- Browse your history of summarized articles and copy the links
- Enjoy a beautiful and user-friendly interface

## Technologies

This project is built with:

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) - A next-generation frontend tooling that provides a fast development environment
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework that provides a set of customizable classes for styling elements
- [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview) - A powerful data fetching and caching tool that simplifies state management and API integration
- [RapidAPI](https://rapidapi.com/) - A platform that provides access to thousands of APIs for various purposes
- [Article Extractor and Summarizer API](https://rapidapi.com/montanaflynn/api/article-extractor-and-summarizer) - An API that extracts the main content from a webpage and summarizes it using natural language processing

## Installation

To run this project locally, you need to have [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) installed on your machine.

1. Clone this repository:

```bash
git clone https://github.com/AhmetTasdemir/AI_summarizer_React_RapidAPI.git
```

2. Navigate to the project directory:

```bash
cd AI_summarizer_React_RapidAPI
```

3. Install the dependencies:

```bash
npm install
```

4. Create a .env file in the root directory and add your RapidAPI key:

```bash
VITE_RAPID_API_ARTICLE_KEY=your_key_here
```

5.Start the development server:

```bash
npm run dev
```
