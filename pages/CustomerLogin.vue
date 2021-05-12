<template>
  <div>
    <nav
      class="bg-dark-green h-36 flex justify-space-between content-center items-center"
    >
      <div class="m-24">
        <img src="../assets/icons/Nova Logo nav.png" class="w-45 h-20" />
      </div>
      <div class="absolute right-11">
        <div class="flex flex-row justify-center content-center items-center">
          <img src="../assets/icons/Ellipse 8.png" />
          <span class="mx-2.5 w-40 font-poppins text-lg leading-1 text-white"
            >Isaac NINSON</span
          >
          <img src="../assets/icons/Exit.png" class="" />
        </div>
      </div>
    </nav>
    <div class="containeer w-full">
      <div class="m-0 m-auto w-1/3 md:w-3/6 pt-20 sm:w-full">
        <div class="w-full pb-10">
          <div class="m-0 m-auto w-3/6">
            <button class="bg-dark-green text-white items-center subButton">
              Scan Return Cylinder
            </button>
          </div>
        </div>
        <div class="shadow-form p-10 cardSt sm:w-full">
          <div class="flex justify-between">
            <div>
              <label class="text-xl">Customer Details</label>
            </div>
            <div>
              <img src="../assets/icons/VectorClose.png" class="" />
            </div>
          </div>

          <!-- Line -->
          <div class="bg-gray-200 line"></div>
          <!-- Line -->

          <div>
            <label for="noval_id" class="button-green">Nova ID</label>
          </div>
          <div class="pb-3">
            <input
              type="text"
              class="rounded bg-input-grey w-full h-10 border-none"
            />
          </div>
          <div>
            <label for="noval_id" class="button-green">Phone Number</label>
          </div>
          <div class="pb-3">
            <input
              type="text"
              class="rounded bg-input-grey w-full h-10 border-none"
            />
          </div>
          <div>
            <label for="noval_id" class="button-green">Surname</label>
          </div>
          <div class="pb-3">
            <input
              type="text"
              class="rounded bg-input-grey w-full h-10 border-none"
            />
          </div>
          <div>
            <label for="noval_id" class="button-green">Other Names</label>
          </div>
          <div class="pb-3">
            <input
              type="text"
              class="rounded bg-input-grey w-full h-10 border-none"
            />
          </div>

          <!-- Line -->
          <div class="pt-16 pb-10">
            <div class="bg-gray-200 line"></div>
          </div>
          <!-- Line -->

          <div class="flex justify-between">
            <div class="sm:pb-4">
              <button
                type="reset"
                class="rounded pl-6 pr-7 pt-2 pb-2 text-white items-center btn-color-one"
              >
                Cancel
              </button>
            </div>
            <div>
              <button
                type="submit"
                class="bg-dark-green rounded pl-6 pr-6 pt-2 pb-2 text-white items-center"
              >
                Confirm
              </button>
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
/* Only comments */
.subButton {
  height: 67px;
  width: 100%;
  left: 578px;
  top: 232px;
  border-radius: 10px;
  padding: 20px, 37px, 20px, 37px;
}
.cardSt {
  width: 100%;
  left: 464px;
  top: 354px;
  border-radius: 10px;
}
.line {
  padding-bottom: 3px;
  width: 100%;
  left: 502px;
  top: 429px;
  margin-bottom: 12px;
}
.btn-color-one {
  background-color: #4d83a2;
}
</style>
