This API is being built to create a more convenient system for Universities and High Schools to run their class systems off of, as well as information access necessary for students and school staff and faculty.

# USERS

### User Registration
#### /users POST
###### Required Params

* user: {email:email, password:password}
```
{
  "user": {
    "email": "a@a.com",
    "authentication_token": "eP_gB_eG8BKqSTMsoDeH"
  }
}
```

### User Sign-in
#### /users/sign_in POST
###### Required Params

* user: {email:email, password:password}
```
{
  "user": {
    "email": "a@a.com",
    "authentication_token": "eP_gB_eG8BKqSTMsoDeH"
  }
}
```