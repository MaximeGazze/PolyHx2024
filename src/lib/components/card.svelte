<script lang="ts">
  export let imgSrc: string = '';
  export let imgAlt: string = '';
</script>

<div>
  <img src={imgSrc} alt={imgAlt} />
  <p>
    <slot />
  </p>
</div>

<style>
  div {
    display: flex;
    background-color: rgb(116, 99, 99);
    align-items: center;
    padding: 0 1rem;
    gap: 1rem;
    border-radius: 0.5rem;
  }

  img {
    width: 3rem;
    height: 3rem;
    object-fit: cover;
  }

  p {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
</style>
