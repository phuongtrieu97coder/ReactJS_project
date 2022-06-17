# 1.Purpose:

- This project is used to connect react with nodejs and mongoDB database to register user information, store data to database, and display it for users

# 2.Files is being used:

- In this project, i work with 7 files: index.html, index2.html, index3.html, nodejs_test1.js, index.js, package.json, Userdata1_mongoDB.json

# 3.Files and Folder url:

- Index.js is placed in “my-app/src/”
> Link: 
```diff
+ index.js
```
<a type="button">[index.js](./src/index.js)</a>
<br>

- Userdata1_mongoDB.json is placed in “my-app/public/mongoDB_userdata/”   
> Link: [Userdata1_mongoDB.json](./public/mongoDB_userdata/Userdata1_mongoDB.json)
<br>

- Other files are placed in “my-app/public/”
<br>
- In “my-app/public/” folder I got “image” folder contains “company1.jpg,company2.jpg,company3.jpg”
<br>


# 4.Programing languages

- HTML, CSS, jQuery, Reactjs, nodejs, JavaScript Ajax+JSON, expressJS, npm bodyParser module

# 5.Setup Proxy

##  Purpose: 
>      Connect Reactjs with NodeJS

- Please write "proxy":"http://localhost:8080" inside "package.json" file to connect reactjs to nodejs at the same proxy

- Normally you can’t run two program on the same port as localhost:8080, but you can allow ReactJS run on the same proxy with nodejs at localhost:8080

![image](https://user-images.githubusercontent.com/82598726/174354953-94cf8073-5867-4c25-bebb-c508c4911d3c.png)

<br><br><br>


# 6.Proxy Server basic concepts:

<p align="center">

<h4>
- In computer networking, a proxy server is a server application that acts as an intermediary between a client requesting a resource 
and the server providing that resource.
</h4>

<h4>
- Instead of connecting directly to a server that can fulfill a request for a resource, such as a file or web page,
  the client directs the request to the proxy server, which evaluates the request and performs the required network transactions
</h4>

</p>

<p>


<h4>  
- A proxy server is a bridge between you and the rest of the internet. Normally, when you use your browser to surf the internet,
  you connect directly to the website you’re visiting. Proxies communicate with websites on your behalf.
</h4>

<h4>
- When you use an online proxy, your browser first connects to the proxy, and the proxy forwards your traffic to the website you’re visiting. 
  That’s why proxy servers are also known as “forward proxies.” An internet proxy will also receive the website’s response and send it back to you.
</h4>


</p>

<br><br><br>


# 7.Running:

- We must create 2 terminal to run both reactjs(cd my-app => npm start) and nodejs(cd my-app => cd-public => node nodejs_test1.js) 
to work effectively with this program.


![image](https://user-images.githubusercontent.com/82598726/174353447-acf54cf6-e165-4114-8150-25cfb8602eda.png)
![image](https://user-images.githubusercontent.com/82598726/174353469-68b96c1c-5801-460a-973e-2397957ce2af.png)



<br><br><br>

- We mostly work with url 'localhost:3000'
![image](https://user-images.githubusercontent.com/82598726/174353602-76ebdcb0-fede-486b-968a-f1a8d2367ea7.png)

- If user click “sign-up”, a form will appear
![image](https://user-images.githubusercontent.com/82598726/174353694-8f94300b-1af9-48e0-a218-b2462897fa77.png)



- After user fill out information and click “register”=> a photo will appear 
 
![image](https://user-images.githubusercontent.com/82598726/174356381-06562071-62a7-44ad-b6e2-ab9d2b4ecb1a.png)


![image](https://user-images.githubusercontent.com/82598726/174356306-c2b7bda7-f2a5-4dfe-997d-508bd9a19ebd.png)

![image](https://user-images.githubusercontent.com/82598726/174356345-065e5e32-a8e5-4bd5-b00e-f02b106329ce.png)


 
- After that, page reload

- Here is what we got in the nodejs terminal
 
![image](https://user-images.githubusercontent.com/82598726/174356199-7a638a6b-af79-4143-a7b0-bf99bfe7b860.png)


- Now user go back to index.html page

- If user click “account” button =>

![image](https://user-images.githubusercontent.com/82598726/174356129-32f9585e-15ee-4eae-8248-137689c2d613.png)

 
 
![image](https://user-images.githubusercontent.com/82598726/174356096-1642c3c5-81ea-4a9d-9186-177c679a6478.png)

- These contents are from index2.html


- Now check mongoDB Atlas Database Cloud

 
![image](https://user-images.githubusercontent.com/82598726/174356025-58959285-911f-4c19-8c56-c70d4ab2a034.png)





