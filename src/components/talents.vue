<template>
    <talents>
        <ul>
            <li v-for="talent in talents" v-bind:value="talent.value" :key="talent.value">
                {{talent}}
            </li>
        </ul>
    </talents>
</template>

<script>
    export default {
        data() {
            return {
                talents: [
                    'Being On time',
                    'Making An Effort',
                    'Being High Energy',
                    'Having A Positive Attitude',
                    'Being Passionate',
                    'Using Good Body Language',
                    'Being Coachable',
                    'Doing A Little Extra',
                    'Being Prepared',
                    'Having A Strong Work Ethic'
                ]  
            }
        }
    }
</script>

<style>
    li {
        color: rgb(84, 54, 59);
        list-style-type: none;
        font-size: 30px;
        line-height: 50px;
        font-weight: bold;
    }
    
</style>