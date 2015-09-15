# Language Monster Docs

## Rest API

### user/register
**method:** POST  

**parameters:**   
{ "email": string,
  "password": string }
  
**errors:**  
420 - email already taken  
421 - wrong email format  
422 - password does not meet requirements

### user/login
**method:** POST  
    
**parameters:**  
{ "email": string, "password": string }  





