<template>
    <div class="corner-style">
        <md-select name="task" v-model="el.value" class="md-select-value corner-style">
            <md-option value="controls">Controls</md-option>
            <md-option value="executes">Executes</md-option>
            <md-option value="?">?</md-option>
        </md-select>
    </div>
</template>

<script>
export default {
    name: 'task',
    props: ['el']
}
</script>

<style>
.corner-style {
    width:20px !important;
    height:20px !important;
    margin:auto;
}

.md-select-value {
    padding-right: 20px !important;
    line-height: 20px !important;
    min-width:20px;
}

</style>