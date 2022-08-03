<template>
  <q-page padding>
    <q-btn label="click me" color="green"></q-btn>
    <q-card style="width: 350px">
      <q-card-section class="bg-blue text-white">
        My Card
      </q-card-section>
      <q-card-section>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque aperiam, obcaecati delectus ea quos minus vel vero nobis eaque amet officia illum hic, alias necessitatibus corporis magni excepturi soluta itaque.
      </q-card-section>
    </q-card>
    <q-select outlined label="outlined" :options="['Luke', 'shannen', 'lilly']" v-model="selected"></q-select>
    <q-select borderless label="borderless" :options="['Luke', 'shannen', 'lilly']" v-model="selected"></q-select>
    <q-select filled label="filled" :options="['Luke', 'shannen', 'lilly']" v-model="selected"></q-select>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

// Options API vs Compsition API (later will conver to CompositionAPI)
export default defineComponent({
  name: 'IndexPage',
  data () {
    return {
      selected: null
    }
  }
})
</script>
