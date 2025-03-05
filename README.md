# 🎬 Netflix Backend  

# This is the backend for a Netflix-like application, built with Node.js and Express, and using MongoDB as the database.  

## 🚀 Getting Started  

### 📋 Prerequisites  

# - **Node.js** (Latest LTS version recommended)  
# - **MongoDB** (Locally installed or a cloud database like MongoDB Atlas)  

### 🔧 Installation  

# 1. **Clone this repository:**  
#    ```sh
#    git clone https://github.com/your-username/netflix-backend.git
#    cd netflix-backend
#    ```

# 2. **Install dependencies:**  
#    ```sh
#    npm install
#    ```

# 3. **Create a `.env` file in the root directory and add the following:**  
#    ```env
#    MONGO_URI=your_mongodb_connection_string
#    PORT=5000
#    ```

# 4. **Start the server:**  
#    ```sh
#    npm start
#    ```

### ▶️ Running the Frontend  

# Ensure the backend is running before starting the frontend. Then, navigate to your frontend project directory and run:  
#    ```sh
#    npm install
#    npm start
#    ```

### 📡 API Endpoints  

# | Method | Endpoint        | Description          |
# |--------|---------------|----------------------|
# | POST | `/api/v1/auth/signup` | Create new user account |
# | POST | `/api/v1/auth/login` | Login with existing account |
# | POST | `/api/v1/auth/logout` | Log out |

# | GET | `/api/v1/movie/trending` | Get trending movies |
# | GET | `/api/v1/movie/:id/details` | Get movie details by id |
# | GET | `/api/v1/movie/:id/trailers` | Get movie trailers by id |
# | GET | `/api/v1/movie/:id/similar` | Get similar movies by id |
# | GET | `/api/v1/movie/category` | Get movies by category |

# | GET | `/api/v1/tv/trending` | Get trending tv-shows |
# | GET | `/api/v1/tv/:id/details` | Get tv-show details by id |
# | GET | `/api/v1/tv/:id/trailers` | Get tv-show trailers by id |
# | GET | `/api/v1/tv/:id/similar` | Get similar tv-shows by id |
# | GET | `/api/v1/tv/category` | Get tv-shows by category |

# | GET | `/api/v1/search/person/:query` | Search person |
# | GET | `/api/v1/search/movie/:query` | Search movie |
# | GET | `/api/v1/search/tv/:query` | Search tv-show |
# | GET | `/api/v1/search/history` | Get search history |
# | DELETE | `/api/v1/search/history/:id` | Remove item from search history |


## 🛠 Tech Stack  

# - **Backend:** Node.js, Express.js  
# - **Database:** MongoDB (Mongoose ODM)  
# - **Authentication:** JWT (if implemented)  
# - **Frontend:** React (in a separate repository)  

## 📜 License  

# This project is open-source and available under the MIT License.  

# ---
