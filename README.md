# myProfile

# sass
$mybg: red;
$mybg2: green;
body{
  background-color: $mybg;
}
div{
  $mybg: blue;
  color: $mybg;
}
header{
  $mybg2: lime !global;
}

section{
  background-color: $mybg2;
}

.myNav{
  ul{
    color: $mybg;
  }
  ul li{
    display: inline;
  }
}
article{
  margin: {
    left: 20px;
    right: 10px;
    top: 5px;
    bottom: 15px;
  }  
}

