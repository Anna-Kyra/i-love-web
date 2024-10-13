<footer>
    <nav>
        <ul>
            <li><a href="https://nl.linkedin.com/in/anna-kyra-strik-a87ba5204" target="_blank">LinkedIn</a></li>
            <li><a href="mailto:info@anna-kyra.nl">E-mail</a></li>
            <!-- <li><a href="/">CV</a></li> -->
        </ul>
    </nav>
    <p>Ⓒ 2024 Anna-Kyra Strik | FDND</p>
</footer>

<style>
    /******************************************************/
    /* MOBILE FIRST */
    /******************************************************/
    footer {
        --text-clr: var(--background-clr);

        width: 100%;
        /* height: 100%; */

        position: absolute;
        bottom: 0;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 2em;

        padding: 2em 3em;

        background-color: var(--primary-clr);
        color: var(--text-clr);
    }

    footer nav ul {
        display: flex;
        gap: 1em;

        list-style: none;
    }

    footer nav ul a {
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