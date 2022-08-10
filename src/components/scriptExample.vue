<template>
    <div>
        <h1>first tweet is {{tweets[0]}}</h1>
        <h2>num of friends are {{num_friends}}</h2>
        <p>am i logged in? <br> the answer is {{logged_in}}</p>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                tweets: [`be honest`,`be positive`,`be humble`],
                num_friends: 500,
                logged_in: true
            }
        },
    }
</script>

<style scoped>

</style>