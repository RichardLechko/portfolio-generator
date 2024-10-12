<script>
	import '../app.css';
</script>

<header class="bg-gray-800 text-white p-4">
	<h1 class="text-2xl">Your Portfolio</h1>
	<nav>
		<ul class="flex space-x-4">
			<li><a class="hover:text-gray-300" href="/">Home</a></li>
			<li><a class="hover:text-gray-300" href="/about">About</a></li>
			<li><a class="hover:text-gray-300" href="/projects">Projects</a></li>
			<li><a class="hover:text-gray-300" href="/contact">Contact</a></li>
		</ul>
	</nav>
</header>

<main class="p-4">
	<slot />
</main>

<footer class="bg-gray-800 text-white p-4 text-center">
	<p>© {new Date().getFullYear()} Your Name</p>
</footer>
