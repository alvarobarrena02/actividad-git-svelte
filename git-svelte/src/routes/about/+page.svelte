<svelte:head>
  <title>About</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>About this app</h1>

  <p>
    This is a <a href="https://kit.svelte.dev">SvelteKit</a> app. You can make your own by typing the following into your command line and following the prompts:
  </p>

  <pre>npm create svelte@latest</pre>

  <p>
    The page you're looking at is purely static HTML, with no client-side interactivity needed.
    Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
    the devtools network panel and reloading.
  </p>

  <p>
    The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
    using it with JavaScript disabled!
  </p>

  <form class="form">
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required class="form-control">
    </div>
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required class="form-control">
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>

<style>
	/* Add your styles here */
	.text-column {
	  max-width: 600px;
	  margin: 0 auto;
	}
  
	form {
	  display: grid;
	  gap: 10px;
	  margin-top: 20px;
	}
  
	label {
	  display: block;
	}
  
	input {
	  width: 100%;
	  padding: 8px;
	  box-sizing: border-box;
	}
  
	button {
	  padding: 10px;
	  background-color: #4caf50;
	  color: #fff;
	  border: none;
	  cursor: pointer;
	}
  
	button:hover {
	  background-color: #45a049;
	}
  </style>