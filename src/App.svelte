<script>
  import CardBig from "./components/CardBig.svelte";
  import CardSmall from "./components/CardSmall.svelte";
</script>

<div class="grid grid-rows-4 grid-cols-4 min-h-screen gap-4 p-4 bg-dark">
  <CardSmall content='<i class="icon-linux"></i>' url="https://archlinux.org/" />
  <CardSmall content='<i class="icon-github-circled"></i>' url="https://github.com" />
  <CardSmall content='<i class="icon-stackoverflow"></i>' url="https://stackoverflow.com/" />
  <CardSmall content='<i class="icon-reddit-alien"></i>' url="https://www.reddit.com/" />
  <CardSmall content='<i class="icon-twitch"></i>' url="https://www.twitch.tv/" />
  <CardBig />
  <CardSmall content='<i class="icon-twitter"></i>' url="https://twitter.com/" />
  <CardSmall content='<i class="icon-keyboard"></i>' url="https://www.codewars.com/" />
  <CardSmall content='<i class="icon-wikipedia-w"></i>' url="https://nonsa.pl/wiki/Strona_g%C5%82%C3%B3wna" />
  <CardSmall content='<i class="icon-mail-alt"></i>' url="https://mail.google.com" />
  <CardSmall content='<i class="icon-hdd"></i>' url="https://drive.google.com" />
  <CardSmall content='<i class="icon-youtube-play"></i>' url="https://www.youtube.com/" />
  <CardSmall content='<i class="icon-calc"></i>' url="https://docs.google.com/spreadsheets/" />
</div>

<style lang="postcss" global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
