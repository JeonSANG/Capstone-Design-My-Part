<template> 
<div class="container" style="width:100%;">
<v-container style="color:white">
    <!--스낵바 : 경고 창 출력-->
    <v-snackbar :timeout="timeout" :top="'top'" v-model="snackbar">
        {{ snackbar_text }}
        <v-btn flat color="pink" icon @click.native="snackbar = false">
            <v-icon large> close </v-icon>
        </v-btn>
    </v-snackbar>

    <v-layout>
        <v-flex xs12>
            
        </v-flex>
    </v-layout>
</v-container>
</div>
</template>

<script>
export default {
    methods: {
        
    }
}
</script>

<style>

</style>
