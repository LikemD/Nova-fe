<template>
  <div class="font-poppins button-green">
    <!-- Title -->
    <div class="flex justify-between">
      <div class="text-2xl">Payment Type</div>

      <div class="float-right">
        <img src="../assets/icons/VectorClose.png" />
      </div>
    </div>
    <!-- Title -->
    <div class="line pb-4"></div>

    <div>
      <div class="flex">
        <div>
          <div class="text-xl">Cash</div>
          <div class="bg-input-grey p-4 rounded-lg">
            <div>
              <img src="../assets/icons/Payment_One.png" />
            </div>
          </div>
        </div>
        <div>
          <div class="text-xl">Mobile Money</div>
          <div class="bg-input-grey p-4 rounded-lg">
            <div class="flex">
              <img src="../assets/icons/vodafone 1.png" />
              <img src="../assets/icons/mtn 1.png" />
              <img src="../assets/icons/airteltigo 1.png" />
            </div>
          </div>
        </div>
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
img {
  width: 100%;
  height: 100%;
}
</style>