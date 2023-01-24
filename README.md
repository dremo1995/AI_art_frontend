# Artist AI (Frontend)

### Description

This project is a simple image generation app that users will be able to generate a randome image based on a description that is provided and has the option to share the image with other users.

### Technologies/Tools Used

- JavaScript
- React
- TailwindCSS
- Vite
- File-Saver


### How It Works

Users will go the URL (https://artist-ai.netlify.app/) and be taken to the homepage where, if there are any, images of other users will show here and you are able to explore other AI generated images and see who created it and what prompt was used to create it.

The user can then Create their own image by clicking on the "Create" button on the top right. This will take the user to the Create Image Page that has a text fields that for the User name and the prompt. If the user needs some inspiration, the "Surprise Me" button next to the Prompt label will randomly generate a phrase that has been precompiled in a json file. Once the user fills both the name and prompt fields they can click the Generate image at which point we use the Open AI API to generate an image and the OpenAI responds with the image to displays it on the page. Once the image is available the use will be able to share it to be displayed on the Home Page. When the Share button is clicked, the image is stored on Cloudinary(cloud based asset storage platform) and the Json data is stored in MongoDB. 

To view the Backend source plase follow this link (https://github.com/dremo1995/AI_art_backend)
