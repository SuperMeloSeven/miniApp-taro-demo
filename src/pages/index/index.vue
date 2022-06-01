<template>
  <view class="index">
    <text>{{ msg }}</text>
    <text>第一次使用taro</text>
    <text class="font-style">
      第二次使用使用taro
    </text>
    <view>
      多端同步调试
    </view>
  </view>
</template>

<script>
import './index.less'

export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  }
}
</script>
