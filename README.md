@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    outline: none;
    font-family: 'Inter', sans-serif;
}
body{
    background-color:rgb(0, 0, 0);
}
section, footer{
    padding: 54px 0;
}
h3{
    font-size: 50px;
}
p{
    color: rgb(11, 247, 70);
}
.container{
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 5%;
}

.btn{
    background-color: aliceblue;
    color: rgb(21, 95, 11);
    padding: 15px 20px;
    border-radius: 10px;
    cursor: pointer;
    display: inline-block;
}
.bnt:hover{
    background-color: rgb(241, 247, 247);

}
@keyframes animte-outline {
from{
    outline: 0px solid #0ea8548a;
}
to{
   outline: 15px solid #13cc2200;
}
}
header{
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 30px;
}
nav ul{
    display: flex;
    align-items: center;
}
nav ul a{
    color: rgb(98, 218, 74);
    margin: 0 25px;
    text-transform: uppercase;
    font-size: 14px;
    display: block;
}
nav ul a:not(.btn):after{
    content: "";
    background-color: rgb(73, 236, 32);
    height: 3px;
    width: 100%;
    display: block;
    margin: 0 auto;
    transition: 0.3s;
}
nav ul a:hover::after{
    width: 100%;
    color: #21a810;
}
.banner{
    display: flex;
    justify-content: center;
}
.banner .banner-text{
    margin: 150px;
    text-align: center;
    padding: 0 90px;
}
.banner .banner-text h1{
    font-size: 96px;
    color: rgb(5, 160, 18);
}
.banner .banner-text p{
    font-size: 20px;
    color: rgb(253, 253, 253);
    font-weight: lighter;
    margin: 18px 0;
}
/* faca mais */
.faca-mais .container{
    display: flex;
    align-items: flex-end;
}
.faca-mais .faca-mais-text{
    width: 50%;
    padding: 0 40px;
    color: #21a810;
}
.faca-mais .faca-mais-text h3 {
    font-size: 56px;
}
.faca-mais .faca-mais-text p{
    margin: 5px 0 10px 0;
}
.faca-mais .faca-mais-img{
    width: 50%;
}
.faca-mais .faca-mais-img img{
    width: 50%;
}
/*depoimentos*/
.depoimentos h3{
    text-align: center;
}
.depoimentos p{
    margin-bottom: 20px;
    text-align: center;
}
.cards{
    display: flex;
    justify-content: center;
}
.depoimentos .card-item{
    background-color: rgb(7, 77, 7);
    margin: 15px;
    border-radius: 14px;
    text-align: center;
    width: 350px;
    transition: 0.3s;
}
.depoimentos .card-item img{
    border-radius: 100%;
    width: 80px;
    display: block;
    margin: 10px auto;
}
.depoimentos .card-item .nome-user{
    font-weight: 600;
    font-size: 20px;
    margin-bottom: 15px;
    transition: 0.3s;
}
.depoimento .card-item .depoimento-user{
    font-size: 15px;
    padding: 0 15px;
    transition: 0.3s;
}
.depoimentos .card-item .estrelas{
    margin: 15px 0;
    border-top: 2px solid #1b5c1323;
    transition: 0.3s;
}
.depoimentos .card-item .estrelas i{
    color: #21a810;
    margin-top: 15px;
    font-size: 20px;
}
.depoimentos .card-item:hover{
    background-color: rgb(35, 136, 22);
    margin-top: -5px;
}
.depoimento .card-item:hover .nome-user,
.depoimento .card-item:hover .depoimento-user,
.depoimentos .card-item:hover .estrelas i{
    color: rgb(20, 65, 2);
}
/* colaboradores */
.colaboradores h3,
.colaboradores p{
    text-align: center;
}
.colaboradores .container div{
    display: flex;
    align-items: center;
    justify-content: space-around;
}
/* footer*/
.footer{
    background-color: forestgreen;
    text-align: center;
}
.footer i{
    color: antiquewhite;
    font-size: 19px;
    background-color: black;
    padding: 10px;
    margin: 3px;
    border-radius: 10px;
}
.footer p{
    margin-top: 10px;
    color: antiquewhite;
}
