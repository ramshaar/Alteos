# Alteos
Tasks including the following steps:

POST /api/jsonBlob (for creating).
GET /api/jsonBlob/<blobId> (to fetch the post).
Inorder to verify the blog post is created, there are automated test cases written in the GET Request. 
PUT /api/jsonBlob/<blobId> (to update the blog post)
Inorder to validate the blog post is updated, there are automated test cases written in the GET Request.
DELETE /api/jsonBlob/<blobId> (using ID)
to verify that the blog post is deleted successfully, send the GET request again with the ID and you will get 404 (NOT FOUND). 

*Where <blobId> is the last part of the URL path returned from the POST request. The URL can be found through the 'Location' in the Header of POST Response.
