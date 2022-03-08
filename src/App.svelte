<script>
	let firstName = '';
	let lastName = '';
	$: fullName = `${firstName} ${lastName}`;
  </script>
  
  <main>
	<input bind:value={firstName}>
	<input bind:value={lastName}>
	<div>Hello, {fullName}</div>
  </main>
  
  <style>
  </style>