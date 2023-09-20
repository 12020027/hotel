*{
    margin: 0;
    padding: 0;
}

body{
    background-image: url(bed-4416515_640.jpg);
    background-size: cover;
    background-position: center;
    font-family: sans-serif;
    width:50%;
}

.form-box{
    width: 50%;
    background:black;
    background-color: transparent;
    margin: 20% 20%;
    padding: 30px 0;
    color: red;
    background-position: center;
    box-shadow: 0 0 20px 2px rgba(0,0,0,0.5);
}

h1{
    text-align: initial;
    margin-bottom: 20px; 
    color: black;
    padding-top: 30px;  
}

h2{
    text-align: initial;
    margin-bottom: 10px; 
    color: black;
    padding-top: 2px;  
}

.input-box{
    margin: 30px auto;
    width: 80%;
    border-bottom: 1px solid black;
    padding-top: 10px;
    padding-bottom: 5px;
}

.input-box input{
    border:none;
    width: 90%;
    outline:none;
    background: transparent;
    color: black;
}

#form{
    width: 500px;
    margin: 20vh auto 0 auto;
    padding: 20px;
    background-color: whitesmoke;
    border-radius: 4px;
    font-size: 12px;
}

#form h1{
    color: #0f2027;
    text-align: center;
}

#buton{
    padding: 5px;
    margin-top: 5px;
    width: 10%;
    color: white;
    background-color: transparent;
    border-radius: 4px;
}

.input-control input{
    border: 2px solid black;
    border-radius: 4px;
    display: block;
    font-size: 12px;
    padding: 10px;
    width: 100%;
    color:black;
}

.input-control input:focus{
    outline:0;
}

.input-control.success input{
    border-color: green;
}

.input-control.error input{
    border-color: red;
}

.input-control.error{
    border-color: red;
    font-size: 9px;
    height: 13px;
}

.login-btn{
    margin: 30px auto 20px;
    width:100%;
    background: buttonhighlight;
    cursor: pointer;
    padding: 10px 0;
    outline: none;
    color: black;
    font-size: 20px;
}

.input-box input[type="email"]::placeholder {
    color: black;
}

.input-box input[type="password"]::placeholder {
    color: black;
}

.form-box h2 {
    font-style: italic;
}
