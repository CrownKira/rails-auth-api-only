*CREATE USER
POST: http://localhost:3000/users
eg. 
{
  "email": "test@email.com",
  "password": "1234567"
}
*AUTHORISE USER
will receive a token
POST: /api/v1/auth
eg. 
{
  "email": "test@email.com",
  "password": "1234567"
}
token eg. 
{
  "token": "..."
}


include the token in the header with key name Authorization (for authentication)
*GET ALL TEMPERATURES
GET: /api/v1/temperatures
*GET MOST RECENT TEMPERATURE
GET: /api/v1/temperature
*CREATE NEW TEMPERATURE
POST: /api/v1/temperature
eg.
{
    "value": 35.5
}
