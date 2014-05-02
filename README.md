API
---
GET **/api/:user_id/list**  
NO params  
return :  
[{
"id": 3,
"content": "kill a dog.",
"done": 0,
"user_id": 1
}]

---
POST **/api/:user_id/create**  
params  { content : string}  
return :  
{ todo_id : string }

---
DELETE **/api/destroy/:id**  
NO params  
return done  or  fail

---
PUT **/api/update/:id**
params  { content : string }  
return done  or  fail


---
POST**/api/login**  
params  { username : string, password : string }    
return { user_id } or fail  

---
POST**/api/signup**  
params  { username : string, password : string }    
return { user_id } or fail 