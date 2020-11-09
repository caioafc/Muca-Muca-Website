<template>
    <div class="display">
        <img src="../assets/images/bg-welcome.svg" alt="box-welcome-message" id="wlc">
        <img src="../assets/images/bg-kids.svg" alt="kids-background" id="kids">
    </div>

</template>

<script>
export default {

}
</script>

<style>
    .display {
        display: grid;
        grid-template-rows: 1fr 1fr 1fr;
        grid-template-columns: 1fr 1fr 1fr;
        height: 89vh;
    }

    .display #wlc {
        grid-row: 2 / span 1;
        grid-column: 2 / span 1;        
    }

    .display #kids {
        grid-row: 1 / span 3;
        grid-column: 1 / span 3;
    }

</style>