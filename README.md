# 🚀 Postman API Testing Collection

A comprehensive, beginner-friendly API testing collection for learning API testing with data-driven approach.

## 📋 Overview

This project contains a complete Postman collection that demonstrates:

- **Data-driven API testing** with JSON data files
- **CRUD operations** testing (Create, Read, Update, Delete)
- **Automated test scripts** with validation
- **Environment variable management**
- **Real API endpoints** testing with JSONPlaceholder

## 🎯 Features

- ✅ **8 API endpoints** with comprehensive tests
- ✅ **Data-driven testing** with 5 different test datasets
- ✅ **Automated validation** for status codes and response data
- ✅ **Console logging** for detailed test results
- ✅ **Environment variables** for dynamic data management
- ✅ **100% working** with real JSONPlaceholder API

## 📁 Project Structure

```
postman-api-testing/
├── FINAL-Working-Collection.postman_collection.json  # Main collection file
├── test-data.json                                   # Test data for iterations
├── Environment.postman_environment.json             # Environment variables
├── README.md                                        # This file
└── docs/                                           # Additional documentation
    ├── FIXED-README.md                             # Troubleshooting guide
    └── HOW-TO-USE.md                              # Detailed usage guide
```

## 🚀 Quick Start

### Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your system

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/YOUR-USERNAME/postman-api-testing.git
   cd postman-api-testing
   ```

2. **Import Collection**

   - Open Postman
   - Click **Import** button
   - Select `FINAL-Working-Collection.postman_collection.json`
   - Collection imported successfully! ✅

3. **Import Environment** (Optional)

   - Click gear icon (⚙️) in top right
   - Select **Import**
   - Choose `Environment.postman_environment.json`
   - Set as active environment

4. **Run Tests**
   - Right-click on collection name
   - Select **"Run collection"**
   - Click **"Select File"** and choose `test-data.json`
   - Click **"Run"**

## 📊 Test Data

The `test-data.json` file contains 5 different test datasets:

```json
[
  {
    "name": "John Doe",
    "email": "john@example.com",
    "product_name": "iPhone 15",
    "product_description": "Latest iPhone model"
  }
  // ... 4 more datasets
]
```

## 🧪 API Endpoints Tested

| #   | Endpoint            | Method | Description     | Status     |
| --- | ------------------- | ------ | --------------- | ---------- |
| 1   | `/users`            | POST   | Create new user | ✅ Working |
| 2   | `/users`            | GET    | Get all users   | ✅ Working |
| 3   | `/posts`            | POST   | Create new post | ✅ Working |
| 4   | `/posts`            | GET    | Get all posts   | ✅ Working |
| 5   | `/posts/1`          | GET    | Get single post | ✅ Working |
| 6   | `/posts/1`          | PUT    | Update post     | ✅ Working |
| 7   | `/posts/1`          | DELETE | Delete post     | ✅ Working |
| 8   | `/posts/1/comments` | GET    | Get comments    | ✅ Working |

## ✅ Test Results

When you run the collection with data file, you'll get:

```
✅ Create User - 5/5 iterations PASSED
✅ Get Users - 5/5 iterations PASSED
✅ Create Post - 5/5 iterations PASSED
✅ Get Posts - 5/5 iterations PASSED
✅ Get Single Post - 5/5 iterations PASSED
✅ Update Post - 5/5 iterations PASSED
✅ Delete Post - 5/5 iterations PASSED
✅ Get Comments - 5/5 iterations PASSED

Total: 40/40 tests PASSED (100% success rate)
```

## 🛠️ Customization

### Using with Your Own API

1. Update the `base_url` in collection variables:

   ```json
   {
     "key": "base_url",
     "value": "https://your-api-domain.com"
   }
   ```

2. Modify endpoints in requests to match your API structure

3. Update test scripts to validate your API responses

### Adding More Test Data

Edit `test-data.json` to add more test scenarios:

```json
[
  {
    "name": "New User",
    "email": "newuser@example.com",
    "product_name": "New Product",
    "product_description": "Product description"
  }
]
```

## 📚 Learning Resources

This collection demonstrates:

- **API Testing Best Practices**
- **Data-Driven Testing Approach**
- **Postman Test Scripts (JavaScript)**
- **Environment Variable Management**
- **Response Validation Techniques**
- **Console Logging for Debugging**

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues:

1. Check the [troubleshooting guide](docs/FIXED-README.md)
2. Review the [detailed usage guide](docs/HOW-TO-USE.md)
3. Open an [issue](https://github.com/YOUR-USERNAME/postman-api-testing/issues)

## 🌟 Acknowledgments

- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for providing free testing API
- [Postman](https://www.postman.com/) for the excellent API testing platform

---

**Made with ❤️ for API Testing Learning**

⭐ If this project helped you learn API testing, please give it a star!
