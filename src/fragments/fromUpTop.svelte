<script>
  const notsure: string = "I'm not sure what I'm doing"

  const logOut = (someVar): string => {
    console.log('function ran')
      return someVar
  }

const someOtherFunction = (): string => {
  console.log('some other shit')
  return 'testing'
}
</script>



    <button onClick={logOut}>Click to log out</button>
<button onClick={someOtherFunction}>Click to log out</button>
