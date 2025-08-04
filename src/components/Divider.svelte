<script lang=ts>
    let { direction = 'vertical' } = $props();

    const directionClasses: Record<string, string> = {
        vertical: 'h-full w-px mx-auto',
        horizontal: 'w-full h-px my-auto'
    }
</script>

<div class="{directionClasses[direction]} bg-white/15 dark:bg-black/15"></div>