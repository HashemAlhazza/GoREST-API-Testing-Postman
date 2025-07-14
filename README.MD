# 🧪 GoREST API Testing with Postman

This project contains automated API tests for the [GoREST API](https://gorest.co.in/) using **Postman**.  
The API is split into **four logical collections**:

- `/users`
- `/posts`
- `/comments`
- `/todos`

---

## 📦 Project Files

| File                             | Description                         |
|----------------------------------|-------------------------------------|
| `Users_Postman_Collection.json`   | Test suite for `/users` endpoint    |
| `Posts_Postman_Collection.json`   | Test suite for `/posts` endpoint    |
| `Comments_Postman_Collection.json`| Test suite for `/comments` endpoint |
| `Todos_Postman_Collection.json`   | Test suite for `/todos` endpoint    |
| `GoREST_Environment.json`         | Environment config (baseURL, token) |
| `Test_Results_Run1.json` *(opt)* | Sample test result export           |

---

## ✅ Test Coverage

Each collection includes:

- Positive test cases (201/200 responses)
- Negative test cases (422/404/etc.)
- Schema validation using JSON Schema
- Request–response consistency checks
- Status code & performance tests
- Format checks (email, dates, etc.)
- Full resource lifecycle: Create → Retrieve → Delete
- Use of Postman global/environment variables

---

## 🛠️ Tools Used

- Postman
- JSON Schema Validation
- Collection Runner
- Global & Environment Variables

---

## 🚀 How to Run the Tests

1. Import each collection into Postman
2. Import the `GoREST_Environment.json`
3. Set your personal Bearer Token in the environment
4. Run each collection using the **Collection Runner**
5. (Optional) Use Newman CLI for automation or reporting

---

## ✍️ Author

Made with 💻 and 🧪 by **Hashem** — Embedded Systems & QA Engineer  
Feel free to use or fork for learning or interview prep!
