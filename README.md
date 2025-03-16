# HttpRequestDemo - Postman Collection

This repository contains a Postman Collection named **"HttpRequestDemo"**, which demonstrates the use of basic HTTP requests (GET, POST, PUT, DELETE) using the public API [https://reqres.in](https://reqres.in).

---

## 📋 Collection Overview

| Method  | Endpoint                  | Description                    |
|--------|--------------------------|--------------------------------|
| GET    | `/api/users?page=2`       | Retrieve list of users (page 2)|
| POST   | `/api/users`              | Create a new user              |
| PUT    | `/api/users/767`          | Update user with ID 767        |
| DELETE | `/api/users/767`          | Delete user with ID 767        |

---

## 🚀 How to Use This Collection

### 1. Open with Postman

- **Download and Install Postman**: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
- **Import Collection**:
  1. Open Postman.
  2. Click on **"Import"**.
  3. Select **"Upload Files"**.
  4. Choose `HttpRequestDemo.postman_collection.json` from this repository.
  5. Click **"Import"** to add it to your collections.

- **Run Requests**:
  1. Go to **"Collections"**.
  2. Select **"HttpRequestDemo"**.
  3. Choose any request (GET, POST, PUT, DELETE) and click **"Send"** to execute and see the response.

---

## 🌐 Direct API Testing via Reqres

If you don't want to use Postman, you can test these APIs directly using [https://reqres.in](https://reqres.in).

### ✅ Sample Requests:

#### GET Request - List Users
```
GET https://reqres.in/api/users?page=2
```

#### POST Request - Create User
```
POST https://reqres.in/api/users
Content-Type: application/json

{
    "name": "pavan",
    "job": "trainer"
}
```

#### PUT Request - Update User
```
PUT https://reqres.in/api/users/767
Content-Type: application/json

{
    "name": "pavan",
    "job": "Engineer"
}
```

#### DELETE Request - Delete User
```
DELETE https://reqres.in/api/users/767
```

---

## 📂 File Structure

```
.
├── HttpRequestDemo.postman_collection.json  # Postman collection file
└── README.md                               # Documentation file
```

---

## 📌 Notes

- This collection uses [https://reqres.in](https://reqres.in), a free public API for testing HTTP requests.
- No authentication is required.
- Ensure an active internet connection to receive responses from the API.

---

## 📧 Contact

If you have any questions or suggestions, feel free to reach out via **GitHub Issues**.

---

⭐️ **Don't forget to star this repository if you found it useful!**
