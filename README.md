# ComfortCove
**ComfortCove** is a web application inspired by Airbnb that allows users to sign up, log in, add their home listings, and leave reviews. The project includes a map feature for listing locations and utilizes Cloudinary for media management.

## Features
- **User Authentication**: Sign up and log in securely.
- **Add Listings**: Users can create and manage their home listings.
- **Review System**: Leave and view reviews for listings.
- **Map Integration**: View listings on a map using Mapbox.
- **Media Management**: Upload and manage media using Cloudinary.
- **Responsive Design**: The application is optimized for various devices.

## Tech Stack
- **MongoDB**: Database for storing user data, listings, and reviews.
- **Express.js**: Web framework for Node.js used to build the application.
- **Node.js**: JavaScript runtime for the server-side.
- **EJS (Embedded JavaScript)**: Templating engine for rendering HTML pages.
- **Cloudinary**: Media management and image hosting.
- **Mapbox**: Map service for displaying locations.
- **HTML/CSS/JavaScript**: Front-end technologies for the user interface.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
```
git clone https://github.com/arpan-tanwar/ComfortCove.git
```

2. **Install dependencies:**
```
npm install
```

3. **Set up environment variables:**
   - Create a '.env' file in the root directory.
   - Add the following environment variables:
```
CLOUD_NAME=<CLOUD_NAME>
CLOUD_API_KEY=<CLOUD_API_KEY>
CLOUD_API_SECRET=<CLOUD_API_SECRET>

MAP_TOKEN=<MAP_TOKEN>

ATLASDB_URL=<ATLASDB_URL>

SECRET=<SECRET>
```

4. **Run the application:**
```
node app.js
```
The app will be available at http://localhost:8080 by default.

## Roadmap
- [x] User Authentication
- [x] Add Listings
- [x] Review System
- [ ] Search and Filter
- [ ] Improve UI/UX
- [ ] Additional Features (Wishlist, Favorites, etc.)

## Contributing
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or feedback, please contact [arpantanwar.at@gmail.com].
