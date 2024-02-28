# gulzi8march
 @import url(https://fonts.googleapis.com/css?family=Poiret+One);
 body {
	 background-color: #f1afaf;
	 /* font-family: 'Poiret One', Segoe UI Light, cursive; */
	 font-family:  'Brush Script MT', cursive;
}
h1{
    font-size: 50px;
    margin-top: -20px;
    margin-bottom: 100px;
}
 #card {
	 position: absolute;
	 top: 200px;
	 width: 460px;
	 height: 360px;
	 left: 50%;
	 margin-left: -230px;
     
}
 #card .heart {
	 width: 260px;
	 height: 260px;
	 float: left;
}
 #card .heart #circle {
	 height: 130px;
	 width: 130px;
	 border-radius: 50%;
	 background-color: #d32f2f;
}
 #card .heart #rec, #card .heart #rec2 {
	 margin-top: -60px;
	 width: 130px;
	 height: 130px;
	 background-color: #d32f2f;
	 border-radius: 35% 0 0 0;
}
 #card .heart #half2 {
	 -ms-transform: rotate(-90deg);
	/* IE 9 */
	 -webkit-transform: rotate(-90deg);
	/* Chrome, Safari, Opera */
	 transform: rotate(-90deg);
	 margin-top: -330px;
	 margin-left: -200px;
}
 #card #heart2 {
	 margin-top: -60px;
	 margin-left: -130px;
}
 #card #heart2 #circle, #card #heart2 #rec {
	 background-color: #d32f2f;
}
 #card #heart2 #half2 #rec {
	 border-bottom: 1px solid #d32f2f;
	 margin-top: -61px;
}
 #card #message {
	 float: left;
	 width: 200px;
	 height: 200px;
	 margin-left: -130px;
	 background-color: #333;
	 border-radius: 35% 0 35% 0;
	 text-align: center;
}
 #card #message h2 {
	 font-size: 30px;
	 color: #e2bb0b;
	 width: 160px;
	 margin-top: 60px;
	 margin-left: 16px;
}
 #card #heart1 {
	 -webkit-transform: rotate(180deg);
	 -moz-transform: rotate(180deg);
	 -ms-transform: rotate(180deg);
	 transform: rotate(180deg);
	 -webkit-animation: closeLeft 2s ease-in-out forwards;
	 -moz-animation: closeLeft 2s ease-in-out forwards;
	 -ms-animation: closeLeft 2s ease-in-out forwards;
	 animation: closeLeft 2s ease-in-out forwards;
}
 #card #heart2 {
	 -webkit-animation: closeRight 2s ease-in-out forwards;
	 -moz-animation: closeRight 2s ease-in-out forwards;
	 -ms-animation: closeRight 2s ease-in-out forwards;
	 animation: closeRight 2s ease-in-out forwards;
}
 #card:hover #heart1 {
	 -webkit-animation: openLeft 2s ease-in-out forwards;
	 -moz-animation: openLeft 2s ease-in-out forwards;
	 -ms-animation: openLeft 2 ease-in-out forwards;
	 animation: openLeft 2s ease-in-out forwards;
}
 #card:hover #heart2 {
	 -webkit-animation: openRight 2s ease-in-out forwards;
	 -moz-animation: openRight 2s ease-in-out forwards;
	 -ms-animation: openRight 2 ease-in-out forwards;
}
 @-webkit-keyframes closeLeft {
	 from {
		 -webkit-transform: rotateY(0deg);
	}
	 to {
		 -webkit-transform: rotateY(180deg);
	}
}
 @-moz-keyframes closeLeft {
	 from {
		 -moz-transform: rotateY(0deg);
	}
	 to {
		 -moz-transform: rotateY(180deg);
	}
}
 @-ms-keyframes closeLeft {
	 from {
		 -ms-transform: rotateY(0deg);
	}
	 to {
		 -ms-transform: rotateY(180deg);
	}
}
 @keyframes closeLeft {
	 from {
		 transform: rotateY(0deg);
	}
	 to {
		 transform: rotateY(180deg);
	}
}
 @-moz-keyframes openLeft {
	 from {
		 -moz-transform: rotateY(180deg);
	}
	 to {
		 -moz-transform: rotateY(0deg);
	}
}
 @-webkit-keyframes openLeft {
	 from {
		 -webkit-transform: rotateY(180deg);
	}
	 to {
		 -webkit-transform: rotateY(0deg);
	}
}
 @-ms-keyframes openLeft {
	 from {
		 -ms-transform: rotateY(180deg);
	}
	 to {
		 -ms-transform: rotateY(0deg);
	}
}
 @keyframes openLeft {
	 from {
		 transform: rotateY(180deg);
	}
	 to {
		 transform: rotateY(0deg);
	}
}
 @-moz-keyframes openRight {
	 0% {
		 -moz-transform: rotateX(180deg);
	}
	 100% {
		 -moz-transform: rotateX(0deg) rotateZ(180deg);
	}
}
 @-webkit-keyframes openRight {
	 0% {
		 -webkit-transform: rotateX(180deg);
	}
	 100% {
		 -webkit-transform: rotateX(0deg) rotateZ(180deg);
	}
}
 @-ms-keyframes openRight {
	 0% {
		 -ms-transform: rotateX(180deg);
	}
	 100% {
		 -ms-transform: rotateX(0deg) rotateZ(180deg);
	}
}
 @keyframes openRight {
	 0% {
		 transform: rotateX(180deg);
	}
	 100% {
		 transform: rotateX(0deg) rotateZ(180deg);
	}
}
 @-webkit-keyframes closeRight {
	 from {
		 -webkit-transform: rotateX(0deg) rotate(180deg);
	}
	 to {
		 -webkit-transform: rotateX(180deg);
	}
}
 @-moz-keyframes closeRight {
	 from {
		 -moz-transform: rotateX(0deg) rotate(180deg);
	}
	 to {
		 -moz-transform: rotateX(180deg);
	}
}
 @-ms-keyframes closeRight {
	 from {
		 -ms-transform: rotateX(0deg) rotate(180deg);
	}
	 to {
		 -ms-transform: rotateX(180deg);
	}
}
 @keyframes closeRight {
	 from {
		 transform: rotateX(0deg) rotate(180deg);
	}
	 to {
		 transform: rotateX(180deg);
	}
}
 
