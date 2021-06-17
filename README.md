# [File Metadata Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice)

Task Description:

Build a full stack JavaScript app that is functionally similar to this: https://file-metadata-microservice.freecodecamp.rocks/. 

HINT: You can use the multer npm package to handle file uploading.


Solution:

Using [multer](https://www.npmjs.com/package/multer) I was easily able to solve this task. A simple POST request that is handled by Multer middleware and returned an object - file metadata (name, type, size).

