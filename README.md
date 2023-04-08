# Product 3D AI

![product3d_1](https://user-images.githubusercontent.com/81036521/230707834-2ed0b108-ac44-4d33-982f-64904a14fbf7.JPG)
#

The 3D product website is a comprehensive platform that showcases customizable 3D t-shirts with the ability to alter their logos 
and textures. Moreover, the platform offers cutting-edge AI technology that generates logos and textures tailored to your specific 
requirements, based on prompts provided by the user. The website is Developed using React, a popular JavaScript library, the 
platform boasts the integration of Three.js, a powerful 3D modeling library. Additionally, ChatGPT's DallE image generation model 
has been employed to provide users with advanced AI-generated image customization capabilities.

The 3D product website also provides users with an intuitive and user-friendly interface that facilitates easy navigation and smooth 
interaction with the platform. The website is optimized for a seamless user experience and features a responsive design that ensures 
compatibility across all devices.
#

## Installation for developement

1. Client (FrontEnd)
        
    a. Go into the client folder by running the command :
        
        cd client
    
    b. Install the packages, to install the packages run the command :
    
        npm install
     
    c. Change the link in the code in folder : 
    
        Folder Location : client > src > pages > Customizer.jsx
        
        Code change : In handleSubmit function change the link from
        
        https://product-3d-ai.onrender.com/api/v1/dalle to http://localhost:8080/ 
        
        or else the AI model with not work on your local server.
     
     d. Now Run the client (frontend), To run the frontend run the command :
     
        npm run dev
      
     e. Your client (frontend) is ready you can open your frontend from the given link in the terminal. 🎉
    
2. Server (BackEnd)

    a. Go into the server folder by running the command :
        
        cd server
    
    b. Install the packages, to install the packages run the command :
    
        npm install
        
    c. Create an .env file in the server folder, you can get the api key from the [OpenAi Official website](https://platform.openai.com/account/api-keys),
    and add the API key in the file, :
    
        OPENAI_API_KEY = YOUR_OPENAI_API_KEY
        
    d. Now Run the server (Backend), To run the frontend run the command :
     
        npm start
      
    e. Your server (Backend) is ready you can open your frontend from the given link in the terminal. 🎉
 
3. Congratulation you are all set and got to go. 🤹‍ 

#

Have Fun.😉

