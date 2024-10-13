<script>
    import logo from '$lib/assets/logo.png'
</script>

<header>
    <a href="/">
        <img src="{logo}" alt="Hi, welkom bij de portfolio van Anna-Kyra Strik" height="100" width="100">
    </a>
    <nav>
        <button aria-hidden="true">
            menu
        </button>
        <ul>
            <li><a href="/projects">Projecten</a></li>
            <li><a href="/i-love-web">I love web</a></li>
            <li><a href="/about-me">Over mij</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

<style>
    /******************************************************/
    /* MOBILE FIRST */
    /******************************************************/
    header {
        width: 100%;
        height: 100%;

        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 2em;

        padding: 2em 3em;

        background-color: var(--primary-clr);
        
        position: relative;
    }

    header img {
        position: absolute;
        margin-top: -2em;
    }

    header nav {
        display: flex;
        gap: 1em;
    }

    header nav ul{
        display: flex;
        align-items: center;
        gap: 1em;

        list-style: none;
    }

    header nav ul a {
        --text-clr: var(--background-clr);

        text-decoration: none;
        text-transform: uppercase;

        color: var(--text-clr);
    }

    /******************************************************/
    /* TABLET */
    /******************************************************/

    @media (min-width:38em) {
    }

    /******************************************************/
    /* DESKTOP */
    /******************************************************/
    @media (min-width:54em) {
    }
</style>