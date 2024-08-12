<!-- src/lib/components/Header.svelte -->
<header>
  <nav>
    <ul>
      <li><a href="/">홈</a></li>
      <li><a href="/about">소개</a></li>
      <li><a href="/contact">연락처</a></li>
    </ul>
  </nav>
</header>

<style>
  header {
    background-color: #f0f0f0;
    padding: 1rem;
  }

  ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    gap: 1rem;
  }

  a {
    text-decoration: none;
    color: #333;
  }
</style>