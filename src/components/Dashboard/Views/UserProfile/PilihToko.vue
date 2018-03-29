<template>
  <card>
    <div class="row">
      <div class="col-md-6">
        <h4 slot="header" class="card-title">Toko Anda : Balin Tokopedia</h4>
      </div>
      <div class="col-md-6 text-right">
        <h6 class="mt-2 mb-1">Pengaturan</h6>
      </div>
    </div>
  </card>
</template>

<script>
  import Card from 'src/components/UIComponents/Cards/Card.vue'

  export default {
    components: {
      Card
    },
    data () {
      return {
        user: {
          company: 'Paper Dashboard',
          username: 'michael23',
          email: '',
          firstName: 'Mike',
          lastName: 'Andrew',
          address: 'Melbourne, Australia',
          city: 'melbourne',
          country: 'Australia',
          postalCode: '',
          aboutMe: `Lamborghini Mercy, Your chick she so thirsty, I'm in that two seat Lambo.`
        }
      }
    },
    methods: {
      updateProfile () {
        alert('Your data: ' + JSON.stringify(this.user))
      }
    }
  }

</script>
<style>

</style>
