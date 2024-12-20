🌟 Image Search Application
This is a web application built to search for images using the Pixabay public API. The project aims to strengthen understanding of backend interaction through HTTP Requests and the use of asynchronous JavaScript functions.



📝 Features
Advanced Image Search: Enter a search term to display a gallery of relevant images.
Responsive Design: The interface is optimized for all devices, and images are displayed in an adaptive grid format.
Backend Interaction: Data is fetched from the Pixabay API using fetch, async/await, and promise handling.
Dynamic Pagination: A "Load More" button allows users to load more images without refreshing the page.
Image Zoom Gallery: Users can click on images to view larger versions using the SimpleLightbox library.
Dynamic Error Messages: Notifications are displayed using the iziToast library for an enhanced user experience.
Loading Indicator: While fetching data from the server, a loading indicator keeps users informed.



🛠️ Technologies Used
HTML5 and CSS3 for structure and styling.
JavaScript ES6+ for application logic.
SimpleLightbox for detailed image viewing.
iziToast for intuitive and attractive notifications.
Pixabay API for accessing data.
Vite for quick setup and application performance.



📂 Project Structure

bash
Copiază codul
.
├── index.html             # Main application page
├── src/
│   ├── css/
│   │   └── style.css       # Styling file
│   ├── js/
│   │   ├── main.js         # Main application logic
│   │   ├── pixabay-api.js  # Functions for Pixabay API interaction
│   │   └── render-functions.js # Functions for UI rendering
├── vite.config.js          # Vite configuration
├── package.json            # Information about dependencies and scripts
└── README.md               # Documentation




🚀 How to Run the Project?
Clone this repository:

bash
Copiază codul
git clone https://github.com/username/image-search-app.git
Install dependencies:

bash
Copiază codul
npm install
Start the development server:

bash
Copiază codul
npm run dev
Open the application in your browser: Navigate to http://localhost:5173 in your preferred browser.




🎯 Future Features
Add infinite scrolling to replace the "Load More" button.
Implement functionality to save favorite images.
Enable additional search filters (e.g., size, colors, etc.).



📄 License
This project is licensed under the MIT License.
