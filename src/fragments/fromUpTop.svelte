<script>

  const test = () => {
      return 'testing'
  }

  

const someOtherFunction = () => {
  console.log('some other shit')
  return 'testing'
}
</script>



    <button on:click={test}>Click to log out</button>
    <button on:click={someOtherFunction}>Click to log out</button>
