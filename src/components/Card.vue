<template>
    <div class="card">
        <div class="card-header">
            <img :src="card.img">
        </div>
        <div class="card-body">
            <h3>{{ card.title }}</h3>
            <p>{{ card.description }}</p>
            <div class="options">
                <p class="formFactor">Pack of{{ card.formFactor}}</p>
                <div class="order">
                    <button @click="order -= 1">-</button>
                    <span>{{ order }}</span>
                    <button @click="order += 1">+</button>
                </div>
                <p>${{ card.price }}</p>
            </div>
        </div>
        <div class="card-footer">
            <button @click="addToCart">Add to cart</button>
        </div>
    </div>
</template>
<script>
import { defineComponent, defineProps, ref, onMounted } from 'vue'

export default defineComponent({
    props: {
        card: {
            img: String,
            title: String,
            description: String,
            formFactor: Number,
            price: Number,
        }
    },
    setup(props) {
        
        const order = ref(0)

        onMounted(() => {
            JSON.parse(JSON.stringify(props))
        })
        return {
            order
        }
    }    
})

</script>
<style lang="scss">
.card {
    width: 480px;
    height: 687px;
    display: inline-block;

    .card-header {
        width: 480px;
        height: 450px;
    }
}

</style>