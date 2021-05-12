<template>
  <div class="p-6 font-poppins">
    <div class="flex justify-between pl-4 pr-4 pb-3">
      <div class="text-2xl text-button-green">Customer Order</div>
      <div>
        <div>
          <img src="../assets/icons/VectorClose.png" />
        </div>
      </div>
    </div>
    <hr />

    <div class="flex justify-between p-3">
      <div class="flex pl-4 pr-4">
        <div>
          <div class="bg-form-grey rounded-full">
            <div class="text-2xl p-6">
              <img src="../assets/icons/profileIcon.png" />
            </div>
          </div>
        </div>

        <div class="pt-3 pl-5">
          <div class="text-xl text-button-green">Deborah Anthonio</div>
          <div class="text-form-grey">332244355544</div>
        </div>
      </div>
      <div>
        <img src="../assets/icons/qrCode.png" />
      </div>
    </div>
    <hr />

    <div class="pl-4 pr-4">
      <div class="pt-4">
        <label for="" class="text-button-green text-xl"
          >Preferred Cylinder Type</label
        >
        <select class="rounded bg-input-grey w-full p-3 focus:outline-none">
          <option value="">select</option>
          <option value="">1</option>
        </select>
      </div>
      <div class="pt-4">
        <label for="" class="text-button-green text-xl">Preferred Size</label>
        <select class="rounded bg-input-grey w-full p-3 focus:outline-none">
          <option value="">select</option>
          <option value="">1</option>
        </select>
      </div>
    </div>

    <div class="pt-10 pl-4 pr-4 pb-6">
      <div class="flex justify-between">
        <div class="flex">
          <div class="text-button-green text-xl pt-2 pr-6">Qty</div>
          <div class="p-3 rounded-full">
            <div class="relative">
              <div class="pt-0.5">
                <img src="../assets/icons/Rectangle.png" />
              </div>
              <div class="absolute top-2 left-2">
                <img src="../assets/icons/arrowLeft.png" />
              </div>
            </div>
          </div>
          <div class="pt-2 button-green text-2xl">1</div>
          <div class="p-3 rounded-full">
            <div class="relative">
              <div class="pt-0.5">
                <img src="../assets/icons/Rectangle.png" />
              </div>
              <div class="absolute top-2 left-2.5">
                <img src="../assets/icons/arrowRight.png" />
              </div>
            </div>
          </div>
        </div>
        <div>
          <button
            class="focus:outline-none bg-button-green rounded-md text-white pt-2 pb-2 pr-6 pl-6 text-lg"
          >
            Add
          </button>
        </div>
      </div>
    </div>
    <hr />

    <div class="pl-4 pr-4">
      <div class="text-button-green text-xl pt-4">Your Purchase List</div>
      <div class="flex justify-between pt-4">
        <div class="flex">
          <div>
            <div class="bg-form-grey rounded-full p-6 relative">
              <div class="absolute top-2.5 left-2.5">
                <img src="../assets/icons/NovaCylinderImageSmall.png" />
              </div>
            </div>
          </div>
          <div class="pl-6 pt-1 w-full relative">
            <div class="text-button-green text-xl">3kg Steel Cylinder</div>
            <div class="flex justify-between">
              <div>
                <span class="text-form-grey">DepositType - </span
                ><span class="text-button-green font-bold">Cash</span>
                <span class="text-green font-bold pl-4">100</span>
              </div>
            </div>
            <div class="pSize">
              <span class="text-form-grey">Qty - </span>
              <span class="text-button-green font-bold">1</span>
            </div>
          </div>
        </div>
        <div>
          <div>
            <img src="../assets/icons/VectorDeleteCart.png" />
          </div>
        </div>
      </div>

      <div class="flex justify-between pt-4 pb-6">
        <div class="flex">
          <div>
            <div class="bg-form-grey rounded-full p-6 relative">
              <div class="absolute top-2.5 left-2.5">
                <img src="../assets/icons/NovaCylinderImageSmall.png" />
              </div>
            </div>
          </div>
          <div class="pl-6 pt-1 w-full relative">
            <div class="text-button-green text-xl">5kg Steel Cylinder</div>
            <div class="flex justify-between">
              <div>
                <span class="text-form-grey">DepositType - </span
                ><span class="text-button-green font-bold">Cylinder</span>
              </div>
            </div>
            <div class="pSize">
              <div>
                <span class="text-form-grey">Qty - </span>
                <span class="text-button-green font-bold">1</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div>
            <img src="../assets/icons/VectorDeleteCart.png" />
          </div>
        </div>
      </div>
    </div>
    <hr />

    <!-- Button -->
    <div class="flex justify-between pt-6">
      <div>
        <button
          type="reset"
          class="rounded-lg pl-6 pr-7 pt-2 pb-2 text-lg text-white items-center btn-color-one focus:outline-none"
        >
          Cancel
        </button>
      </div>
      <div>
        <button
          class="bg-green pt-2 pb-2 pl-6 pr-7 text-white text-lg rounded-lg focus:outline-none"
        >
          Confirm
        </button>
      </div>
    </div>
    <!-- Button -->
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
img {
  width: 100%;
  height: 100%;
}
.pSize {
  position: absolute;
  top: 34px;
  left: 269px;
  width: 100%;
}
.btn-color-one {
  background-color: #4d83a2;
}
</style>