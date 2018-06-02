# file-upload-with-express-multer-typescript
<!-- below repo is based on https://scotch.io/tutorials/express-file-uploads-with-multer article and repo is located at https://github.com/chybie/file-upload-express -->
step1: npm install express cors multer lokijs del --save
step2: npm install typescript @types/express @types/multer @types/lokijs @types/del --save-dev
step3: Add a typescript configuration file. i.e tsconfig.json
step4: add prestart and start scripts in package.json
Note: When we run "npm start", it will trigger prestart script first. The command "tsc" will read the tsconfig.json file and compile all typescript files to javascript in "dist" folder.
Then, we will run the compiled index file "dist/index.js".
step5: create Express server by creating index.ts file. We allow Cross-Origin Resource Sharing (CORS), set the connection port to 3000, and start the server.
