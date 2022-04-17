# How-to-Debug-JavaScript-in-VS-Code---No-Extension-Required
Follow these steps to set-up :
- Open VS Code
 
 ![Code_I3SE1b78ml](https://user-images.githubusercontent.com/59534048/163707980-af869e22-df8f-4899-aeec-cb33f4e46e9e.png)


- Click on the run and debug icon on the left side of your VS Code

![Pv8ZbrUkpK](https://user-images.githubusercontent.com/59534048/163708027-b7dfc422-8556-453c-b5ce-573da53f1a7c.png)


- Add/Create a json file. click on the link to add configuration

![Code_iOVM7JqLud](https://user-images.githubusercontent.com/59534048/163708156-c31a471b-6750-4a0b-a4d5-d1d367463c00.png)

- Add the configaration below to your project.
    
    // Use IntelliSense to learn about possible attributes.
    
    // Hover to view descriptions of existing attributes.
    
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    
    "version": "0.2.0",
    "configurations": [
    
        {
            "type": "chrome",
            "request": "launch",
            "name": "Launch Chrome against localhost",
            "url": "http://localhost:5500",
            "webRoot": "${workspaceFolder}"
        }
    ]
}


- A file launch.json will appear VS Code folder which is now the configuration for the app you're working on.

![Code_hUxXVu2X6X](https://user-images.githubusercontent.com/59534048/163708278-7d1b3668-9ece-45e3-9d2a-819b406b05f9.png)

- Save it (press Ctrl+S) and press the play button in the top left. This will set up debugging and launch the application/ page on Chrome Browser at port 5500.

 ![Code_Vt8LkohMLO](https://user-images.githubusercontent.com/59534048/163708395-f4513858-5655-4634-9710-0ae64b78bcc8.png)





Key points: 
  1. Have your application running in a local-server. Helps us use the live server extention
  2. Click go live  to start your application on port 5500. This will be a live reloading server.

   ![WJQsvz5AhW](https://user-images.githubusercontent.com/59534048/163708559-874466af-a4ab-4206-adf1-a270edb9ba77.png)

  4. Note that you can change the ports to your desired config.
  5. Thank You for checking and Have a good time coding.

   
