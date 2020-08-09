<template>
  <div class="home">
<employees></employees>
<gtable></gtable>
  </div>
</template>

<script>
import employees from '../components/Employees/employees'
import gtable from '../components/Employees/table'


export default {
  name: 'Home',
  components: {
employees, gtable
  }
}
</script>
