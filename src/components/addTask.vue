<template>
  <div>
    <div class="line">
      <span class="title">目标名称</span>
      <input type="text" class="content">
    </div>
    <div class="line">
      <span class="title">计划开始时间</span>
      <van-datetime-picker
        v-model="currentDate"
        type="date"
        title="选择年月日"
        :min-date="minDate"
        :max-date="maxDate"
      />
    </div>
    <div class="line">
      <span class="title">计划完成时间</span>
      <van-datetime-picker
        v-model="currentDate"
        type="date"
        title="选择年月日"
        :min-date="minDate"
        :max-date="maxDate"
      />
    </div>
    <div class="line">
      <span>完成奖励/失败惩罚</span>
    </div>
    <div class="line">
      <span class="title">是否通知好友监督</span>
    </div>
    <div class="line">
      <van-button type="info">保存</van-button>

    </div>

  </div>
</template>

<script>
  export default {
    data() {
      return {

      }
    },

    components: {},

    methods: {
      addTask() {

      }

    },

    created() {
      // let app = getApp()
    }
  }

</script>

<style scoped>


</style>
