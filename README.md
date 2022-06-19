## WORDPRESS HA (High Availbility)

This code to setup Wordpress for High Availbility, with:
  - 2 Wordpress with Master and Slave
  - 1 Database server
  
To running code, u can:  
  1. Pull Code
  2. Copy .env.example to .env for own credentials
     ```bash
     cp .env.example .env
     ```

  3. Running wordpress service
     ```bash
     docker-compose up -d
     ```    

  4. Stopping wordpress service
     ```bash
     docker-compose down
     ```  
     
 ## References
  - https://github.com/icheko/wordpress-ha
