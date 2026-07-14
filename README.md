# Super App

A modern entertainment dashboard built with Next.js, TypeScript, Redux Toolkit, and Tailwind CSS.

## Live Demo

https://your-vercel-app.vercel.app

## GitHub Repository

https://github.com/your-username/super-app

---

## Overview

Super App is a personalized entertainment dashboard that allows users to:

* Register and create a profile
* Select entertainment categories
* View live weather information
* Read automatically updating news headlines
* Use a countdown timer/alarm
* Save personal notes with persistence
* Discover movies based on selected interests

The application follows modern frontend development practices with reusable components, optimized performance, responsive design, and state management.

---

## Features

### User Registration

* Name, Username, Email, Mobile Number
* Form validation
* Error handling
* Local storage persistence

### Category Selection

Users can select entertainment categories such as:

* Action
* Drama
* Romance
* Thriller
* Horror
* Fantasy
* Music
* Fiction

**Requirement:** Minimum 3 categories must be selected before proceeding.

### Dashboard

#### User Profile

Displays:

* Name
* Username
* Email
* Mobile Number
* Selected Categories

#### Weather Widget

Provides live weather information using OpenWeatherMap API:

* Temperature
* Humidity
* Wind Speed
* Weather Conditions

#### News Feed

Displays latest news headlines and automatically rotates every 2 seconds.

#### Timer Widget

Features:

* Countdown timer
* Start
* Pause
* Reset
* Alarm notification

#### Notes Widget

* Create notes
* Auto-save functionality
* Stored in browser local storage

### Movie Discovery

Based on selected categories:

* Fetches movies dynamically
* Hover animations
* Responsive movie cards
* Detailed movie modal

Movie Details Include:

* Poster
* Title
* Plot
* Genre
* Actors
* Runtime
* IMDb Rating

---

## Tech Stack

### Frontend

* Next.js 15
* React 19
* TypeScript
* Tailwind CSS

### State Management

* Redux Toolkit

### APIs

* OpenWeatherMap API
* NewsAPI
* OMDB API

### Storage

* Browser Local Storage

---

## Project Structure

```bash
src/
│
├── app/
│   ├── register/
│   ├── categories/
│   ├── dashboard/
│   └── movies/
│
├── components/
│   ├── RegistrationForm.tsx
│   ├── CategoryCard.tsx
│   ├── ProfileCard.tsx
│   ├── WeatherWidget.tsx
│   ├── NewsWidget.tsx
│   ├── TimerWidget.tsx
│   ├── NotesWidget.tsx
│   ├── MovieCard.tsx
│   └── MovieModal.tsx
│
├── store/
│   ├── store.ts
│   ├── userSlice.ts
│   └── categorySlice.ts
│
├── services/
│   ├── weatherApi.ts
│   ├── newsApi.ts
│   └── movieApi.ts
│
└── hooks/
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/super-app.git

cd super-app
```

### Install Dependencies

```bash
npm install
```

### Create Environment File

Create a `.env.local` file in the root directory.

```env
NEXT_PUBLIC_WEATHER_API_KEY=your_weather_api_key

NEXT_PUBLIC_NEWS_API_KEY=your_news_api_key

NEXT_PUBLIC_OMDB_API_KEY=your_omdb_api_key
```

### Run Development Server

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

---

## Build for Production

```bash
npm run build
```

```bash
npm start
```

---

## Performance Optimizations

* Next.js App Router
* Dynamic Imports
* Image Optimization
* Redux Toolkit State Management
* Local Storage Persistence
* Component Reusability
* SEO Metadata
* Responsive Layout

---

## Validation Rules

### Registration

* Name Required
* Username Required
* Valid Email Required
* Mobile Number Must Be 10 Digits

### Category Selection

* Minimum 3 Categories Required

---

## Environment Variables

```env
NEXT_PUBLIC_WEATHER_API_KEY=

NEXT_PUBLIC_NEWS_API_KEY=

NEXT_PUBLIC_OMDB_API_KEY=
```

---

## Deployment

### Vercel

```bash
npm run build
```

Deploy using:

https://vercel.com

### Netlify

```bash
npm run build
```

Deploy the generated build.

---

## Future Enhancements

* User Authentication
* Dark Mode
* Personalized Recommendations
* Favorite Movies
* Search Functionality
* PWA Support
* Offline Storage

---

## Author

Your Name

GitHub: https://github.com/hemalathavenkamsetty

LinkedIn: https://linkedin.com/in/hemalathavenkamsetty

---

## License

This project is developed for educational and assessment purposes.
