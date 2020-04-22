<template>
    <mdb-navbar color="secondary-color" dark>
        <mdb-navbar-brand href="https://mdbootstrap.com/">
            SUNSHINE TUR
        </mdb-navbar-brand>
        <mdb-navbar-toggler>
            <mdb-navbar-nav>
                <mdb-nav-item href="#" active>Acasă</mdb-nav-item>
                <mdb-nav-item href="#">Pachete</mdb-nav-item>
                <mdb-nav-item href="#">Preturi</mdb-nav-item>
            </mdb-navbar-nav>
            <form>
                <mdb-input type="text" class="text-white" placeholder="Search" aria-label="Search" label navInput waves waves-fixed/>
            </form>
        </mdb-navbar-toggler>
    </mdb-navbar>
</template>

<script>
    import { mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem, mdbInput} from 'mdbvue';
    export default {
        name: 'NavbarPage',
        components: {
            mdbNavbar,
            mdbNavbarBrand,
            mdbNavbarToggler,
            mdbNavbarNav,
            mdbNavItem,
            mdbInput
        }
    }
</script>