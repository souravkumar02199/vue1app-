<template>
    <v-container>
        <v-row class="text-center">
            <v-col cols="12">
                <h1>TodoList</h1>
                <ListaTareas />
            </v-col>   
        </v-row> 
    </v-container>
</template>
<script>
import ListaTareas from '../components/ListaTareas'
export default {
    components:{ ListaTareas},
    data() {
        return {}
    },
    
}
</script>