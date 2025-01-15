<script lang="ts">
    function increment() {
        console.log('working')
    }

    const test = () => {
        console.log('testing')
    }
  </script>
  
  <button onclick={test} class="btn">
    h1llo
  </button>

  <style>
    .btn {
        background-color: red;
        color: black;
        padding: 1rem;
        border-radius: 5px;
    }

    .btn:hover {
        cursor: pointer;
    }
  </style>