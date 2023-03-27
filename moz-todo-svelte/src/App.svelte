<script>
	export let name;
</script>

<!-- 
<script lang="ts">
	import svelteLogo from './assets/svelte.svg'
	import viteLogo from '/vite.svg'
	import Counter from './lib/Counter.svelte'
</script>
 -->
<!--
  Admin/Developer
  Admin login page
  Add member page
  Add product page
  Customer product page
  Customer management page
  Customer order page
-->

<main>
	<!-- <h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->

	<nav>  
		<h1 id='company-logo'>2DArchive</h1>
		<ul id='nav-bar'>
		  <li><a href="#">Store</a></li>
		  <li>Community</li>
		  <li>About</li>
		  <li>Support</li>
		  <li>Developers</li>
		</ul>
	  </nav>
	  <section id='right-sign-in'>
		<h1>Join a million developers and publish your games today!</h1>
		<button>Sign Up</button>
		<ul>
		  <li>Username</li>
		  <input class='sign-in'>
		  <li>Email</li>
		  <input class='sign-in'>
		  <li>Password</li>
		  <input class='sign-in'>
		</ul>
	  </section>
	
	
	  <!-- <div>
		<a href="https://vitejs.dev" target="_blank" rel="noreferrer">
		  <img src={viteLogo} class="logo" alt="Vite Logo" />
		</a>
		<a href="https://svelte.dev" target="_blank" rel="noreferrer">
		  <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
		</a>
	  </div>
	  <h1>Vite + Svelte</h1>
	
	  <div class="card">
		<Counter />
	  </div>
	
	  <p>
		Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
	  </p>
	
	  <p class="read-the-docs">
		Click on the Vite and Svelte logos to learn more
	  </p> -->
</main>

<style>
	nav {
    margin: 0;
    padding: 0;
  }

  #company-logo {
    font-size: 30px;
    position: absolute;
    top: 1%;
    left: 2.5%;
  }

  button {
    font-size: 2em;
  }

  ul {
    list-style: none;
    position: relative;
  }

  #nav-bar {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  /* .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  } */

	/* main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	} */

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>