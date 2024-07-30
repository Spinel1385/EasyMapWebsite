# EasyMapWebsite

This repository contains code and files for publishing a Folium map as a very simple GitHub Pages site.
Steps
1. Connect to your Github space
2. Create a new repository called EasyMapWebsite with the public and readme.md options checked.
3. Setting>Pages>Build and deployment>Branch>main/(root)   --> save
4. Upload DataForTP/Logo_IUT_SD_Carcassonne.jpg et ManausMap.html
5. Créer un fichier _config.yml
    
        theme: jekyll-theme-minimal
        title: Simple Map Website
        description: This website demonstrates how to easily publish and display an interactive map made with Folium.
        logo: Logo_IUT_SD_Carcassonne.jpg
        #You can also add a logo from an image URL, logo: https://upload.wikimedia.org/wikipedia/commons/3/3f/UPVD_Logo_2023.jpg
    
6. Setting>Pages>copy the website link (similar to https://spinel1385.github.io/EasyMapWebsite/) 
    
7. Create an index.md file and fill it with the following command
   
       Easy map website
       Here s my easy map website !
       <iframe src="ManausMap.html" height="500" width="500"></iframe>
        You can explore this map at https://spinel1385.github.io/EasyMapWebsite
