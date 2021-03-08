<template>
<header>
<!-- Mobile view -->
<header class="d-lg-none nav-mobile">
<nav class="navbar navbar-expand-lg navbar-light py-4">
	<div class="container">
		<a class="navbar-brand" href="#">
		</a>
		<div class="navbar-toggler custom-hamburger-btn" type="button" data-toggle="collapse"       data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
		<div class="hamburger">
		<div class="line-1"></div>
		<div class="line-2"></div>
		<div class="line-3"></div>
		</div>
		</div>
		<div class="collapse navbar-collapse" id="navbarNavDropdown">
			<ul class="navbar-nav ml-auto">
				<li class="nav-item mx-lg-3">
				<a class="nav-link active" href="index.html">Home</a>
				</li>
				<li class="nav-item mx-lg-3">
				<a class="nav-link" href="index.html#about">About</a>
				</li>
				<li class="nav-item mx-lg-3">
				<a class="nav-link" href="index.html#music">Music</a>
				</li>
				<li class="nav-item mx-lg-3">
				<a class="nav-link" href="index.html#concerts">Concerts</a>
				</li>
				<li class="nav-item mx-lg-3">
				<a class="nav-link" href="index.html#contact">Contact Us</a>
				</li>
			</ul>
		</div>
	</div>
</nav>

</header>
<!-- Desktop view -->
<header class="header sticky-top d-none d-lg-block">
<nav class="navbar navbar-expand-lg navbar-light py-4">
	<div class="container">
		<a class="navbar-brand" href="#">
		</a>
		<div class="collapse navbar-collapse" id="navbarNavDropdown">
			<ul class="navbar-nav ml-auto">
				<li class="nav-item mx-lg-3">
					<a class="nav-link active" href="#">Overview</a>
				</li>
				<li class="nav-item mx-lg-3">
					<a class="nav-link" href="index.html#about">About</a>
				</li>
				<li class="nav-item mx-lg-3">
					<a class="nav-link" href="index.html#music">Pricing</a>
				</li>
				<li class="nav-item mx-lg-3">
					<a class="nav-link" href="index.html#concerts">How it Works</a>
				</li>
				
			</ul>
		</div>
	</div>
</nav>
</header>
</header>
</template>
<script>
export default {
  name: "Navbar"
};
</script>
<style>
.header {
  /* background-color: #fff; */
  height: 88px;
  color: white;
}

.nav-mobile {
  height: 100vh;
  /* background-image: url('../images/mobile.svg'); */
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}

.header-mobile {
  color: #fff;
}

.navbar-brand img {
  max-height: 60px;
}

.navbar-light .navbar-nav .nav-link {
  color: #000;
}

.navbar-light .navbar-nav .nav-link.active {
  color: #a64253;
}

.custom-hamburger-btn {
  border: none;
}

.hamburger {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-end;
  padding-right: 2.5%;
  cursor: pointer;
}

.line-1,
.line-2,
.line-3 {
  width: 30px;
  height: 4px;
  background-color: #fff;
  margin: 2.5px 0;
  transition: 0.4s;
}

/* Toggle class to  change the state of hambuger icon cross*/
.toggle .line-1 {
  transform: translateY(12px) rotate(135deg);
}

.toggle .line-2 {
  opacity: 0;
}

.toggle .line-3 {
  transform: translateY(-6.89px) rotate(-135deg);
}
</style>


