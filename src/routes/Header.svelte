<script lang="ts">
    import { Button } from "$lib/components/ui/button";
</script>

<header class="bg-background flex items-center">
    <a class="headerBlock" href=".">MUSICTHINGY add icon</a>
    <div class="flex justify-end rightHandHeader">
        <a class="headerBlock" href=".">JUMP1</a>
        <a class="headerBlock" href=".">JUMP2</a>
        <a class="headerBlock" href=".">JUMP3</a>
    </div>
</header>

<style>
	header {
		width: 100dvw;
		height: 7dvh;
		min-height: 65px;

        border-bottom: 2px;
        border-style: solid;
        border-color: hsl(var(--primary));

        position: sticky;
        top: 0px;
	}

    .headerBlock {
        flex-grow: 3;
        user-select: none;
        color: var(--accent);
        text-decoration: none;

        width: 100%;
        height: 100%;
        padding-left: 54px;
        padding-right: 54px;

        display: flex;
        justify-content: flex-start;
        align-items: center;

        border-right: 2px;
        border-style: solid;
        border-color: hsl(var(--primary));
    }

    .headerBlock:hover {
        background: hsl(var(--secondary));
    }

    .rightHandHeader {
        flex-grow: 1;
        width: 100%;
        height: 100%;
    }

    .headerBlock:last-child {
        border: 0;
    }
</style>