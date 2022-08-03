<template>
  <q-page class="row">
    <q-card class="col-xs-9">
      <q-toolbar class="bg-primary" />
      <q-list>
        <q-item>
          <q-item-section side>
            <q-checkbox :model-value="true" />
          </q-item-section>
          <q-item-section>
            Go Shopping
          </q-item-section>
          <q-item-section side>
            <q-btn
              icon="mdi-delete"
              flat
              round
              size="sm"
            />
          </q-item-section>
        </q-item>
      </q-list>
    </q-card>
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
