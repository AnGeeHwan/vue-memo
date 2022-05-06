<template>
  <div class="ground">
    <HeaderMemo />
    <ContentMemo />
    <FooterMemo />
  </div>
</template>

<script>
import HeaderMemo from "./HeaderMemo.vue";
import FooterMemo from "./FooterMemo.vue";
import ContentMemo from "./ContentMemo.vue";

export default {
  components: { HeaderMemo, FooterMemo, ContentMemo },
};
</script>
