<template>
  <div class="grade">
    <div class="sidebar">
      <Sidebar>

      </Sidebar>
    </div>
    <div class="content">
      <Feed>

      </Feed>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Feed from '~/components/feed/feed.vue'
import Sidebar from '~/components/sidebar/sidebar.vue'

export default Vue.extend({
  name: "HomePage",
  components: { Feed, Sidebar }
})
</script>
