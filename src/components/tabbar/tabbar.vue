<template>
      <div class="c_tabbar border_t_1 border_b_1">
              <slot></slot>
      </div>
</template>
<script>
import {tabBar} from '../../../assets/mixins/index.js'
export default{
    mixins:[tabBar]
}
</script>
<style lang="less">
@bg:#fff;
    .c_tabbar{
          width:100%;
          background-color:@bg;
          display: flex;
          justify-content:space-between;
          align-items:center;
    }
</style>

