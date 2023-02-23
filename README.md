# Postman-k6
STEP 1: Export envirornmwnt.json and collection.json from your postman.                                                                                        
STEP 2: npm install -g @apideck/postman-to-k6 
STEP 3:postman-to-k6 test-api.json -e env.json -o k6-script.js      .It generates a k6-script.js file 
STEP 4:k6 run k6-script.js

