<template>
    <v-app-bar app clipped-left dense color="primary" class="white--text">
        <!-- <v-app-bar-nav-icon> </v-app-bar-nav-icon> -->

        <!-- <v-toolbar-items class="hidden-sm-and-down ml-4">
            <v-btn class="text-capitalize" to="/forums" text dark>
                <v-icon left> fas fa-comments </v-icon> Forums
            </v-btn>

            <v-btn class="text-capitalize" to="/topic" text dark>
                <v-icon left> fas fa-store-alt </v-icon> Topic
            </v-btn>

            <v-btn class="text-capitalize" to="/posts" text dark>
                <v-icon left> fas fa-building </v-icon> Posts
            </v-btn>

            <v-btn class="text-capitalize" to="/parametres" text dark>
                <v-icon left> fas fa-cogs </v-icon> Paramètres
            </v-btn>
        </v-toolbar-items> -->

        <v-spacer />

        <UserProfile />
    </v-app-bar>
</template>

<script>
import UserProfile from './UserProfile';

export default {
    name: 'AppBar',

    components: {
        UserProfile
    }
};
</script>