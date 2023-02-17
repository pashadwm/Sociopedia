Resources:
- Relationship map: https://lucid.app/lucidchart/9a27595a-e4fb-4220-8b30-3bb1a7fed443/edit?invitationId=inv_2897ff3e-0c64-4833-8079-6cafdcc0b830&page=0_0#
- Tutorial: https://www.youtube.com/watch?v=K8YELRmUb5o&t=6965s
- Mongo: https://cloud.mongodb.com/v2/63a2c23ceb7a144c32d5d96d#/clusters
- Fonts: https://fonts.google.com/specimen/Rubik?query=rubik

Last Seen: 25.00 -> Model & DB structure
Last Seen: 41.30 -> Assets
Last Seen: 53.30 -> Authenticaton
Last Seen: 1.16.06 -> Posts
Last Seen: 1.35.35 -> Clear Backend
Last Seen: 1.41.46 -> Mulai Frontend
Last Seen: 1.49.56 -> Setup Awal
Last Seen: 2.19.39 -> Selesai theme, state, routing
Last Seen: 2.46.52 -> Selesai HomePage tapi gak tampil, jadi copas dari git banyak file

todo in terminal:
1. root -> npm init -y
2. server -> npm i -g nodemon
3. server -> npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
4. server -> nodemon
5. root -> npx create-react-app client
6. client -> npm i react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material
7. client -> npm run start

todo in mongo:
1. buat cluster
2. add ip
3. add user
4. connect app
5. paste string

optional todo in lucid:
1. + shape library
2. Entity Relationship
3. Field : Type
4. buat relation map
5. tarik perhubungan

alur:
Backend = file/folder for description = import => library
1. .env
2. index for map & base route = route, controller, middleware => express, mongoose
3. route for interface & branch route (export default router) = middleware, controller => express
4. middleware for decorator (export) {cukup sekali / opsional} =  => jsonwebtoken
5. controller for function (export) = model => bebas
6. model for create tableSchema (export default Model) =  => mongoose
7. data for dummy data (export) =  => mongoose

library digunakan:
backend
1. express = routing (maybe)
2. body-parser = process request body
3. bcrypt = password encryption
4. cors = cross-origin request
5. dotenv = environment variable
6. gridfs-stream = file upload
7. multer & multer-gridfs-storage = upload files locally
8. helmet = request safety
9. morgan = logging
10. jsonwebtoken = authentication
11. mongoose = mongodb

frontend
1. react-redux = state management tool
2. @reduxjs/toolkit = redux wrapper (for ease of use)
3. redux-persist = store state to local storage
4. react-dropzone = file upload & handling
5. dotenv = environment variable
6. formik = form handling
7. yup = validation
8. react-router-dom@6 = handling react router different route different pages
9. - material ui = templating
   + @mui/material 
   + @emotion/react 
   + @emotion/styled 
   + @mui/icons-material