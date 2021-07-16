<script></script>

<header>
  <h1>Anthony Rivas</h1>
  <nav>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/about">About</a></li>
      <li><a href="/work">Examples</a></li>
      <li><a href="/contact">Contact</a></li>
      <li><a href="/experiments">Experiments</a></li>
    </ul>
  </nav>
</header>

<style>
  header {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    padding: 0.5rem;
  }

  nav {
    flex-grow: 1;
    display: flex;
    justify-content: flex-end;
    align-items: stretch;
  }

  nav ul {
    display: flex;
    flex-flow: row wrap;
    justify-content: flex-end;
    align-items: stretch;
    gap: var(--gap);
    list-style: none;
  }

  nav li {
    display: flex;
    justify-content: center;
    align-items: stretch;
  }

  nav a {
    text-decoration: none;
    color: inherit;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 2rem;
    padding: 0 var(--padding);
    background: var(--color-primary);
    color: var(--color-white);
    border-radius: var(--radius-s);
  }
</style>