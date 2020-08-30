<template>
<div class="text-center">
  <b-navbar toggleable="lg" type="light" variant="faded">
    <b-navbar-brand to="/">NRT</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-dropdown-item to="/intro">自己紹介</b-dropdown-item>
        <b-dropdown-item to="/intern">インターン・バイト経験</b-dropdown-item>
        <b-dropdown-item to="#">開発経験</b-dropdown-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>
</template>
