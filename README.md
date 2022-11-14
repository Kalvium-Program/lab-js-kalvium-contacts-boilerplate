![Logo-nav](https://user-images.githubusercontent.com/109285740/201720547-c8c7344e-5779-4fcd-8521-2becf59ac805.png)


# Kalvium Lab | JS | Kalvium-CONTACTS

We have learned promise works in JavaScript. Now lets work with our promise lab, applying all of the concepts we have just learned.

### Progression 1: PROMISE ME
Create a promise call which fetches data from (https://jsonplaceholder.typicode.com/users). When the promise gets resolved display the data in browser console.

<!-- ![](https://i1.faceprep.in/ProGrad/contact-1.png)
 -->
<img width="1509" alt="Screenshot 2022-11-14 at 10 28 48 PM" src="https://user-images.githubusercontent.com/109285740/201720838-62bbef33-c218-44d3-b965-0607c5194791.png">


### Progression 2: SHOW MY PROMISE
Once the promise gets resolved, Display it in the form of list as shown in the output.
Use the code snippet below for reference
```
var player='<h2>Lists of Users</h2>';
                    result.forEach(function(user) {
                     player+=
                    `<div class="player">
                      <div class="strength">Name : ${user.name}</div>
                      <div>Email   : ${user.email}</div>
                      <div>Phone   : ${user.phone}</div>
                      <div>Website : ${user.website}</div>
                      <div>Company : ${user.company.name}</div>
                      <div>City    : ${user.address.city}</div>
                      <div>Zipcode : ${user.address.zipcode}</div>
                     </div>`
```
<!-- ![](https://i1.faceprep.in/ProGrad/contact-2.png) -->

<img width="1511" alt="Screenshot 2022-11-14 at 10 29 05 PM" src="https://user-images.githubusercontent.com/109285740/201720919-01e21409-d5fa-4cff-8533-629310da2554.png">


### Progression 3: REJECT ME
When the promise call is rejected then throw an error.

```
(error) => {
    console.log('Promise rejected.');
    console.log(error.message);
  });
```

Happy Coding Kalvium❤️
