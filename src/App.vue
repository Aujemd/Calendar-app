<template>
  <div id="app">
    <b-navbar toggleable ="md" type="dark" variant ="danger" >
      <b-container>
        <b-navbar-brand href="#">NavBar</b-navbar-brand>
        <b-navbar-toggle target="nav_collapse" />

        <b-collapse is-nav id="nav_collapse">

            <b-navbar-nav>
              <b-nav-item :to="{name: 'home'}">Home</b-nav-item>
              <b-nav-item :to="{name: 'about'}">About</b-nav-item>
            </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>




