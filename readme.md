# YouTube Clone

This is a **YouTube Clone** built using **React**, **Redux Toolkit**, **TypeScript**, and **TailwindCSS**. The application mimics the core functionalities of YouTube, including video search, video playback, and recommendations.

## Features

- **Home Page**: Displays a list of videos fetched from the YouTube API.
- **Search Functionality**: Search for videos using the YouTube API.
- **Watch Page**: Play videos with details like views, likes, and channel information.
- **Recommended Videos**: Display recommended videos based on the current video.
- **Responsive Design**: Styled using TailwindCSS for a modern and responsive UI.
- **Infinite Scrolling**: Load more videos as you scroll.

## Tech Stack

- **Frontend**: React, TypeScript
- **State Management**: Redux Toolkit
- **Styling**: TailwindCSS
- **API Integration**: Axios
- **Icons**: React Icons
- **Routing**: React Router DOM

## Folder Structure

YouTube ├── public/ # Static assets ├── src/ │ ├── components/ # Reusable UI components │ ├── pages/ # Application pages (Home, Search, Watch) │ ├── store/ # Redux store and reducers │ ├── utils/ # Utility functions │ ├── Types.ts # TypeScript types │ ├── App.tsx # Main application component │ ├── index.tsx # Entry point │ ├── index.css # Global styles ├── .gitignore # Git ignore file ├── package.json # Project dependencies and scripts ├── postcss.config.js # PostCSS configuration ├── tailwind.config.js # TailwindCSS configuration ├── tsconfig.json # TypeScript configuration

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/J0hnMilt0n/YouTube.git
   cd YouTube
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Create a .env file in the root directory and add your YouTube Data API key:

```
REACT_APP_YOTUBE_DATA_API_KEY=your_api_key
```

4. Start the development server:

```
npm start
```

5. Open the app in your browser at http://localhost:3000.

#### Scripts

**npm start**: Start the development server.
**npm run build**: Build the app for production.
**npm test**: Run tests.


**Dependencies**
**React**: Frontend library for building user interfaces.
**Redux Toolkit**: State management.
**TailwindCSS**: Utility-first CSS framework.
**Axios**: HTTP client for API requests.
**React Router DOM**: Routing library.
**React Icons**: Icon library.


**Dev Dependencies**
**PostCSS**: CSS processing tool.
**Autoprefixer**: Adds vendor prefixes to CSS.
**TailwindCSS**: CSS framework.


**API Integration**
The app uses the YouTube Data API to fetch video data, including:

Video details (title, views, duration, etc.)
Channel information
Recommended videos
Features in Detail
Home Page
Displays a grid of videos fetched from the YouTube API.
Infinite scrolling to load more videos.
Search Page
Allows users to search for videos.
Displays search results with video thumbnails, titles, and descriptions.
Watch Page
Plays the selected video in an embedded YouTube player.
Displays video details (views, likes, description, etc.).
Shows recommended videos in a sidebar.
Styling
The app is styled using TailwindCSS. Customizations are made in the tailwind.config.js file, and additional styles are added in index.css.

**Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests.

**License**
This project is for educational purposes only and is not intended for commercial use.

**Disclaimer**: This is a YouTube clone built for learning purposes. It is not affiliated with or endorsed by YouTube or Google.
