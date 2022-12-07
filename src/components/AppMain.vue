<script>
import AppSectionnews from "./AppSectionnews.vue";
import AppPosts from "./AppPosts.vue";
import AppNavigation from "./AppNavigation.vue";
import AppPrincipal from "./AppPrincipal.vue";

export default {
    name: "AppMain",
    components: {
        AppSectionnews,
        AppPosts,
        AppNavigation,
        AppPrincipal,
    },
};
</script>

<template>
    <div>
        <AppSectionnews />
        <AppPosts />
        <AppNavigation />
        <AppPrincipal />
    </div>
</template>

<style scoped></style>