<style>

    header {
        width: 100vw;
        height: 4rem;
        background-color: #555;
        color: #fff;

        display: flex;
    }
    
    header * {
        color: #fff;
    }

    .logo {
        width: 10rem;
        flex-shrink: 1;
        height: 100%;
        object-fit: contain;
        opacity: 50% 0;
    }

    .menu {
        flex-grow: 1;
        height: 100%;
    }

    .menu ul {
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
    }

</style>

<header id="cabecera_principal">
	<img src="http://fakeimg.pl/300x100/555/fff?text=logo" alt="Logotipo" class="logo" />

	<nav class="menu">
	<ul>
		<li>
		<a href="#">
			Menú 1
		</a>
		</li>
		<li>
		<a href="#">
			Menú 2
		</a>
		</li>
		<li>
		<a href="#">
			Menú 3
		</a>
		</li>
	</ul>
	</nav>
</header>