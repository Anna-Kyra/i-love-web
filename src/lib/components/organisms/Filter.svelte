<nav>
    <p>Filter:</p>

    <ul>
        <li><button>Alles</button></li>
        <li><button>Sveltekit</button></li>
        <li><button>Contentful</button></li>
        <li><button>Design</button></li>
    </ul>
</nav>

<style>
    nav, nav ul {
        display: flex;
        gap: .5em;
        align-items: center;
    }

    nav ul {
        list-style: none;
    }

    button {
        border-radius: 1000px;
        background-color: var(--text-50-clr);
    }
</style>
