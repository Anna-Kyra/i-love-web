<header>
    <h1>
        <a href="/">
            <img src="#" alt="Hi, welkom bij de I love web van Anna-Kyra Strik" height="50" width="100">
        </a>
    </h1>
    <nav>
        <button aria-hidden="true">
            menu
        </button>
        <ul>
            <li><a href="/">Projecten</a></li>
            <li><a href="/">I love web</a></li>
            <li><a href="/">Over mij</a></li>
            <li><a href="/">Contact</a></li>
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

        padding: 1em 3em;

        background-color: teal;
    }

    header nav {
        display: flex;
        gap: 1em;
    }

    header nav ul{
        display: flex;
        gap: 1em;

        list-style: none;
    }

    header nav ul a {
        text-decoration: none;
        text-transform: uppercase;
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