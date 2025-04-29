# itbootcamp_final_api_testing_

# API Testing Final Project

## 📋 About the Project
This project is a **Postman API testing collection** that tests a simple API with functionalities like user authentication, city management, and user profile handling.  
The tests cover **CRUD operations** (Create, Read, Update, Delete) for multiple endpoints.

## 🛠️ Tools and Libraries Used
- **Postman** (for API testing)
- **Postman Test Scripts** (JavaScript-based assertions)
- **Chai Assertion Library** (for advanced assertion handling inside Postman)
- **Swagger** (for understanding API endpoints and documentation)

## 🧪 Tested API Endpoints
- **Auth**: Login and register
- **City**: Create, read, update, and delete cities
- **Profile**: Manage user profiles
- **User**: User administration (Create/Update/Delete)

---

## 📄 Swagger Documentation

The API documentation was accessed via Swagger.

You can view the documentation in two ways:

### ✅ Option 1 – View online using Swagger Editor:
1. Open 👉 [Swagger Editor](https://editor.swagger.io/)
2. Click **File → Import File**
3. Upload this file from the repo: [`docs/swagger.yaml`](docs/swagger.yaml)

### ✅ Option 2 – Copy and paste:
1. Open [`swagger.yaml`](https://github.com/SasaDavic/itbootcamp_final_api_testing_/blob/main/docs/swagger.yaml)
2. Copy the raw content and paste it directly into the Swagger Editor

The Swagger documentation helps to:
- Understand the available API endpoints
- Get the base URL for API requests (e.g., `http://localhost:3000`)
- Verify request/response formats for test cases

---

## 🔗 Postman Documentation (Live)

You can view the live Postman documentation here:  
👉 [Postman API Documentation](https://documenter.getpostman.com/view/23500535/2sB2j1grfR)

---

## 📦 Local Postman Collection

If you'd like to run the API tests locally:

1. Download the following files:
   - [`api_testing_collection.postman_collection.json`](collection/api_testing_collection.postman_collection.json) (Postman Collection)
   - [`api_testing_environment.postman_environment.json`](collection/api_testing_environment.postman_environment.json) (Postman Environment)
   
2. Open Postman

3. Click **File → Import** and import both the collection and the environment files.

4. After importing, ensure the correct environment is selected in the top right corner of Postman.

5. Run the collection or specific requests using the **Collection Runner**.

---

## 📂 Project Structure
├── docs/ 
│ └── swagger.yaml # API documentation (OpenAPI 3.0) 
├── collection
│ └── api_testing_collection.postman_collection.json
│ └── api_testing_environment.postman_environment.json
├── README.md


---

## 🧾 Notes

> ⚠️ If the API or test scenarios change, please make sure to:
> - Update the `swagger.yaml` file in the `docs/` folder
> - Re-export and upload the latest Postman collection JSON

---

## 👩‍💻 Author

**Sasa (Davic) Zivkovic**  
GitHub: [github.com/SasaDavic](https://github.com/SasaDavic)




