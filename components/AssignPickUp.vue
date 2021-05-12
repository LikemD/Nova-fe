<template>
 <div class="p-10 w-full">
    <div class="button-green text-2xl">Assign Pick Up</div>
    <div><hr class="form-grey" /></div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Surname</label>
    </div>
    <div class="pb-3">
      <input
        type="text"
        class="formtextbox bg-input-grey w-full p-2 border-none focus:outline-none"
      />
    </div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Other Names</label>
    </div>
    <div class="pb-3">
      <input
        type="text"
        class="formtextbox bg-input-grey w-full p-2 border-none focus:outline-none"
      />
    </div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Phone Number</label>
    </div>
    <div class="pb-3">
      <input
        type="text"
        class="formtextbox bg-input-grey w-full p-2 border-none focus:outline-none"
      />
    </div>
    <div class="pt-5">
      <label for="noval_id" class="button-green">Security Code</label>
    </div>
    <div class="pb-3">
      <input
        type="text"
        class="formtextbox bg-input-grey w-full p-2 border-none focus:outline-none"
      />
    </div>
    <div class="pt-10">
      <button
        type="reset"
        class="formtextbox pl-6 pr-7 pt-2 pb-2 text-white items-center btn-color-one focus:outline-none"
      >
        Cancel
      </button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.formtextbox {
  border-radius: 10px;
}
.line {
  border: 1px solid #000000;
}
.btn-color-one {
  background-color: #4d83a2;
}
</style>