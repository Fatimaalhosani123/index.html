<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">	
  <title>Our Menu</title>
<style>

	/********** Base styles **********/
	*{
		box-sizing: border-box;
	}
	h1 {
		margin-bottom: 15px;
	}

	p{
	border: 1px solid black;
	background-color: #A52A2A;
	width: 90%;
	height: 150px;
	margin-right: auto;
	margin-left: auto;
	font-family: Helvetico;
	color: white;
}

/* simple Responsive Framework. */
.row {
	width: 100%;
}

/********** Large devices only **********/
@media (min-width: 992px){
	.col-lg-1, .col-lg-2, .col-lg-3,{
		float: left;
		border:1px solid green;
	}
	.col-lg-1{
		width: 8.33%;
	}
	.col-lg-2{
		width: 16.66%;
	}
	.col-lg-3{
		width: 100%;
	}
}
/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px){
	.col-md-1, .col-md-2, .col-md-3,{
		float:8.33%
		border:1px solid green;
	}
	.col-md-1{
		width: 8.33%;
	}
	.col-md-2{
		width: 16.66%;
	}
	.col-md-3{
		width: 100%;
	}
}

/********** Medium devices only **********/
@media(min-width: 768px) and (max-width: 991px){
	.col-md-1, .col-md-2, .col-md-3{
		float: left;
		border: 1px solid green;
	}
	.col-md-1{
		width: 8.33%;
	}
     .col-md-2{
     	width: 16.66%;
     }
     .col-md-3{
     	width: 100%
     }
 }

</style>
</head>
<body>
 <h1>Our Menu</h1>
<div class="row">
	<div class="col-lg-3 col-md-6"><p>Sushi</p></div>
	<div class="col-lg-3 col-md-6"><p>Chicken</p></div>
	<div class="col_lg_3 col_md_6"><p>beef</p></div>
</div>

</body>
</html>
