[styles.css](https://github.com/user-attachments/files/27874786/styles.css)
h1 {

color: rgb(0, 0, 0);
font-size: 40px;
background-color: hsl(350, 56%, 85%);


}   
h5{
    font-size: 25px;
    color: rgb(0, 0, 0);
    background-color: hsl(350, 56%, 85%);
    text-align: left;
}


#imagen_fundas{

    border-color: black;
    border: 2px solid hsl(0, 0%, 0%);
    border-radius: 5px;
    
}

.caja_imagenes {
    text-align: center;

}

h3{
    font-size: 25px;
    background-color: hsl(350, 56%, 85%);
    color: hsl(0, 0%, 0%);
}


.caja img{
    width: 100%;
    border-radius: 5px;

}


.caja{

    background-color: hsl(350, 56%, 85%);
    border: 2px solid black;
    width: 150px;
    height: 200px; 
    border-radius: 10px;
    padding: 30px;
    padding-top: 5px;
    margin: 10px; 
    text-align: center;

}


.botton{
    background-color: hsl(350, 56%, 85%);
    color: hsl(0, 0%, 100%);
    border: 2px solid black;
    border-radius: 5px;
    padding: 10px;
    margin-top: 10px;
}


p{
    font-size: 25px;
    color: rgb(0, 0, 0);
}

li{
    font-size: 25px;
    color: rgb(0, 0, 0);
    text-align: left;
}

h4{
    font-size: 30px;
    color: rgb(0, 0, 0);
    background-color: hsl(350, 56%, 85%);
}


body{

    background: linear-gradient(to right, rgb(239, 202, 234), rgb(239, 202, 234));
    margin: 20px;
    font-family: "Montserrat", system-ui;
}

.contenedor_cajas{

    background-color: hsl(350, 56%, 85%);
    border-radius: 10px;
    
    /* -------------------------------------------------- */
    
    display: flex;
    justify-content: space-around; /*<---------- alineacion horizontal */
    flex-wrap: wrap;


    /* -------------------------------------------------- */

    padding: 25px;
    margin-top: 30px;
    gap: 15px;
    
    /* -------------------------------------------------- */
}


.caja{

    background-color: hsl(350, 56%, 85%);
    border-radius: 20px;

    /* -------------------------------------------------- */

    padding: 20px;
    padding-bottom: 50px;
    display: flex;
    flex-direction: column;
    align-items: center; /* <--------- alineacion vertical */

    /* -------------------------------------------------- */

    box-shadow: 10px 10px 30px;
}

.caja img{
    width: 100%;
    height: 80%;
    border-radius: 50px;
    border: hsl(350, 56%, 85%) solid;
}


header{
    background-color: hsl(350, 56%, 85%);
    border-radius: 30px;

    display: flex;
    justify-content: space-around;
    align-items: center;

}


header img{

    border-radius: 400px;
    height: 120px;
    width: 120px;
    box-shadow: 5px 5px 10px;
    border: rgb(227, 177, 177) solid;

}


header h1{

    color: rgb(12, 12, 44);
    font-size: 40px;
    text-align: center;
    letter-spacing: 5px;

}


nav ul{
    display: flex;
    gap: 35px;
    list-style: none; 
    padding: 40px;
    
}


nav ul li a{
    text-decoration: none;
    font-size: 20px;
}


.hero{

    min-height: 100px;

    /* -------------------------------------------------- */

    background-image: url(Fondo.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

    border-radius: 30px;

}


.hero h2{

    color: rgb(0, 0, 0);
    font-size: 50px;
    letter-spacing: 10px;
    text-align: center;
    padding-top: 10px;
}


.hero_texto{
    background-color: rgb(238, 203, 203);
    font-size: 30px;
    display: flex;
    flex-direction: column;
    padding: 30px;
    column-gap: 20px;
}


.hero_texto p{

    color: rgb(0, 0, 0);
    font-size: 20px;
    text-align: center;
}


footer{
    background-color: hsl(350, 56%, 85%);
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    margin-top: 30px;
    font-size: 40px;
}
