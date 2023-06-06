Here, we use Mongoose as the ODM (Object Data Modeling) library for MongoDB. We define a Blog model using the blogSchema and set up the necessary routes for each CRUD operation.

- The POST /blogs endpoint allows users to create a new blog post by sending a JSON payload with title and content properties.
- The GET /blogs endpoint retrieves all blog posts.
- The GET /blogs/:id endpoint retrieves a single blog post by its ID.
- The PUT /blogs/:id endpoint updates a blog post by its ID, with the new title and content provided in the request body.
- The DELETE /blogs/:id endpoint deletes a blog post by its ID.