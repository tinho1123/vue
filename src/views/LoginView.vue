<script>
    import {useCounterStore} from '@/stores/counter';
    const counter = useCounterStore();
    counter.increment();

</script>

<template>
    <h1>    
        {{counter.count}}
    </h1>
</template>