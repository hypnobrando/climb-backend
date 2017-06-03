# climb-backend

## Endpoints

### POST /save_user_info
request:  
{  
&nbsp;&nbsp;"first_name"  :   string,  
&nbsp;&nbsp;"last_name"   :   string,  
&nbsp;&nbsp;"fb_id"       :   string (optional),  
&nbsp;&nbsp;"user_id"     :   string (optional, updates the user info if supplied)  
}  

response:  
{  
&nbsp;&nbsp;"result"   :  {   "user_id"   :   string  }    
}  
