# 📺 User Video History - DynamoDB Rating Entry

This project demonstrates how to create a new item in an **Amazon DynamoDB** table named `UserVideoHistory`, with a focus on adding a numeric **rating** attribute to the entry. This is a simple but critical step in building scalable, personalized recommendation systems using AWS services.

## 🧩 Project Goal

- ✅ Create a new item in the **UserVideoHistory** table.
- ✅ Use a unique `userId` for the new entry.
- ✅ Add a new attribute named **`rating`** of **Number** data type.

## 🧪 Solution Validation

The solution is considered valid if:
- The table **UserVideoHistory** contains at least one new item.
- The new item includes:
  - A unique `userId` (string).
  - A `rating` attribute that is of **Number** data type.

## 📝 Example Item

```json
{
  "userId": "user_001",
  "videoId": "video_123",
  "timestamp": "2025-07-03T10:00:00Z",
  "rating": 4.5
}
