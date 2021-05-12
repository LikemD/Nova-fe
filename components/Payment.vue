<template>
  <div class="p-4 w-full">
    <div class="float-right"><img src="../assets/icons/VectorClose.png" /></div>
    <div class="button-green text-2xl flex justify-center">Mobile Money</div>
    <div class="pt-5"><hr class="form-grey" /></div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Network</label>
    </div>
    <div>
      <select class="rounded bg-input-grey w-full p-3 focus:outline-none">
        <option value="">select</option>
        <option value="">1</option>
      </select>
    </div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Phone Number</label>
    </div>
    <div class="pb-3">
      <input
        type="text"
        class="rounded bg-input-grey w-full p-2 border-none focus:outline-none"
      />
    </div>
    <div class="flex justify-between leading-3">
      <div class="text-lg font-bold colorPurchase">Purchase</div>
      <div class="text-lg font-bold colAmt">105</div>
    </div>
    <div class="flex justify-between leading-3">
      <div class="text-lg font-bold colorPurchase">Delivery</div>
      <div class="text-lg font-bold colAmt">10</div>
    </div>
    <div class="flex justify-between leading-3">
      <div class="text-lg font-bold">Total Amount</div>
      <div class="text-lg font-bold text-red-500">115</div>
    </div>
    <div class="pt-10">
      <div
        class="bg-green p-2 flex justify-center text-white text-lg rounded-lg"
      >
        <button class="focus:outline-none">Proceed to check out</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.colorPurchase{
    color:#969393;
}
.colAmt {
    color:#0B7786;
}
</style>