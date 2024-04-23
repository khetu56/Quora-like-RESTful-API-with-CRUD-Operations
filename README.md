# Features:
Unique Post IDs: Each post is assigned a unique identifier, ensuring efficient retrieval and management of posts.<br>
Create Posts: Users can create new posts by submitting relevant information such as title, content, and author details.<br>
Read Posts: Retrieve posts individually by their unique IDs or fetch all posts to view the entire collection.<br>
Update Posts: Modify existing posts by updating their title, content, or any other relevant information.<br>
Delete Posts: Remove unwanted posts from the database, maintaining data integrity and cleanliness.<br>
Error Handling: Robust error handling ensures smooth interaction with the API, providing informative messages in case of invalid requests or server errors.

# Technologies Used:
Node.js: Utilized as the runtime environment for running JavaScript server-side code.<br>
Express.js: Framework for building robust and scalable web applications and APIs.<br>


# Endpoints:
GET /posts: Retrieve all posts.<br>
GET /posts/:postId: Retrieve a specific post by its unique ID.<br>
POST /posts: Create a new post.<br>
PUT /posts/:postId: Update an existing post by its unique ID.<br>
DELETE /posts/:postId: Delete a post by its unique ID.
