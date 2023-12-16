<script lang="ts">
    let number = $state(0);
</script>

<h1>Number is { number }!</h1>
<button on:click={() => number++}>Increment</button>
<button on:click={() => number--}>Decrement</button>
