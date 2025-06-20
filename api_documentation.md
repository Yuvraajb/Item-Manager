# API Documentation

**Base URL:** `http://localhost:5001/api`

This API allows you to manage items by performing standard CRUD (Create, Read, Update, Delete) operations. All endpoints return JSON responses.

---

## Endpoints

### 1. Get All Items

**GET** `/items`

- Returns a list of all items.

**Response Example:**
```json
[
  {
    "id": 1,
    "name": "Sample Item",
    "description": "This is a sample item"
  },
  ...
]
```

---

### 2. Get a Single Item

**GET** `/items/:id`

- Returns the item with the specified ID.

**Response Example:**
```json
{
  "id": 1,
  "name": "Sample Item",
  "description": "This is a sample item"
}
```

---

### 3. Create a New Item

**POST** `/items`

- Creates a new item.
- Accepts a JSON body:

```json
{
  "name": "New Item",
  "description": "Description of the new item"
}
```

**Response Example:**
```json
{
  "id": 2,
  "name": "New Item",
  "description": "Description of the new item"
}
```

---

### 4. Update an Item

**PUT** `/items/:id`

- Updates the item with the specified ID.
- Accepts a JSON body with updated fields:

```json
{
  "name": "Updated Name",
  "description": "Updated description"
}
```

**Response Example:**
```json
{
  "id": 1,
  "name": "Updated Name",
  "description": "Updated description"
}
```

---

### 5. Delete an Item

**DELETE** `/items/:id`

- Deletes the item with the specified ID.

**Response Example:**
```json
{
  "message": "Item deleted successfully"
}
```

---

## Error Responses

- If an item is not found, the API returns:
```json
{
  "error": "Item not found"
}
```

- For invalid requests, the API returns:
```json
{
  "error": "Invalid request"
}
```

---

## Notes

- All endpoints expect and return JSON.
- Make sure the backend server is running at `http://localhost:5001`.

---

For any further questions or issues, please refer to the project README or open an issue in the repository.
