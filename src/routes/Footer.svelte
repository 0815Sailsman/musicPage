<script>
import Button from "\$lib/components/ui/button/button.svelte";
</script>

<footer class="bg-background">
    <div id="scrollContainer">
        <div class="animate-infinite-scroll">
            <span>MUSICTHINGY</span>
            <span>MUSICTHINGY</span>
        </div>
        <div class="animate-infinite-scroll">
            <span>MUSICTHINGY</span>
            <span>MUSICTHINGY</span>
        </div>
    </div>
    <div class="navContainer">
        <a href=".">This</a>
        <a href=".">Is</a>
        <p>Powered by <a href="https://kit.svelte.dev">kit.svelte.dev</a></p>
        <a href=".">Legal</a>
        <a href=".">Bullshit</a>
    </div>
</footer>

<style>

    footer {
        height: 30dvh;
        min-height: 200px;
        border-top: 2px solid hsl(var(--primary));

        display: flex;
        flex-direction: column;
    }

    #scrollContainer {
        height: 20dvh;
        overflow: hidden;
        font-size: 10rem;
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
    }

    .navContainer {
        width: 100%;
        flex-grow: 1;

        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: end;

        padding-bottom: 18px;
    }

    a {
        color: hsl(var(--muted-foreground));
        text-decoration: none;
    }

    a:hover {
        color: hsl(var(--primary));
    }

    .animate-infinite-scroll {
        animation: infinite-scroll 30s linear infinite;
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
    }

    /* for Firefox */
    @-moz-keyframes my-animation {
        from { -moz-transform: translateX(0%); }
        to { -moz-transform: translateX(-100%); }
    }

    /* for Chrome */
    @-webkit-keyframes my-animation {
        from { -webkit-transform: translateX(0%); }
        to { -webkit-transform: translateX(-100%); }
    }

    @keyframes infinite-scroll {
        from {
            -moz-transform: translateX(0%);
            -webkit-transform: translateX(0%);
            transform: translateX(0%);
        }
        to {
            -moz-transform: translateX(-100%);
            -webkit-transform: translateX(-100%);
            transform: translateX(-100%);
        }
    }
</style>