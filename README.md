# Foody-API-Manual-Testing
This repository contains manual API testing for the Foody API, performed using Postman. The goal of this project is to validate various API endpoints for managing users, food items, and authentication within the Foody platform.

## Project Overview
The Foody API allows users to create, update, search, and delete food items. The project also supports user authentication, allowing registered users to manage food-related data. Below are the APIs tested in this project:

- Create User: Allows the creation of new user accounts.
- Get Authentication Token: Retrieves an authentication token for user access.
- Create Food: Allows users to submit a new food item.
- Get All Foods: Fetches a list of all food items.
- Search Food: Allows users to search food items by keywords.
- Update Food: Allows users to modify an existing food item.
- Delete Food: Allows users to remove a food item from the system.
- Supported Methods: Retrieves all the supported methods of the API.
  
## Tested API Endpoints

The following endpoints were tested:

POST /api/User/Create: Create a new user.
POST /api/Auth/Token: Get authentication token.
POST /api/Food: Create a new food item.
GET /api/Food: Get all foods.
GET /api/Food/Search: Search for food by keyword.
PATCH /api/Food/{id}: Update an existing food item.
DELETE /api/Food/{id}: Delete a food item.
GET /api/Info/Methods: List supported methods.

## Tools Used
- Postman: For creating and running API test cases.
- GitHub: For version control and repository management.
  
## How to Use
1. Clone the repository:
   
git clone https://github.com/yourusername/Foody-API-Testing.git

2. Navigate to the project directory:
   
cd Foody-API-Testing

3. Run the test cases by following the test collection within the Postman workspace.

## License
This project is licensed under the MIT License.
