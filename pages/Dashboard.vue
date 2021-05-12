<template>
  <div>
    <!-- Header -->
    <nav
      class="bg-dark-green h-36 flex justify-space-between content-center items-center"
    >
      <div class="m-24">
        <img src="../assets/icons/Nova Logo nav.png" class="w-45 h-20" />
      </div>
      <div class="absolute right-11">
        <div class="flex flex-row justify-center content-center items-center">
          <img src="../assets/icons/Ellipse 8.png" class="" />
          <span class="mx-2.5 w-40 font-poppins text-lg leading-1 text-white"
            >Isaac NINSON</span
          >
          <img src="../assets/icons/Exit.png" class="" />
        </div>
      </div>
    </nav>
    <!-- Header -->

    <section class="mt-12 mb-32 h-56 fixed right-24">
      <button
        class="text-white bg-orange rounded-3xl font-poppins text-xl leading-1 px-12 py-5 signInBtn"
      >
        Sign Up Client
      </button>
    </section>
    <section class="pt-32 flex justify-center content-center items-center">
      <div class="w-2/3 grid justify-items-stretch grid-cols-4 gap-20">
        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/salesANDexchangewhite1.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            <p>Sales and Exchange</p>
          </div>
        </div>

        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/online shopping cart 1.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            Online Order
          </div>
        </div>

        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/product list 1.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            Product Request
          </div>
        </div>

        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/transactions 1.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            Reports
          </div>
        </div>

        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/Cylinder group.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            Inventory
          </div>
        </div>

        <div class="justify-self-center items-center">
          <div
            class="flex justify-center items-center dashIcon bg-grey rounded-3xl focus:bg-dark-green"
          >
            <img src="../assets/icons/door to door 2.png" />
          </div>
          <div
            class="text-center text-dark-green font-poppins text-sm leading-1 mt-3.5"
          >
            Door to Door Delivery
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.signInBtn {
  display: inline-block;
  background-image: url(../assets/icons/Vector-signIn.png);
  background-repeat: no-repeat;
  background-position: right 16px center;
}

.dashIcon {
  width: 138px;
  height: 138px;
}
</style>
