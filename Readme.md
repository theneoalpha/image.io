    

  Step 1 :-Vite - Fastest way to generate frontend tool - through which we can quickly generate react(create-react-app) within a second.
          
          
          step 1.1 :

               # npm create vite@latest

          step 1.2 :      

               # npm install

  Step 2 :- make a folder "Client/src/constants/index.js" and copy the surpriseMePrompts Function - takii user agar kuch na soch paye to app apne se user ko kuch idea de khud se ,Array of 50 prompts(ideas) 
            

  Step 3 :- Adding tailwind css framework and changing some code in App.jsx,index.css and tailwind.config.js folder  

            step 3.1

               #  npm install -D tailwindcss postcss autoprefixer

            Step 3.2 installing tailwind

               #  npx tailwindcss init -p

  Step 4 :- Adding react-router-dom for page switching from one page to another page and creating two pages CreatePosts and Home     

            step 4.1 

              # npm react-router-dom          


  Step 5 : Undo 4th step and adding react-router-dom for page switching and adding some asstes(images,logo) and solving step 4 errors { previous issue- pages export default not working, FIX- Changing the CreatePosts and Home.jsx file code} 


            step 5.1 

            # npm react-router-dom      

   Step 6 : exporting CreatePost and Home.jsx through index.js file (taaki dono jsx file ek file index.js se access ho jaye), also adding routes in App.jsx (Page switching- from home and create-post page)             