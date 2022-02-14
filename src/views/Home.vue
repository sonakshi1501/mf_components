<template>
  <div class="conatiner">
    <div class="col-md-12">   
      <Card title="This is card tittle" desc="This is card descripton" link="https://vrijraj.xyz/"/>
      <UserInfo name="sonakshi" email="sonakshishukla1501@gmail.com"/>
       </div>

  </div>
</template>

<script>
// @ is an alias to /src
import Card from '../components/Card.vue'
import UserInfo from '../components/UserInfo.vue'

export default {
  name: 'Home',
  components: {
    Card, UserInfo
  }
}
</script>
