<template>
  <div>
    <Navbar></Navbar>
    <main role="main">
      <Banner></Banner>
      <Todo></Todo>
    </main>
  </div>
</template>

<script>
/*import HelloWorld from './components/HelloWorld.vue'*/
import Navbar from "@/components/Navbar";
import Banner from "@/components/Banner";
import Todo from "@/components/Todo";
export default {
  name: 'App',
  components: {
    Todo,
    Banner,
    Navbar
  }
}
</script>

<style>
/* Make the image fully responsive */
/* Make the image fully responsive */
.carousel-inner img {
  width: 100%;
  height: 100%;
}

/**********************
/***** Services *******
/*********************/

section{
  padding: 60px 0;
}
section .section-title{
  text-align:center;
  color:#007b5e;
  margin-bottom:50px;
  text-transform:uppercase;
}
#what-we-do{
  background:#ffffff;
}
#what-we-do .card{
  padding: 1rem!important;
  border: none;
  margin-bottom:1rem;
  -webkit-transition: .5s all ease;
  -moz-transition: .5s all ease;
  transition: .5s all ease;
}
#what-we-do .card:hover{
  -webkit-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
  -moz-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
  box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}
#what-we-do .card .card-block{
  padding-left: 50px;
  position: relative;
}
#what-we-do .card .card-block a{
  color: #007b5e !important;
  font-weight:700;
  text-decoration:none;
}
#what-we-do .card .card-block a i{
  display:none;

}
#what-we-do .card:hover .card-block a i{
  display:inline-block;
  font-weight:700;

}
#what-we-do .card .card-block:before{
  font-family: FontAwesome;
  position: absolute;
  font-size: 39px;
  color: #007b5e;
  left: 0;
  -webkit-transition: -webkit-transform .2s ease-in-out;
  transition:transform .2s ease-in-out;
}


.button {
  border-radius: 4px;
  border: none;
  color: black;
  text-align: center;
  font-size: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}

.nav-link{
  color:black;
  background-color: #4D4D4D;
  margin-left: 1em;
  margin-right: 1em;
}
nav{
  background-color: #4D4D4D;

}

#topnav{
  background-color: #F8F9FA;
}
.jumbotron{
  background-image: url("http://backgroundcheckall.com/wp-content/uploads/2017/12/soothing-background-music-14.jpg") ;
  background-size: 2000px 600px;
  height: 250px;
}

.carouselsection{
  background-image: url("https://www.training.com.au/wp-content/uploads/travel-and-tourism-courses-copy.jpg");
  background-size: cover;
  height: 500px;
}



/* Footer */
@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
section {
  padding: 60px 0;
}

section .section-title {
  text-align: center;
  color: #007b5e;
  margin-bottom: 50px;
  text-transform: uppercase;
}
#footer {
  background: black !important;
  opacity: 0.7;
}
#footer h5{
  padding-left: 10px;
  border-left: 3px solid #eeeeee;
  padding-bottom: 6px;
  margin-bottom: 20px;
  color:#ffffff;
}
#footer a {
  color: #ffffff;
  text-decoration: none !important;
  background-color: transparent;
  -webkit-text-decoration-skip: objects;
}
#footer ul.social li{
  padding: 3px 0;
}
#footer ul.social li a i {
  margin-right: 5px;
  font-size:25px;
  -webkit-transition: .5s all ease;
  -moz-transition: .5s all ease;
  transition: .5s all ease;
}
#footer ul.social li:hover a i {
  font-size:30px;
  margin-top:-10px;
}
#footer ul.social li a,
#footer ul.quick-links li a{
  color:#ffffff;
}
#footer ul.social li a:hover{
  color:#eeeeee;
}
#footer ul.quick-links li{
  padding: 3px 0;
  -webkit-transition: .5s all ease;
  -moz-transition: .5s all ease;
  transition: .5s all ease;
}
#footer ul.quick-links li:hover{
  padding: 3px 0;
  margin-left:5px;
  font-weight:700;
}
#footer ul.quick-links li a i{
  margin-right: 5px;
}
#footer ul.quick-links li:hover a i {
  font-weight: 700;
}

@media (max-width:767px){
  #footer h5 {
    padding-left: 0;
    border-left: transparent;
    padding-bottom: 0px;
    margin-bottom: 10px;
  }
}
</style>
