# alx-files_manager
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.  The objective is to build a simple platform to upload and view files: 

* User authentication via a token
* List all files
* Upload a new file
* Change permission of a file
* View a file
* Generate thumbnails for images

## Files

### [0. Redis utils](./utils/redis.js)
* Create the connection to Redis
* Set the value of a key
* Get the value of a key
* Get the value of a key and delete it
