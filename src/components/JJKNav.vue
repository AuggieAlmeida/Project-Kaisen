<template>
    <div>
        <nav class="navbar is-black" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a class="navbar-item" href="https://bulma.io">
                    <img src="../assets/logo.png" width=""
                        height="28">
                </a>

                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false"
                    data-target="navbarBasicExample">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>

            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                    <a class="navbar-item">
                        Home
                    </a>

                    <a class="navbar-item">
                        Instituição Jujutsu
                    </a>

                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">
                            Feiticeiros
                        </a>

                        <div class="navbar-dropdown">
                            <a class="navbar-item">
                                Especial
                            </a>
                            <a class="navbar-item">
                                Grau 1
                            </a>
                            <a class="navbar-item">
                                Grau 2
                            </a>
                            <a class="navbar-item">
                                Grau 3
                            </a>
                            <a class="navbar-item">
                                Grau 4
                            </a>
                            <hr class="navbar-divider">
                            <a class="navbar-item">
                                Tokyo
                            </a>
                            <a class="navbar-item">
                                Kyoto
                            </a>
                        </div>
                    </div>

                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">
                            Maldições
                        </a>

                        <div class="navbar-dropdown">
                            <a class="navbar-item">
                                Especial
                            </a>
                            <a class="navbar-item">
                                Grau 1
                            </a>
                            <a class="navbar-item">
                                Grau 2
                            </a>
                            <a class="navbar-item">
                                Grau 3
                            </a>
                            <a class="navbar-item">
                                Grau 4
                            </a>
                            <hr class="navbar-divider">
                            <a class="navbar-item">
                                Desconhecido
                            </a>
                        </div>
                    </div>
                </div>

                <div class="navbar-end">
                    <div class="navbar-item">
                        <div class="buttons">
                            <input v-model="number">
                        </div>
                    </div>
                </div>
            </div>
        </nav>

    </div>
</template>

<script type="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'JJKNav',
    data() {
        return {
        }
    },
    methods: {

    },

})
</script>

<style scoped>

</style>
