<template>
  <div id="app">
    <!-- Boardコンポーネントの呼び出し -->
    <board />
  </div>
</template>


<script>
// インポート文を追加
import Board from './components/Board.vue'

export default {
  name: 'App',
  components: {
    // コンポーネントに登録
    Board
  }
}
</script>
