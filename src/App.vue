<template>
    <div id="app">
        <img src="../images/sportclips.png"/>

        <div>

        </div>

        <md-tabs class="md-primary" md-dynamic-height md-sync-route>
            <md-tab id="tab-home" md-label="Home" to="/components/tabs/home">
                <iframe id="POS" src="https://salonultimate.com"/>
            </md-tab>
            <md-tab id="tab-marketing" md-label="Marketing" to="/components/tabs/marketing">ddd</md-tab>
            <md-tab id="tab-survey" md-label="Survey" to="/components/tabs/survey">ddd</md-tab>
            <md-tab id="tab-pos" md-label="Salon POS" to="/components/tabs/pos">
            </md-tab>
            <md-tab id="tab-training" md-label="Training" to="/components/tabs/training">ddd</md-tab>
            <md-tab id="tab-finance" md-label="Finance" to="/components/tabs/finance">ddd</md-tab>
            <md-tab id="tab-huddle" md-label="SCI Huddle" to="/components/tabs/huddle">ddd</md-tab>
        </md-tabs>
    </div>
</template>

<script>
    export default {
        name: 'app',
        data () {
            return {
                msg: 'Welcome to Your Vue.js App!'
            }
        }
    }
</script>

<style lang="css">
    #app {
        color: #56b983;
    }
    iframe {
        width: -webkit-fill-available;
        height: -webkit-fill-available;
        border: unset;
        border-image: unset;
    }
    #tab-home {
        padding: unset;
    }
</style>