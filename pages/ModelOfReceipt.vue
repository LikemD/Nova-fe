<template>
  <div class="font-poppins font-bold text-button-green">
    <div class="p-3">
      <div class="text-2xl pb-2">
        <p>Mode of Receipt</p>
      </div>
      <div class="line pb-4"></div>
      <div
        class="flex space-x-4 border border-border rounded-md pt-6 pb-6 pl-3 pr-3"
      >
        <div class="leading-10">
          <input type="radio" class="bg-border" />
        </div>
        <div class="w-1/2">
          <img src="../assets/icons/delivery.png" />
        </div>
        <div class="leading-10 text-xl font-bold">
          <label for="">Delivery</label>
        </div>
      </div>
      <div class="pt-6">
        <div class="flex space-x-8 border border-border rounded-md p-3">
          <div class="pt-6">
            <input type="radio" class="bg-border" />
          </div>
          <div class="w-1/4">
            <img src="../assets/icons/pickup.png" />
          </div>
          <div class="pt-6 text-xl font-bold">
            <label for="">Self-Pickup</label>
          </div>
        </div>
      </div>

      <div class="pt-6">
        <div class="flex space-x-8 border border-border rounded-md p-3">
          <div class="pt-6">
            <input type="radio" class="bg-border" />
          </div>
          <div class="w-1/4">
            <img src="../assets/icons/pickup.png" />
          </div>
          <div class="pt-6 text-xl font-bold">
            <label for="">Assign-Pickup</label>
          </div>
        </div>
      </div>
      <div class="pt-6 flex justify-center">
        <button
          class="bg-button-green text-white focus:outline-none pt-2 pb-2 pr-6 rounded-md pl-6"
        >
          Confirm
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.line {
  border-top: 1px solid #adabab;
}
</style>