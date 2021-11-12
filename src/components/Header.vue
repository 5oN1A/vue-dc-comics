<template>
  <header>
    <div class="container d-flex">
      <img src="../assets/dc-logo.png" alt="" />
      <nav>
        <ul class="d-flex">
          <li v-for="(item, i) in navItems" :key="i" :class="i === currentActive ? 'active' : ''">
              <a :href="item.href" >{{item.title}}</a>
            </li>
          
        </ul>
      </nav>
    </div>
  </header>
</template>


<script>
export default {
  name: "Header",
  data() {
    return {
      navItems: [
        {
          title: "CHARACTERS",
          href: "#",
        },
        {
          title: "COMICS",
          href: "#",
        },
        {
          title: "MOVIES",
          href: "#",
        },
        {
          title: "TV",
          href: "#",
        },
        {
          title: "GAMES",
          href: "#",
        },
        {
          title: "COLLECTIBLES",
          href: "#",
        },
        {
          title: "VIDEOS",
          href: "#",
        },
        {
          title: "FANS",
          href: "#",
        },
        {
          title: "NEWS",
          href: "#",
        },
        {
          title: "SHOP",
          href: "#",
        },
      ],
      currentActive: 5,
    };
  },
};
</script>





