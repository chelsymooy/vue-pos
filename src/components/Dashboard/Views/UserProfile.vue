<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-12">
          <pilih-toko>
          </pilih-toko>
        </div>
        <div class="col-md-12">
          <katalog>
          </katalog>
        </div>
        <div class="col-md-12">
          <flow>
          </flow>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import PilihToko from './UserProfile/PilihToko.vue'
  import Katalog from './UserProfile/Katalog.vue'
  import Flow from './UserProfile/Flow.vue'

  export default {
    components: {
      PilihToko,
      Katalog,
      Flow
    }
  }

</script>
<style>

</style>
