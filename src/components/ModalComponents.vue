<template >
    <div class="backdrop">
        <div class="modal">
           <h1 class="head1">Login Form</h1>
           
           <p class="para1">ENTER YOUR NAME</p>
           <input type="text" placeholder="enter your name"/>
           
           
           <p class="para1">ENTER YOUR PASSWORD</p>
           <input type="password" placeholder="enter your password"/>
        
           <br/>
           <button class="btn">Submit</button>
           <p class="para1">Developed by using Vue.js and Visual studio Code</p>
           <div>
           <img src="https://miro.medium.com/v2/resize:fit:900/1*OrjCKmou1jT4It5so5gvOA.jpeg" class="img"/>
           <img src="https://static1.xdaimages.com/wordpress/wp-content/uploads/2022/09/Visual-Studio-Code-featured-2.jpg" class="img"/>
           
        </div>
      </div>
    </div>
    
</template>

<style>
h1{
    color:black;
    font-weight: 700;
}
button{
    margin:5px;
}

.modal{
    background-image: url('https://w0.peakpx.com/wallpaper/410/412/HD-wallpaper-plain-black-black.jpg');
    height:100vh;
    background-size: cover;
}
.head1{
    color:white;
    font-size: 24px;
    font-weight:900;
}

.para1{
    color:white;
    font-size: 20px;
    font-weight:300;
}
.img{
    height:200px;
    width:200px;
    margin:5px;
    border-radius:10px;
}
.btn{
    padding:5px;
    border-radius:5px;
}
</style>