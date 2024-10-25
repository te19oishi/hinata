<script>
  let name = '';
  let email = '';

  function handleSubmit() {
    // Handle form submission
  }
</script>

<form on:submit={handleSubmit}>
  <label for="name">名前:</label>
  <input type="text" id="name" bind:value={name} />

  <label for="email">メールアドレス:</label>
  <input type="email" id="email" bind:value={email} />

  <button type="submit">送信</button>
</form>
