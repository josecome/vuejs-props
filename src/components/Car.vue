<script setup>
defineProps({
car_id: {
    type: Number,
    required: true
  },
  brand: {
    type: String,
    required: true
  },
  serie: {
    type: String,
    required: true
  },
  origin: {
    type: String,
    required: true
  },
  price: {
    type: Number,
    required: true
  }
})
</script>

<template>
  <div>
    <table>
            <tr>
                <td>Id</td><td><strong>{{ car_id }}</strong></td>
            </tr>
            <tr>
                <td>Brand</td><td><strong>{{ brand }}</strong></td>
            </tr>
            <tr>
                <td>Serie</td><td><strong>{{ serie }}</strong></td>
            </tr>
            <tr>
                <td>Origin</td><td><strong>{{ origin }}</strong></td>
            </tr>
            <tr>
                <td>Price</td><td><strong>{{ price }}</strong></td>
            </tr>
        </table>
  </div>
</template>

