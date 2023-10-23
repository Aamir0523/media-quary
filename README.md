@media(max-width: 500px){
    /*
    phones
    */
body{
    background-color: red;
}
div::after{
    content: this is mobile cimpatable
}
}

   @media( min-width:600px){
   /* portrate table and big phone*/
   body{
    background-color: aquamarine
   ;}
   div::after{
    content: {portrate tablet and big mobiles};
   }
}
@media(min-width:768px){
    /* tablet*/
    body {
        background-color: blue;
    };
    div::after{
        content: tablets;
    }
}

div{
    text-align: center;
    font-size: x-large;
}
