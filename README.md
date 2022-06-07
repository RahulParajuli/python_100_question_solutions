<h1> How to use the service</h1>
<p> 1. Install Docker. </p>
<p> 2. Clone the repository.<br> use: git clone --branch staging https://gitlab.com/eydean/gruntworks/Bookgara.git </p>
<p> 3. Open terminal on linux/Mac or CMD on Windows. </p>
<p> 4. cd to the cloned folder. </p>
<p> 5. Run command: docker-compose build</p>
<p> 6. Run command: docker-compose up</p>
<p> 7. Check if the server is running or not. </p>
<p> 8. If the server is running healthy without any errors you can use all the services available. </p>

<h1> Use Postman </h1>
<h2> To check User</h2>
<P>Visit URL POST https://localhost:4000/login</p>
<p> Pass email and password in body as json. </p>

<h2> To check services </h2>
<P>Visit URL GET https://localhost:8000/services</p>

<h2> To create orders </h2>
<P> Visit URL POST https://localhost:6000/book/<"service_id"> </p>
<p> Pass auth-token in header as json. </p>
<p> Also pass name, email, phone and lcoation in body as json. </p>
