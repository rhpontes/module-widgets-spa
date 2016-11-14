# module-widgets-spa
version module widgets application

## Dependencies
* npm ^2.14   
* nodejs ^4.2        

## Configurations
* File /app/modules/comunication/comunication.config.js 
    * You may to config your comunication either local or remote    
      * Remote    
          var urlBaseUsers = 'http://spa.tglrw.com:4000/users';    
          var urlBaseWidgets = 'http://spa.tglrw.com:4000/widgets';    
      * Local   
          var urlBaseUsers = 'http://localhost:3001/users';    
          var urlBaseWidgets = 'http://localhost:3001/widgets';    
      
* By default is Remote

## Intructions
1. Clone the repository
2. Install dependencies with npm install    
>npm install
3. Run the application
>node app.js
4. The server will start at port 3000
