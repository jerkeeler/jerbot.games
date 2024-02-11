<script lang="ts">
  export let src: string;
  export let alt: string;
  export let href: string;
</script>

<a {href} class="ml-0 ml-12 mt-3 h-12 w-12 transition-all first:ml-0 hover:scale-125">
  <img {src} {alt} height="48" width="48" />
</a>
