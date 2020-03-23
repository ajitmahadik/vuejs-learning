<template>
  <div>
    <b-nav tabs>
      <b-nav-item disbaled><b>Fancy Quiz App</b></b-nav-item>
      <b-nav-item disbaled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: [
    'numTotal',
    'numCorrect'
  ]
}
</script>