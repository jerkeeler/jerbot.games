<script lang="ts">
  import Logo from '$lib/components/Logo.svelte';
  import discord from '$lib/assets/icons/discord.svg';
  import steam from '$lib/assets/icons/steam.svg';
  import twitter from '$lib/assets/icons/x_twitter.svg';
</script>

<div class="container flex items-center justify-center bg-zinc-950">
  <div class="flex flex-row justify-center text-white">
    <Logo href="https://discord.com/users/181124824435916800" src={discord} alt="Discord logo" />
    <Logo href="https://x.com/jerbot__" src={twitter} alt="Twitter logo" />
    <Logo href="https://steamcommunity.com/profiles/76561198042875546/" src={steam} alt="Steam logo" />
  </div>
</div>

<style>
  .container {
    min-height: 100vh;
    min-width: 100%;
  }
</style>
