A simple spinner with design based on the Equinor logo

![alt text](https://github.com/Statoil/css-equinor-spinner/blob/master/equinor-spinner/images/original/equinor-spinner-250px.png)

example implementation (250px spinner):

.animation {

	width: 250px;
	
	height: 250px;
	
	background: url('./images/original/equinor-spinner-250px.png') center;
	
	animation: spinner 0.6s steps(12) infinite;
	
	-webkit-animation: spinner 0.6s steps(12) infinite;
	
}

@keyframes spinner {

	0% { background-position: -3000px;}
	
	100% { background-position: 0; }
	
}

@-webkit-keyframes spinner {

	0% { background-position: -3000px;}
	
	100% { background-position: 0; }
	
}

