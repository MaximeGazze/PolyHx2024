<script>
  import Card from '$lib/components/card.svelte';
  import Cardlist from '$lib/components/cardlist.svelte';
</script>

<svelte:head>
  <title>Mangeux de yop</title>
</svelte:head>

<Cardlist>
  <Card
    imgSrc="https://i0.wp.com/boingboing.net/wp-content/uploads/2024/01/image-114.png?fit=1348%2C968&ssl=1"
    imgAlt="lol">
    voici un mangeux de yop au banane aaaaaaaaaaaaaaaaa
  </Card>
  <Card
    imgSrc="https://i0.wp.com/boingboing.net/wp-content/uploads/2024/01/image-114.png?fit=1348%2C968&ssl=1"
    imgAlt="lol">
    voici un autre mangeux de yop au banane aaaaaaaaaaaaaaaaa
  </Card>
</Cardlist>
<button>es-tu un mangeux de yop?</button>

<style>
  button {
    background-color: rgb(209, 84, 84);
    padding: 0.5rem;
    margin: 0.5rem 0;
    min-width: 3rem;
    border: none;
    border-radius: 0.5rem;
    cursor: pointer;
  }
</style>
