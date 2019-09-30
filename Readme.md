For auto authentication 

1. create hoc component which takes arguments ( component , reload(true||false) ) and 
2. make /api/auth call which check user is login or not if login then stay login otherwise redirect to login page 
3. use this hoc in route.js for apply auth for perticuler components 


server : package.json


npm install --save bcrypt@1.0.3 
                   concurrently@3.5.1
                   cookie-parser@1.4.3
                   express@4.16.2
                   hogan@1.0.2
                   jsonwebtoken@8.0.1
                   moment-js@1.1.15
                   mongoose@4.10.8
                   nodemailer@6.3.0
                   modemailer-smtp-transport@2.7.4
                   redux-form@8.2.6
                   redux-thunk@2.3.0 

frontend : package.json

npm install --save @material-ui/core@4.4.3
                    axios@0.19.0
                    http-proxy-middleware@0.19.1
                    moment-js@1.1.15
                    react-fontawesome@1.6.1
                    react-redux@7.1.1
                    react-router-dom@5.1.0
                    react-simple-sidenav@1.0.1
                    redux@4.0.4
                    redux-form@8.2.6
                    redux-promise@0.6.0
                    redux-thunk@2.2.0


                    