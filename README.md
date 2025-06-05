# GitHubinder

A React application that allows you to browse, filter, and save potential GitHub candidates, inspired by the Tinder swipe experience.

## Features

- **Browse Candidates:** Fetches and displays GitHub users as "candidates".
- **Save Favorites:** Save interesting candidates to your local storage.
- **Filter & Sort:** Filter and sort saved candidates by name, location, email, or company.
- **Reject Option:** Remove candidates from your saved list.
- **Responsive UI:** Built with [Flowbite React](https://flowbite-react.com/) and Tailwind CSS.
- **Routing:** Navigate between the main search and saved candidates using React Router.

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/github-tinder.git
   cd github-tinder/Develop
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Usage
You can go to the following link if you want to access the app from anywhere in the world: [https://githubinder.onrender.com](GitHubinder)

## Project Structure

```
src/
  components/      # Reusable UI components (Nav, SavedCandidatesTable, etc.)
  pages/           # Main pages (CandidateSearch, SavedCandidates)
  interfaces/      # TypeScript interfaces (Candidate)
  api/             # API functions for GitHub requests
  App.tsx          # Main app layout with routing
  main.tsx         # Entry point
```

## Usage

- **Home:** Browse GitHub candidates and save the ones you like.
- **Potential Candidates:** View, filter, sort, and remove your saved candidates.

## Customization

- Update GitHub API queries in `src/api/API.ts` to change candidate search criteria.
- Adjust UI styles using Tailwind CSS classes.

## License

MIT

---

*Made with ❤️ by Sergio*