**WEATHER WEB APP**
=========================

**Project Overview**
--------------------

This project is a summative that would determine my understanding of APIs and how good I am at using them. I would create a weather web application to help people find the weather in any country of their choice. Just like we can find the time in different countries based on preference or location, my web app would do the same. Making use of HTML, CSS, and Javascript, I would make a visually appealing and interactive website that is easy to navigate and pleasing to view. I would also use the OpenWeatherMap API to solve the problem and give me access to the weather in different countries of the world. Although I faced some challenges with my servers and public keys, I was able to fix them and make sure the right file was being shown and traffic was being distributed evenly across both servers. I got help from classmates and watched videos to learn how to deploy a website. I had cloned my repo in /var/www/html/, where index files were located along with my repo, so when my web app was deployed, it hosted the index file from that directory instead of from my repo directory. I spotted the problem and was able to rectify it. I configured my load balancer to distribute traffic evenly across both servers and made sure they were seen by using the X-Served-By

**Technologies Used**
---------------------

The following technologies and tools were used to develop this application:

*   **HTML**: For structuring the application.
    
*   **CSS**: For designing the layout and styling.
    
*   **JavaScript**: For interactivity, API calls, and client-side logic.
    

**Features**
------------

1.  Integrates live data from multiple APIs to enrich the user experience.
    
2.  Displays user-friendly error messages in case of API failures or connectivity issues.
    
3.  Manages sensitive API keys through a config.js file that is excluded from version control.
    

**APIs Used**
-------------

1.  OpenWeather API
    
    *   Provides real-time data such as weather updates for specific locations.
        
    *   Includes current weather, forecasts, and historical data.
        

**Setup and Installation**
--------------------------

To set up and run the application locally, follow these steps:

1.  git clone [https://github.com/Emma-Asoliya/API\_SUMMATIVE.git](https://github.com/Emma-Asoliya/API_SUMMATIVE.git)
    
2.  **Install Dependencies**:This project requires no external libraries or package managers. Ensure you have a modern web browser installed.
    
3.  **Configure API Keys**:
    
    *   Create a file named config.js in the root of the project directory.
        
    *   const API\_KEY\_1 = 'your\_api\_key\_1';
        
    *   Ensure the config.js file is added to the .gitignore to prevent accidental uploads.
        

**Running the Application Locally**
-----------------------------------

1.  Open the index.html file in a web browser.
    
2.  For a better development experience, use a live server (e.g., Live Server extension in Visual Studio Code).
    

**Deploying to Web Servers**
----------------------------

### **Deploying to Custom Web Servers**

1.  Compress all project files (index.html, styles.css, config.js, etc.) into a ZIP file or use an FTP client.
    
2.  Upload the files to your web server
    
3.  Configure the server to serve the index.html file as the main page.
    

**Challenges and Solutions**
----------------------------

### **1\. Managing API Keys**

*   _Challenge_: Avoid exposing sensitive API keys in public repositories.
    
*   _Solution_: The config.js file is excluded from version control by using a .gitignore file.
    

**Acknowledgments**
-------------------

We acknowledge the contributions of the following resources and tools:

1.  **API Providers**:
    
    *   OpenWeatherAPI for reliable weather data.
        
2.  **Development Tools**:
    
    *   [Visual Studio Code](https://code.visualstudio.com/): For an efficient development environment.