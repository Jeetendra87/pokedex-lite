# How to Run

# Install dependencies:

```bash
npm install
```

# Start the development server:

```bash
npm run dev
```

# Open your browser:
Go to http://localhost:5173

# Technologies / Libraries Used & Why:
| Technology            | Why it was used                                                         |
| --------------------- | ----------------------------------------------------------------------- |
| **React**             | For building UI using component-based architecture and state management |
| **Vite**              | Provides fast dev server & optimized build             |
| **Tailwind CSS**      | For utility-first styling, responsive design & fast iteration           |
| **PokeAPI**           | To fetch real-time Pokémon data like name, images, types, etc.          |
| **Local Storage**     | To persist favorite Pokémon even after page reload                      |
| **JavaScript (ES6+)** | For logic, API handling and functionality implementation                |

# Challenges Faced & Solutions:
Challenge 1: Slow Loading While Fetching Pokémon
Problem: Fetching many Pokémon caused loading delays

Solution: Implemented loading spinner and structured fetch to improve UX.

Challenge 2: Favorites Not Persisting After Reload

Problem: Favorites state disappeared on refresh

Solution: Used localStorage to store favorite Pokémon and retrieve on load.

Challenge 3: Filter and Search Combined Logic

Problem: Filtering by type + searching by name together caused mismatches

Solution: Applied layered filtering logic to ensure both work simultaneously.

Challenge 4: Responsive Layout on Different Screen Sizes

Problem: Ensuring the Pokémon grid and detail modal displayed properly and remained usable across mobile, tablet, and desktop screens without layout breaking


Solution: Used Tailwind CSS responsive utilities (sm, md, lg) to adjust grid columns, spacing, and modal layout. This allowed the UI to automatically adapt to different screen sizes without writing custom CSS.
