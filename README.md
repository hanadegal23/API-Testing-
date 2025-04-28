# API Testing

We are going to use Postman APIs into Okta.

![image](https://github.com/user-attachments/assets/e48a1c52-5bae-4a02-ad15-fd6e89bce0ee)

Step 1. Log in to Okta Admin Console, Navigate to API under Security and select Tokens
![image](https://github.com/user-attachments/assets/1e0876b3-f58f-40d3-a940-ca78f3f37264)
Step 2. Create Token
![image](https://github.com/user-attachments/assets/df424456-1c26-4621-974e-312784fa4169)
Step 3. Name it Postman API

![image](https://github.com/user-attachments/assets/9db684bf-b914-4c4e-ac12-8628628c75bd)
The token has been created be sure to keep this token private and not public.
![API Token](https://github.com/user-attachments/assets/632bb274-362e-448b-9d07-3afa3b2d6f49)
![image](https://github.com/user-attachments/assets/7bbede79-a6ab-49c1-9355-7677f125298a)

Create all the variables within the Environment section. 
![image](https://github.com/user-attachments/assets/db132f08-6260-475a-b132-b53f5b603840)
url : this will be your Okta URL ( https://dev-<number>.okta.com ) 
apikey : this will be the API key that we created within Okta.
email-suffix : anything of your own choice
password : anything of your own choice
![image](https://github.com/user-attachments/assets/fa129bfa-fd6a-411a-a65e-2a19ffadabcb)

Now, we go to one of the request for Create User with Password & Recovery Question, and click the Send button. 
![image](https://github.com/user-attachments/assets/4736acfa-6fc3-47e0-a12e-e47695d01d91)

Now the user has been created
![image](https://github.com/user-attachments/assets/d11bd353-cbbf-40e9-93e8-5786647c5126)
