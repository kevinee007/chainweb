<template>
  <footer class="mainFooter">
    <i-container>
      <i-row class="_padding-y-lg-2 _padding-top-xs-1 _padding-bottom-xs-0">
        <i-column :xs="12" :md="6" class="_padding-left-0">
          <div class="secondaryText">Made with ❤ by <a href="https://matter-labs.io" target="_blank">Matter Labs</a></div>
        </i-column>
        <i-column :xs="12" :md="6" class="_padding-right-0">
          <div class="rightSideLinks">
            <a href="//docs.zksync.io/contact.html"><i class="fal fa-at" />&nbsp;Contacts</a>
            <a href="//github.com/matter-labs/zksync"><i class="fab fa-github" />&nbsp;GitHub</a>
            <a href="//docs.zksync.io/legal/terms.html">Terms</a>
            <a href="//docs.zksync.io/legal/privacy.html">Privacy Policy</a>
          </div>
        </i-column>
      </i-row>
    </i-container>
  </footer>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Footer",
});
</script>
