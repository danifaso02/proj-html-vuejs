<script>
import AppSectionnews from "./AppSectionnews.vue";
import AppPosts from "./AppPosts.vue";
import AppNavigation from "./AppNavigation.vue";
export default {
    name: "AppMain",
    components: {
        AppSectionnews,
        AppPosts,
        AppNavigation,
    },
};
</script>

<template>
    <div>
        <AppSectionnews />
        <AppPosts />
        <AppNavigation />
    </div>
</template>

<style scoped></style>