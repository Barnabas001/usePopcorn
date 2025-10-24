🎬 usePopcorn – Movie Search & Watchlist App

usePopcorn is a React application that lets users search movies from the OMDb API
, view detailed information, rate them, and maintain a personalized “watched” movie list using local storage.

🚀 Features

🔍 Search Movies – Instantly search for any movie by title using the OMDb API.

📄 Movie Details – View runtime, genre, cast, director, and IMDb ratings.

⭐ Rate Movies – Rate movies yourself using a star rating system.

📋 Watched List – Add movies you’ve watched and store them locally.

🧮 Summary Section – View stats such as:

Number of movies watched

Average IMDb rating

Average user rating

Average runtime

💾 Persistent Data – Watched movies are stored in Local Storage, so they stay saved even after reloading.

⚡ Keyboard Shortcuts –

Enter: Focus the search bar

Escape: Close movie details

🧩 Project Structure
src/
│
├── App.js               # Main app logic
├── StarRating.js        # Custom star rating component
├── useMovies.js         # Custom hook to fetch movies from OMDb
├── useLocalStorageState.js  # Custom hook for managing local storage state
├── useKey.js            # Custom hook for handling keyboard shortcuts
└── index.css            # Styling

🛠️ Technologies Used

React (Hooks, Components, Props)

OMDb API (Open Movie Database)

Local Storage API

Custom React Hooks

CSS for styling

⚙️ Setup Instructions

Clone the repository:

git clone https://github.com/yourusername/usepopcorn.git
cd usepopcorn


Install dependencies:

npm install


Add your OMDb API key:

Replace the existing key inside App.js

const KEY = "your_omdb_api_key";


You can get a free API key from OMDb API
.

Run the app:

npm start


Open in browser:
The app should now be running at http://localhost:3000

🧠 Core Concepts Demonstrated

Reusable custom hooks (useMovies, useLocalStorageState, useKey)

Component-based architecture

Conditional rendering and state management

Effect cleanup (resetting document title on component unmount)

Keyboard event handling in React

Data persistence with localStorage

📸 Preview
Search Page	Movie Details	Watched List

	
	

(Replace these with actual screenshots)

💡 Future Enhancements

🔄 Pagination for movie search results

📱 Responsive design for mobile devices

🗃️ Backend support for user accounts and syncing watched lists

🧠 Recommendation system based on ratings

🧑‍💻 Author

Barnabas Affonshike
Frontend Developer passionate about building responsive, accessible, and visually appealing applications.

📧 Email: marichristrav@gmail.com

🌐 Website: www.sabiflyup.com

📄 License

This project is licensed under the MIT License – you’re free to use, modify, and distribute it.
