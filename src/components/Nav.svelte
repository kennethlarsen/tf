<script>
  export let segment;
</script>

<style>

</style>

<header>
  <nav>
    <ul>
      <li class="logo">
        <a
          aria-current={segment === undefined ? 'page' : undefined}
          href="."
          class={segment === undefined ? 'active' : undefined}>
          Turingfesten.
        </a>
      </li>
      <!-- <li class="menu-item">
        <a
          aria-current={segment === 'liste' ? 'page' : undefined}
          href="liste"
          class={segment === 'liste' ? 'active' : undefined}>
          læseliste
        </a>
      </li>
      <li class="menu-item">
        <a
          aria-current={segment === 'interviews' ? 'page' : undefined}
          href="interviews"
          class={segment === 'interviews' ? 'active' : undefined}>
          interviews
        </a>
      </li>
      <li>
        <a
          rel="prefetch"
          aria-current={segment === 'blog' ? 'page' : undefined}
          href="blog">
          blog
        </a>
      </li> -->

    </ul>
  </nav>
</header>
