<template>
    <span>
        <home-hero></home-hero>
    </span>
</template>

<script>
// @ is an alias to /src
import HomeHero from '@/components/HomeHero';
import HomeDetails from '@/components/HomeDetails';

export default {
    name: 'home',
    components: {
        HomeHero,
        HomeDetails
    }
};
</script>
