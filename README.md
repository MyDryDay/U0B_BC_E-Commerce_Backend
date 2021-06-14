# E-Commerce Backend ORM

  # Description
  To create the backend code of an e-commerce business to enable employees to view stock, add items, update items & delete items, and to enable customers to view items

  ## Contents
  Section                       | Description
  ----------------------------- | --------------------------------------------------
  [Installation](#Installation) | How To Install & Dependancies
  [Usage](#Usage)               | How To Use The Application
  [Contributing](#Contributing) | Information For Those That Wish To Contribute
  [Testing](#Testing)           | Information Regarding Tests I've Carried Out
  [Questions](#Questions)       | Contact Information For Those That Have Questions

  ## Installation
  1. Download / clone this repository. 
  2. Navigate to the root of the downloaded / cloned repository with a CLI. 
  3. Run the comman: "npm install" to install all project dependencies. 
  4. Navigate to the .env file and add your mySQL credentials.

  ### Usage
  1. Open the db directory in this repository, open the schema.sql file in mySQL Workbench and run the commands. 
  2. Navigate to the root of the downloaded / cloned repository with a CLI and enter the command: "npm run seed" to add some data to the databse. 
  3. From the root run the command: "node server.js" to start the server. 
  4. Open a programm like Insomnia or Postman that can be used to test API endpoints. 
  5. The URL you will need to use is as follows 'http://localhost:3001/api' followed by 'categories', 'products' or 'tags' depending on which endpoint you would like to test. 
  6. Fill out the request body and select which API method you would like to use. This project allows you to use 'GET', 'POST', 'PUT' and 'DELETE' methods. 

   [Creating & seeding the database, and starting the server demo: ](https://drive.google.com/file/d/1yhTE5U3mVQKGq4pDElxAViwxZWfPAriT/view?usp=sharing)  
    
   [GET all routes for categories, products & tags demo: ](https://drive.google.com/file/d/10vh5oFA87ENJrqktqMT9bAge5sPyM-Yf/view?usp=sharing)  
    
   [GET by ID routes for categories, products & tags demo: ](https://drive.google.com/file/d/1qDwzezcZRQw385mE9J14Kze1CfiGbxoW/view?usp=sharing)  
    
   [POST, PUT & DELETE routes for categories demo: ](https://drive.google.com/file/d/1C_2qdGBhmULmAFZ0JL5N_BPISAL7CcgN/view?usp=sharing)  
    
   [POST, PUT & DELETE routes for products demo: ](https://drive.google.com/file/d/1W86FYENyPp2AK38fft3zPE8vnCPRSpO0/view?usp=sharing)  
    
   [POST, PUT & DELETE routes for tagss demo: ](https://drive.google.com/file/d/19DV50cZuCQ0YlxrqEqKzgpuGPQX0iTEb/view?usp=sharing)  

  ### License ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)(https://opensource.org/licenses/MIT) 
 
  Project created using the MIT license.
  [Learn more...](https://opensource.org/licenses/MIT)

  #### Contributing
  If you would like to contribute please do.

  #### Testing
  Any testing was done via Insomnia.

  #### Questions
  GitHub: https://github.com/MyDryDay  
  LinkedIn: https://www.linkedin.com/in/george-cope-633b761bb/  
  Telegram: https://t.me/G_Cope97
