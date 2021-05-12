<template>
  <!-- Cylinder Scanned Successfully -->
  <div class="font-poppins p-6">
    <div>
      <div class="m-0 m-auto w-20">
        <div class="bg-green rounded-full tickBorder">
          <div class="p-4">
            <img src="../assets/icons/tick.png" />
          </div>
        </div>
      </div>
    </div>
    <div class="text-button-green text-3xl flex justify-center pt-5">
      Cylinder Scanned Successfully
    </div>
    <div class="flex justify-between pt-10">
      <div>
        <button
          type="reset"
          class="rounded pl-6 pr-7 pt-2 pb-2 text-white items-center focus:outline-none bg-button-color-one"
        >
          Scan Another Cylinder
        </button>
      </div>
      <div>
        <button
          type="reset"
          class="rounded pl-12 pr-12 pt-2 pb-2 text-white items-center bg-button-green focus:outline-none"
        >
          Complete Scan
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.tickBorder {
  border: 7px solid #f3f3f3;
}
</style>