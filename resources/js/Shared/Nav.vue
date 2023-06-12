<template>
    <nav class="mt-6">
        <ul class="list-disc">
            <li>
                <NavLink href="/" :active="$page.component === 'Home'"
                    >Home</NavLink
                >
            </li>
            <li>
                <NavLink href="/" :active="$page.component === 'Users'"
                    >Users</NavLink
                >
            </li>
            <li>
                <NavLink href="/" :active="$page.component === 'Settings'"
                    >Settings</NavLink
                >
            </li>
        </ul>
    </nav>
    <ButtonCounter />
</template>

<script>
import NavLink from "./NavLink.vue";

export default {
    components: { NavLink },
};
</script>
