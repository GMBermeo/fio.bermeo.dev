<template>
  <div class="inner-container">
    <div class="mb-2 px-4 sm:px-0">
      <div class="float-left mr-6 lg:mr-12">
        <div class="w-44">
          <img src="/images/mockup/obzidian.jpg" />
        </div>
      </div>
      <p class="text-justify text-lg">
        {{ text.collection }}
      </p>
    </div>
  </div>
</template>

<!-- <template lang="pug">
.inner-container
  .mb-6.px-4
    .float-left.mr-6
      .w-44
        img(src="../../images/mockup/obzidian.jpg")
    p.text-justify.text-lg Lorem ipsum consectetur adipisicing corrupti deleniti impedit commodi beatae, aliquam modi dolor?elit. Nemoaut maiores quos vitae saepe aliquid inventore distinctio veniam, iure. Repellendus temporibus quidemdolor sit amet culpa voluptate aperiam. Blanditiis! Lorem ipsum dolor sit, ametconsectetur adipisicing elit. Consequuntur magnam corrupti quia! Cupiditate, distinctio omnis esse nulla consequuntur adipisci quia aliquid quaerat repellendus et ipsum cum
</template> -->

<script lang="ts">
export default {
  props: ["text"],
};
</script>
