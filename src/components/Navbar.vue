<template>
  <div class='Navbar'>
    <b-navbar toggleable="md" type="dark" variant="info" top="fixed" :sticky="true">
        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
            <b-navbar-brand href="#" size='lg'>PetAssitant</b-navbar-brand>
            <b-collapse is-nav id="nav_collapse">
                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                        <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search"/>
                        <!--b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button-->
                    </b-nav-form>
                    <b-button variant="primary" text="Lang" size='md'>
                        Login
                    </b-button>
                    <b-button variant="danger" type="danger" size='md' text="Lang">
                        Sign Up
                    </b-button>
                </b-navbar-nav>
            </b-collapse>
    </b-navbar>
  </div>
</template>
