Challenge Name:  Admin has the power 

Category: Web Security

level: easy

Challenge Description:
Challenge Link:
http://challenge13-member-26403-web.cybertalentslabs.com

Administrators only has the power to see the flag , can you be one ?


Answer:
hiadminyouhavethepower 

solution:
if we open the link we will see a simple login page looks like this

![133928337-0ec7fba6-fe61-4a4a-9b99-9d08a65152c6](https://user-images.githubusercontent.com/107189760/174202917-b03a9fb5-2c85-4dec-9e27-c88a722cc700.png)


so first we need to see the page source to see under the hood so when we look to the source code we will see that the 
developer forget to remove this comment 

![login](https://user-images.githubusercontent.com/56412281/133931984-bb0f5209-d496-43f4-95c0-6e296c79bb7c.png)


so here we have the credential so we will use it but when we use the user name and the password we got 

![support](https://user-images.githubusercontent.com/56412281/133931934-e32eabf3-f818-4a6d-b3f8-e4fe631225ff.png)


 so the server know the role of the user via cookie so if we use any extension 
 for your foverit browser or if we open the developer tool we will see that with the header they send cookei with name role
 
 ![role](https://user-images.githubusercontent.com/56412281/133931905-890dfd8a-64ca-424b-ba3e-8015ec09b69e.png)
 so we will change it to admin and save it 
 
 ![admin](https://user-images.githubusercontent.com/56412281/133931918-123a7f84-20a0-410a-ae12-80300551258f.png)
 
 
 and after that we resend it to the server and we will the get the flag 
 
 
 ![flag](https://user-images.githubusercontent.com/56412281/133931893-95cbd41a-64d5-4c7e-8922-7af4fd53eb72.png)
 
 
 and that's it have a good one until the next one
 
 
