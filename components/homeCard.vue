<template>
<v-container>
    <v-row>
    <v-col hover cols=4 v-for="card in cards" v-bind:key="card.title">
    <v-card height="200px" color="orange">

    <div class ="title">{{card.title}}</div>
    <v-card-text class="text--primary">{{card.primary}}</v-card-text>


</v-card>
</v-col>
</v-row>
</v-container>


</template>

<script>
export default{
    auth:false,
    data(){
        return{
            cards:[
            {title:"そう、わたしたちは 1",primary:"この"},
            {title:"2",primary:"あ"},
            {title:"4",primary:"ぜ"},
            {title:"5",primary:"みち"},
            {title:"6",primary:"をいけば。そこにはさらさらすすきのながるる"},
            {title:"7",primary:"このばしょにあったもの、あったはずのものはとおくにいって"},
            {title:"8",primary:"みなもにうつるきのうのおもかげ"},
            {title:"9",primary:"やっぱり"},
            {title:"10",primary:"そうだったんだね"}
            ]
        }
    }


}
</script>