#### Installation

1. Install this code on your local system
     
    1. Fork this repository (click 'Fork' button in top right corner)
    2. Clone the forked repository on your local file system
        ```
        cd /path/to/install/location
        
        git clone https://github.com/[your_username]/poster-shop.git
        ```

2. Change directory into the local clone of the repository

    ```
    cd poster-shop
    ```

3. Install dependencies

    ```
    npm install
    ```
4. Create a .env file by copying the sample 

    ```
    cp .env_sample .env

    Now edit the .env file and replace the IMGUR_CLIENT_ID with the client ID 
    ```
5. IMGUR API    
  ```
   CLIENT_ID (5cadbfaf9e1fc7b) : this optional if you have your own id use them if not you can use this 
  ```
6. Start project

    ```
    npm run start
    ```