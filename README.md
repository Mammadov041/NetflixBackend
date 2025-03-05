# Netflix Backend  

# A backend for a Netflix-like app built with **Node.js, Express**, and **MongoDB**.  

## Setup  

### Prerequisites  
# - **Node.js** (LTS recommended)  
# - **MongoDB** (Local or Atlas)  

### Installation  
# ```sh
# git clone https://github.com/your-username/netflix-backend.git
# cd netflix-backend  
# npm install  
# ```

# Create a `.env` file with:  
# ```env
# MONGO_URI=your_mongodb_connection_string  
# PORT=5000  
# ```  

# Start the server:  
# ```sh
# npm start  
# ```  

## API Endpoints  

### Auth  
# - **POST** `/api/v1/auth/signup` – Create account  
# - **POST** `/api/v1/auth/login` – Login  
# - **POST** `/api/v1/auth/logout` – Logout  

### Movies & TV Shows  
# - **GET** `/api/v1/movie/trending` – Trending movies  
# - **GET** `/api/v1/tv/trending` – Trending TV shows  
# - **GET** `/api/v1/movie/:id/details` – Movie details  
# - **GET** `/api/v1/tv/:id/details` – TV show details  
# - **GET** `/api/v1/search/:type/:query` – Search movies, TV shows, or people  

## Tech Stack  
# - **Backend:** Node.js, Express.js  
# - **Database:** MongoDB (Mongoose)  
# - **Auth:** JWT (if implemented)  
# - **Frontend:** React (separate repo)  

## License  
# MIT License.  
