<template>
  <div>
    <!-- Header -->
    <nav
      class="bg-dark-green h-36 flex justify-between content-center items-center pr-10 pl-10"
    >
      <div class="leading-3">
        <img src="../assets/icons/Nova Logo nav.png" />
      </div>
      <div>
        <div class="flex flex-row justify-center content-center items-center">
          <div class="">
            <img src="../assets/icons/Ellipse 8.png" />
          </div>
          <div class="">
            <span class="mx-2.5 w-40 font-Poppins text-lg leading-1 text-white"
              >Isaac NINSON</span
            >
          </div>
          <div class="">
            <img src="../assets/icons/Exit.png" />
          </div>
        </div>
      </div>
    </nav>
    <!-- Header -->

    <!-- Content -->
    <div class="containeer w-full">
      <div class="m-0 m-auto w-2/4 md:w-auto sm:w-4/6 pt-24">
        <div class="w-full">
          <div class="m-0 m-auto xl:w-60 lg:w-64 md:w-60 sm:w-60">
            <p class="not-italic font-bold text-2xl text-dark-green">
              NO DEPOSIT MADE
            </p>
          </div>
        </div>

        <div class="w-full pt-2 pb-2">
          <div class="m-0 m-auto md:w-1/5 sm:w-4/12">
            <img src="../assets/icons/Nova Cylinder Image.png" />
          </div>
        </div>
        <div class="pb-3 text-center md:w-full">
          <div class="text-gray-400 text-xl">
            <p>Client Must Make Deposit to Activate Account.</p>
            <p>Deposit can either be cash or a Cylinder.</p>
            <p>Click the Icon Below to Make Deposit</p>
          </div>
        </div>
        <div class="w-full pb-10">
          <div class="m-0 m-auto xl:w-72 lg:w-80 md:w-72 sm:w-72">
            <button
              type="submit"
              class="bg-dark-green rounded-md pl-20 text-xl pr-20 pt-2 pb-2 text-white items-center"
            >
              Make Deposit
            </button>
          </div>
        </div>
      </div>
    </div>
    <!-- Content -->
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
</style>
