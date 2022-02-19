<script>
    export let content;
    export let url;
</script>

<a href="{url}" class="flex flex-col justify-center items-center hover:scale-105 duration-300 hover:rounded-sm3 bg-light text-8xl text-text">
    {@html content}
</a>