<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<style type="text/css">
	*{
		box-sizing: border-box;
		background: white;
		text-align: center;
	}
	.container{
		background: #fff;
		display: inline;
	}
	.container:hover{

	}
	.gallery{
		width: 100%;
		max-width: 350px;
		height: 650px;
		object-fit: cover;
		margin: 30px;
		padding: 1px;
		display: inline-grid;
	}
	.desc{
		padding: 15px;
		text-align: center;
	}
	.header{
		text-align: center;
		color: #fff;
		height: 60px;
		font-size: 50px;
		background-color: black;
	}
	p{
		text-align: center;
		color: #fff;
		height: 60px;
		font-size: 50px;
		background-color: black;
	}
	button{
		background-color: #156EE3;
  		border: none;
  		color: white;
  		padding: 8px 15px;
  		text-align: center;
  		text-decoration: none;
  		display: inline-block;
  		font-size: 15px;
  		margin: 4px 2px;
  		cursor: pointer;
  		float: left;
	}
	.box{
		box-shadow: 0 0 20px 2px rgba(0, 0, 0, .1);
		transition: 1s ease;
	}
	.box img{
		width: 100%;
		height: 400px;
		display: inline-grid;
		display: flex;
    	flex-direction: column;
    	flex-wrap: wrap;
    	object-fit: cover;
    	flex-wrap: wrap;
    	border-radius: 5px;
	}
	.box:hover{
		transform: scale(1.2);
		z-index: 2;
	}
	.desc{
		text-align: left;
		margin-top: 15px;
	}
	.desc1{
		text-align: left;
	}
	footer{
		text-align: center;
		color: #fff;
		height: 60px;
		font-size: 50px;
		background-color: black;
	}
</style>
<body>
	<div class="header">
		<p> CSS FLEXBOX GALLERY  </p>
	</div>

		<p class="css"> < header > </p>

<div class="container">
	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1703767574991-a35408a264ad?q=80&w=2064&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>
			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1703767574991-a35408a264ad?q=80&w=2064&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1703762855767-d3a8d554b72e?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1703762855767-d3a8d554b72e?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1535392432937-a27c36ec07b5?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1535392432937-a27c36ec07b5?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1704053339907-f2b3bfc2d349?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1704053339907-f2b3bfc2d349?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>
</div>
<div class="container">
	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1704026437274-fe4fa8af1784?q=80&w=1935&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1704026437274-fe4fa8af1784?q=80&w=1935&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1703868674842-f7a2e35b474b?q=80&w=1935&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1703868674842-f7a2e35b474b?q=80&w=1935&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1704108889314-48e5fc7b5790?q=80&w=1978&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1704108889314-48e5fc7b5790?q=80&w=1978&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1705849911044-5ea61913b445?q=80&w=1972&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1705849911044-5ea61913b445?q=80&w=1972&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>
</div>
<div class="container">
	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1630138994765-98fa6a9e633a?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1630138994765-98fa6a9e633a?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1630138996328-5db19df173c5?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1630138996328-5db19df173c5?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1706211307566-8be99af84386?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE3fHx8ZW58MHx8fHx8"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1706211307566-8be99af84386?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE3fHx8ZW58MHx8fHx8"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1705427738207-fd66f611691b?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1705427738207-fd66f611691b?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>
</div>
<div class="container">
	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1479186479563-2af7090284c6?q=80&w=2076&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1479186479563-2af7090284c6?q=80&w=2076&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1503416997304-7f8bf166c121?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1503416997304-7f8bf166c121?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1514897575457-c4db467cf78e?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1514897575457-c4db467cf78e?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1519895710315-a04b64f04a36?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1519895710315-a04b64f04a36?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>
</div>
<div class="container">
	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1706706588488-7f1ed39abe18?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxOHx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1706706588488-7f1ed39abe18?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxOHx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1706709224383-d318215e2756?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxNXx8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1706709224383-d318215e2756?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxNXx8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1706815774376-fac23b511ef5?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxM3x8fGVufDB8fHx8fA%3D%3D"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1706815774376-fac23b511ef5?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxM3x8fGVufDB8fHx8fA%3D%3D"><button class="button">Click Me!</button></a>
	</div>

	<div class="gallery">
		<div class="box"><img src="https://images.unsplash.com/photo-1706561038071-6db568890c12?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw0fHx8ZW58MHx8fHx8"></div>

			<div class="desc">Image Description</div>
			<div class="desc1">Lorem ipsum dolor sit amet consectelar adipisicing elit.</div>
			<a href="https://images.unsplash.com/photo-1706561038071-6db568890c12?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw0fHx8ZW58MHx8fHx8"><button class="button">Click Me!</button></a>
	</div>
</div>
</div>
<footer> < footer > </footer>
</body>
</html>
