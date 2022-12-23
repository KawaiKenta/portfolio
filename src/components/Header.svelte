<script>
  const scrollIntoView = ({ target }) => {
    const el = document.querySelector(target.getAttribute("href"));
    if (!el) return;
    el.scrollIntoView({
      behavior: "smooth",
    });
  };
</script>

<header>
  <div class="logo">Kawai Kenta</div>
  <nav>
    <ul>
      <li>
        <a href="#title" on:click|preventDefault={scrollIntoView}>HOME</a>
      </li>
      <li>
        <a href="#projects" on:click|preventDefault={scrollIntoView}>PROJECTS</a
        >
      </li>
      <li>
        <a href="#skills" on:click|preventDefault={scrollIntoView}>SKILLS</a>
      </li>
    </ul>
  </nav>
</header>

<style>
  header {
    width: 100%;
    box-sizing: border-box;
    background-color: rgba(0, 0, 0, 0.82);
    color: whitesmoke;
    height: 60px;
    display: flex;
    align-items: center;

    padding: 0 20px;
  }
  .logo {
    padding: 10px 20px;
    display: inline-block;
  }
  nav {
    margin-left: auto;
  }

  ul {
    display: flex;
  }

  li {
    list-style: none;
    padding: 10px 20px;
  }

  li a {
    color: inherit;
    text-decoration: none;
    cursor: default;
  }
</style>
