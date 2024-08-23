<script>
   function showMsg() {
     alert("You clicked the button?");
   }
</script>

<h1> This is the html part </h1>
<button on:click={showMsg} > 
  Message
</button>

<style>
  h1 {
    margin: 32px;
  }

  button {
    background-color: cyan;
    color: red;
    margin: 32px;
    padding: 8px 16px;
  }
</style>