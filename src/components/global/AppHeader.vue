<template>
    <div id="header">
        <div class="logo">
            Adam Vue
        </div>
        <ul id="nav">
            <router-link to="/" tag="li"><a>Home</a></router-link> |
            <router-link to="/about" tag="li"><a>About</a></router-link> |
            <router-link to="/help" tag="li"><a>Help</a></router-link>
        </ul>
    </div>
</template>
<script>
export default {
    name: "AppHeader"
};
</script>
