body{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background : rebeccapurple;
}
.box{
    width: 300px;
    padding: 50px;
    position: absolute;
    top : 60%;
    left :60%;
    transform: translate(-60%,-60%);
    background : rgb(30, 182, 0);
    text-align: center;
    border-radius: .3em;
}
.box a1{
    color:aqua;
    text-transform: uppercase;
    font-weight:500;
}
.box a2{
    top: 8px;
}
.box input[type="text"],.box input[type = "password"]{
    border: 0;
    background:rgb(182, 0, 0)
    margin: 7px auto;
    padding: 9px 10px;
    width : 220px;
    outline: none;
    font-display : red;
    border-radius: .3em;
    transition: 0.5s;
}
.box input[type = "sumbit"]{
    border:0;
    background:rgb(0, 182, 70)
    display:  rgb(182, 0, 0)
    font-weight: 800;
    text-align: center;
    margin: 7px auto;
    padding: 9px 10px;
    width : 260px;
    outline: none;
    color : rgb(0 ,0 ,0 )
    border-radius: .3em;
    transition: 0.5s;
}
