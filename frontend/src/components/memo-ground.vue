<template>
    <div class="ground">
        <memoHeader/>
        <memo-page/>
        <memo-footer/>
    </div>
</template>

<script>
import memoHeader from "@/components/memo-header.vue";
import memoFooter from "@/components/memo-footer.vue";
import memoPage from "@/components/memo-page.vue";
export default {
    components: {
        memoHeader,
        memoFooter,
        memoPage
    }
}
</script>
