# CRUD | Create Read Update Delete | Post Get Put/Patch Delete | API Learnings

## CRUD Basic Definitions
*CRUD stands for Create, Read, Update, and Delete, which are the basic operations that can be performed on data. CRUD APIs are a set of application programming interfaces that enable developers to interact with a database or any other storage system to perform these fundamental operations. These APIs are essential for building and managing data-driven applications.*

Here's a brief overview of CRUD operations and how they relate to APIs:

- **Create (C)**:
    - **API Endpoint**: Typically uses HTTP methods like POST.
Purpose: Allows the creation of new records or entities in the database.
- **Read (R)**:
    - **API Endpoint**: Typically uses HTTP methods like GET.
    Purpose: Retrieves information from the database. It can be used to fetch a single record, a list of records, or filtered data.
- **Update (U)**:
    - **API Endpoint**: Typically uses HTTP methods like PUT or PATCH.
    Purpose: Modifies existing records in the database. PUT is often used to update an entire record, while PATCH is used for partial updates.
- **Delete (D)**:
    - **API Endpoint**: Typically uses HTTP method DELETE.
    Purpose: Removes records or entities from the database.

A simple example of how CRUD operations can be implemented using 

### **RESTful API endpoints**:

- **Create**:
```bash
POST /api/resource
```

- **Read**:
```bash
GET /api/resource
GET /api/resource/{id}
```

- **Update**:
```bash
PUT /api/resource/{id}
PATCH /api/resource/{id}
```

- **Delete**:
```bash
DELETE /api/resource/{id}
```

*Frameworks like Express (Node.js), Flask (Python), Django (Python), Spring Boot (Java), and many others provide tools and conventions for building CRUD APIs. These frameworks often use RESTful principles for designing API endpoints, making it easy to understand and work with data resources.*

