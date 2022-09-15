<script>
	import { page } from '$app/stores';
</script>

<header>
  <nav data-sveltekit-prefetch>
    <ul>
      <li class:active={$page.url.pathname === '/'}>
        <a href="/">Home</a>
      </li>

      <li class:active={$page.url.pathname === '/about'}>
        <a href="/about">About</a>
      </li>

      <li class:active={$page.url.pathname === '/todos'}>
        <a href="/todos">Todos</a>
      </li>
    </ul>
  </nav>
</header>