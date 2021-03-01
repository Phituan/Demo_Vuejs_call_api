<template>
  <nav class="navbar navbar-expand-sm  navbar-dark ">

    <!-- Links -->
    <ul class="navbar-nav container ">
      <li class="nav-item" style="margin-left:-20px;font-size:30px">
        <a class="nav-link" href="#">MY TODO</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">HOMEPAGE</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">ABOUT US</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">SERVICES</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">CONTACTS</a>
      </li>

      <!-- Dropdown -->
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
          MORE
        </a>
        <div class="dropdown-menu">
          <a class="dropdown-item" href="#">Link 1</a>
          <a class="dropdown-item" href="#">Link 2</a>
          <a class="dropdown-item" href="#">Link 3</a>
        </div>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
name: "navbar"
}
</script>

<style scoped>

</style>
