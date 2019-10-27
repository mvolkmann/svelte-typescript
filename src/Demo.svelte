<script lang="typescript">
  export let title: string = 'untitled';

  let upperTitle: string;
  $: upperTitle = title.toUpperCase();
</script>

<style lang="scss">
  $color: red;
  div {
    color: $color;
  }
</style>

<div>Hello, {title}!</div>
