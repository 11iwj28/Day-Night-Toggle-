 

<!DOCTYPE html>
<html>
    <head>
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
    </head>
    <body>
    <center>
        <div class="main">
            <input type="checkbox" id="toggle">
            <label for="toggle"></label>
            <div class="card">
                <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed egestas placerat nulla sit amet scelerisque. Nulla facilisi. Nullam sem ipsum, cursus at purus eget, tincidunt facilisis leo. Aliquam erat volutpat. In condimentum mi eros, quis viverra augue hendrerit a. Nullam euismod porttitor tellus at pulvinar. Nullam quis diam vitae elit finibus egestas. Nullam arcu lectus, placerat non </p>
            </div>
            <div class="card">
                <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed egestas placerat nulla sit amet scelerisque. Nulla facilisi. Nullam sem ipsum, cursus at purus eget, tincidunt facilisis leo. Aliquam erat volutpat. In condimentum mi eros, quis viverra augue hendrerit a. Nullam euismod porttitor tellus at pulvinar. Nullam quis diam vitae elit finibus egestas. Nullam arcu lectus, placerat non  .</p>
            </div>
            <div class="card">
             <p>    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed egestas placerat nulla sit amet scelerisque. Nulla facilisi. Nullam sem ipsum, cursus at purus eget, tincidunt facilisis leo. Aliquam erat volutpat. In condimentum mi eros, quis viverra augue hendrerit a. Nullam euismod porttitor tellus at pulvinar. Nullam quis diam vitae elit finibus egestas. Nullam arcu lectus, placerat non</p>
            </div>
            <div class="card">
                <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed egestas placerat nulla sit amet scelerisque. Nulla facilisi. Nullam sem ipsum, cursus at purus eget, tincidunt facilisis leo. Aliquam erat volutpat. In condimentum mi eros, quis viverra augue hendrerit a. Nullam euismod porttitor tellus at pulvinar. Nullam quis diam vitae elit finibus egestas. Nullam arcu lectus, placerat non </p>
            </div>
        </div>
        </center>
       <style>
        
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
*{
    transition:all .5s ease;
}
input{
    visibility:hidden;
}
label{
    margin:20px;
    display:inline-block ;
    height:50px;
    width:50px;
    border-radius:50%;
    box-shadow:5px 5px 5px gray;
}
label::before{
    content:"light_mode";
    font-family:"Material Icons";
    font-size:30px;
    position:relative;
    color:black;
    top:10px;
}
input:checked + label::before{
    content:"dark_mode";
    font-family:"Material Icons";
    font-size:30px;
    position:relative;
    top:10px;
    color:white;
}
.card{
    margin:20px;
    display:inline-block ;
    border:1px solid black;
    font-size:20px;
    letter-spacing:2px ;
    word-spacing:2px;
    box-shadow:5px 5px 5px gray;
    background-color:transparent;
}
input:checked ~ div{
    background:black;
    color:white;
    box-shadow:10px 10px 10px black,
               10px 10px 12px black,
               10px 10px 15px black,
               10px 10px 20px #303030;
    font-family:'Poppins',sans-serif;
    border-radius:10px;
}
input:checked + label{
      background:black;
      box-shadow:5px 5px 5px black;
      
}
     </style>
    </body>
</html>
