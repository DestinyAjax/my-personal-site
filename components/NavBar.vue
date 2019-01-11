<template>
  <header class="masthead mb-auto">
    <div class="inner">
      <h3 class="masthead-brand">Ajax</h3>
      <nav class="nav nav-masthead justify-content-center">
        <a class="nav-link active" href="#">Home</a>
        <a class="nav-link" href="#">About</a>
        <a class="nav-link" href="#">Work</a>
        <a class="nav-link" href="#">Blog</a>
        <a class="nav-link" href="#">Contact</a>
      </nav>
    </div>
  </header>
</template>

<style>
.masthead {
  margin-bottom: 2rem;
}

.masthead-brand {
  margin-bottom: 0;
}

.nav-masthead .nav-link {
  padding: 0.25rem 0;
  /* font-weight: 700; */
  color: rgba(0, 0, 0, 0.541);
  background-color: transparent;
  border-bottom: 0.25rem solid transparent;
}

.nav-masthead .nav-link:hover,
.nav-masthead .nav-link:focus {
  color: #c70039;
}

.nav-masthead .nav-link + .nav-link {
  margin-left: 30px;
}

.nav-masthead .active {
  background-color: #c70039;
  color: white;
  padding: 5px;
  border-radius: 5px;
}

@media (min-width: 48em) {
  .masthead-brand {
    float: left;
  }
  .nav-masthead {
    float: right;
  }
}
</style>
