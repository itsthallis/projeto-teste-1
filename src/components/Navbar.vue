<template>
    <div>
        <b-navbar toggleable="lg" type="light" variant="white" class="shadow-sm">
            <b-navbar-brand><img height="36px" src="../assets/logo.png">
                <span class="ml-1">Projetinho Vue</span>
            </b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
                <b-nav-form>
                <b-button size="sm" class="my-2 my-sm-0 bg-info border-0" type="submit"><b-icon-search></b-icon-search></b-button>
                <b-form-input size="sm" class="ml-sm-2" placeholder=""></b-form-input>
                </b-nav-form>
            </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>

<script>

export default {
  name: 'Navbar'
}
</script>

<style>

</style>