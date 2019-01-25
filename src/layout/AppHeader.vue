<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <a slot="brand" class="navbar-brand mr-lg-5" href="https://demos.creative-tim.com/vue-argon-design-system/documentation">
                <img src="img/brand/Logo.fw.png">
            </a>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/Logo.fw.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a class="nav-link" href="">                                                
                        <span class="nav-link-inner--text">Inicio</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">                                                
                        <span class="nav-link-inner--text">Nosotros</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">                                                
                        <span class="nav-link-inner--text">Planes</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">                                                
                        <span class="nav-link-inner--text">Cobertura</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">                                                
                        <span class="nav-link-inner--text">Contacto</span>
                    </a>
                </li>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.facebook.com/creativetim" target="_blank"
                       data-toggle="tooltip" title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.instagram.com/creativetimofficial"
                       target="_blank" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://twitter.com/creativetim" target="_blank"
                       data-toggle="tooltip" title="Follow us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/creativetimofficial/vue-argon-design-system"
                       target="_blank" data-toggle="tooltip" title="Star us on Github">
                        <i class="fa fa-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://www.creative-tim.com/product/vue-argon-design-system" target="_blank"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-user mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">Mi cuenta</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
