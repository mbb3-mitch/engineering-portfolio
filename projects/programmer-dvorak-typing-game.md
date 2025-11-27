# Programmer Dvorak Typing Game

## What it is
A web typing tutor focused on the Programmer Dvorak layout. Walks you through structured lessons and practice sets, measuring speed and accuracy to build layout muscle memory without losing symbols/punctuation fluency. Play at [https://typingdvorak.com/](https://typingdvorak.com/).

## Why it exists
Built to make adopting Programmer Dvorak faster for developers, pairing curated drills with real-time feedback instead of generic QWERTY-focused trainers.

## What I built
- Dvorak-specific lesson tracks plus practice modes fed by curated JSON configs
- Real-time metrics: WPM, accuracy, total words/characters, timer-based and open-ended sessions
- Level navigation and restart controls for step-by-step progression
- Material Kit React UI with responsive cards, carousels, and headers

## Tech Stack
- React 16 + React Router with Material-UI v3 components themed via Sass
- Express server (`server.js`) serving lesson/practice JSON and the production build on port 5019
- Axios for API calls; underscore/jquery utilities for the typing engine; Storybook scripts for component previews

## Notable Decisions
- Serve lesson/practice configs from Express to keep content versioned alongside the app
- Keep CRA dev server + Express API split for fast local iteration with proxying
- Use Material Kit React to get a polished UI quickly while keeping custom theming in Sass
- Lean on small utilities (underscore/jquery) for the typing engine instead of heavier state libraries

## What I'd Do Next
- Persist session history and progress per lesson
- Add Programmer Dvorak keyboard overlay/finger guides during tests
- Expand practice content (code snippets, punctuation drills) with difficulty filters
- Improve accessibility (focus management, ARIA labels) and mobile typing ergonomics
- Add automated tests and Storybook coverage for the TypingTest flow

## Links
- GitHub Repo: [https://github.com/mbb3/programmer-dvorak-typing-game](https://github.com/mbb3/programmer-dvorak-typing-game)
- Demo/Site: [https://typingdvorak.com/](https://typingdvorak.com/)

## Screenshots

![Menu page with lesson carousel](../assets/programmer-dvorak-typing-game/menu.png)
![Typing session with live stats](../assets/programmer-dvorak-typing-game/typing-session.png)
