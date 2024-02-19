<template >
    <div class="backdrop">
        <div class="modal">
           <h1>Login Form</h1>
           <div>
           <p>ENTER YOUR NAME</p>
           <input type="text" placeholder="enter your name"/>
           </div>
           <div>
           <p>ENTER YOUR PASSWORD</p>
           <input type="password" placeholder="enter your password"/>
        </div>
           <br/>
           <button>Submit</button>

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
div{
    display: flex;
    flex-direction: column;
    align-content: center;
    align-self: center;
}
</style>