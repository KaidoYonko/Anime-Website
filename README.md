# Anime-Website
@import url('https://fonts.googleapis.com/css2?family=Protest+Revolution&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
/* :root{
    
} */
html,
body{
    line-height: 1.4;
}
header{
    position: sticky;
    top: 0;
    z-index: 50;
}
.navigation{
    display: flex;
    justify-content: space-between  ;
    align-items: center;
    /* padding: 5px 10px; */
    background: #260505;
    color: red;
    font-family: sans-serif;
}
.logo img{
    width: 100px;
    height: 70px;
}
.search-nav{
    font-size: 20px;
    display: flex;
    gap: 10px;
    align-items: center;
    margin-right: 20px;
}
.search-nav input{
    padding: 5px 10px;
    width: 20rem;
    height: 2rem;
    border-radius: 50px;
    font-size: 15px;
    transition: 0.3s ease-in;
    outline: #260505;
}
/* .search-nav input:hover{
    outline: #260505;
    transition: 0.3s ease-out;
} */
.search-nav button{
    padding: 8px;
    background: #501313ab;
    color: red;
    border: none;
    font-size: 20px;
    border-radius: 50%;
    transition: 0.3s ease-in-out;
}
.search-nav button:hover{
    cursor: default;
    transition: 0.3s ease-in-out;
    opacity: 0.7;
    background-color: red;
    color: #000;
    transform: scale(1.05);
}
.navigation ul {
    /* margin-right: 20px; */
    display: flex;
    gap: 30px;
    align-items: center;
    list-style: none;
}
.navigation ul li{
    font-size: 20px;
    transition: 0.2s ease-in;
    display: flex;
    align-items: center;
    gap:5px;
    padding:  0 10px;
    height: 75px;
    font-family: "Protest Revolution", sans-serif;
}
.navigation ul li:hover{
    /* color: #fff ; */
    cursor: default;
    transform:scale(1.05);
    transition: 0.2s ease-in;
}
.navigation ul li i{
    font-size: 15px;
    padding: 3px;
    /* border-radius: 5px;
    transition: 0.2s ease-out; */
}
/* .navigation ul li i:hover{
    transition: 0.2s ease-out;
} */

/* HERO SECTION */

/* .container{
    background-color: rgb(55, 55, 55);   
} */
/* body{
     background-color: #000; 
} */
.latest-img-container{
    display: grid;
    grid-template-columns: auto auto auto auto auto;
    
}
.latest-img{
    /* max-width: 1000px; */
    margin: 20px auto;
    border: 5px solid rgb(82, 1, 1);
    overflow: hidden;
}
.latest-img img{
    width: 18vw;
    height: 100%;
    transition: 0.2s ease-in-out;
}
.latest-img img:hover{
    transform: scale(1.05);
    transition: 0.2s ease-in-out;
    cursor: default;
    opacity: 0.5;
}
.content-img{
    display: flex;
    flex-direction: column;
    gap: 20px;
}
.img-content{
    display: flex;
    flex-direction: column;
    gap: 10px;
    text-align: center;
}
.img-content:hover{
    cursor: default;
    color: rgb(160, 158, 158);
}
.date-time{
   text-align: center;
}
.date-time:hover{
    color: rgb(160, 158, 158);
    cursor: default;
}
.img-content h3{
    /* text-align: center; */
    font-weight: 20rem;
    margin-bottom: 20px;
}
.img-content :hover{
    color: rgb(160, 158, 158);
    cursor:default;
}
body{
    background: rgb(23, 23, 23);
}
.container{
    background: rgb(15, 15, 15) ;
    margin: 5px;
    color: rgb(69, 69, 69);
}
.h1{
    padding-top: 20px;
    padding-left: 20px;
    font-family: "Protest Revolution", sans-serif;
}
.h1:hover{
    color: rgb(160, 158, 158);
    cursor: default;
}
footer{
    background: #000;
    color: red;
}
.upper{
    text-align: center;
    padding: 20px;
    font-size: 20px;
}
.lower ul{
    display: flex;
    gap: 10px;
    list-style: none;
    padding: 30px;
    align-items: center;
    justify-content: center;
    color: red;
}
hr{
    border: 0.5px solid rgb(63, 63, 63);
}
.lower ul li{
    font-size: 20px;
    padding: 2px 10px;
}
.lower ul li:hover{
    background-color: red;
    color: black ;
    cursor: pointer;
}
.no-hover :hover{
    background-color: black;
}
@media (max-width:500px) {
    
}
