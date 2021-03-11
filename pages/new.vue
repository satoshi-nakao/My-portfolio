<template>
    <v-row justify="center" align="center"> 
    <v-col cols="12" sm="8" md="6">
    <v-card>
        <v-card-title>新機能</v-card-title>
        <v-card-text>
            <p>カーソルでなぞってみてください</p>
            <vue-scratchable class="new">
        　　　<h1>THANKS!</h1>
    　　　　</vue-scratchable>
        </v-card-text>
    </v-card>
    </v-col>
    </v-row>
</template>

<style>
.new{
    margin: 0 auto;
    min-height: 10vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    color: red;
}
</style>