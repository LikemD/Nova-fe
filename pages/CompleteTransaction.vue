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
          <div>
            <img src="../assets/icons/Ellipse 8.png" />
          </div>
          <div>
            <span class="mx-2.5 w-40 font-Poppins text-lg leading-1 text-white"
              >Isaac NINSON</span
            >
          </div>
          <div>
            <img src="../assets/icons/Exit.png" />
          </div>
        </div>
      </div>
    </nav>
    <!-- Header -->

    <!-- Header-Wrapper -->
    <div class="hWrapper">
      <div class="flex justify-between p-5">
        <div class="flex text-red-500">
          <div class="pr-4 text-xl font-bold">BACK</div>
          <div class="bg-red-500 border:none w-1"></div>
        </div>
        <div class="flex">
          <div class="pr-2">
            <div class="bg-dark-green rounded-full">
              <img src="../assets/icons/logo-16.png" />
            </div>
          </div>
          <div class="pr-2">Buy Accessory</div>
          <div class="line"></div>
          <div class="pl-2">
            <div class="absolute w-3 top-40 right-7">
              <img src="../assets/icons/VectorBag.png" />
            </div>
            <div class="w-7 pt-1">
              <img src="../assets/icons/VectorBag1.png" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Header-Wrapper -->

    <!-- Page Content -->
    <div class="containeer font-poppins">
      <div class="content w-full p-10 xl:flex lg:flex">
        <div
          class="bg-bgTransaction productSection border border-border xl:w-9/12 lg:w-4/6 p-6 flex flex-wrap"
        >
          <div class="m-0 m-auto">
            <img src="../assets/icons/defaultIcon.png" />
          </div>
        </div>

        <!-- Transaction -->
        <div
          class="xl:pl-10 lg:pl-10 xl:pt-0 lg:pt-0 xl:w-1/3 lg:w-2/6 md:pt-5 md:pl-0 sm:pl-0 sm: pt-5"
        >
          <div class="border border-border lg:w-full md:w-2/3 sm:w-2/3 p-4">
            <div class="bg-gray-200 w-1/4 rounded-full m-0 m-auto">
              <div class="bg-green m-0 m-auto rounded-full p-2">
                <div class="xl:p-4 lg:p-2 md:p-4 sm:p-4">
                  <img src="../assets/icons/tick.png" />
                </div>
              </div>
            </div>
            <div class="colorText flex justify-center pt-3">
              <span>Your transaction was successfull</span>
            </div>
            <div class="colorText flex justify-center">
              <span>521265421</span>
            </div>

            <div class="colorText text-2xl flex justify-center leading-3">
              <span>Transaction Details</span>
            </div>

            <div class="hr"></div>

            <div class="text-sm leading-2">
              <div class="flex justify-between colorText1">
                <div class="font-bold">DATE</div>
                <div>6 June, 2020</div>
              </div>
              <div class="flex justify-between colorText1">
                <div class="font-bold">TIME</div>
                <div>11:28 am</div>
              </div>
            </div>

            <div class="line"></div>

            <div class="text-sm leading-2">
              <div class="flex justify-between colorText1">
                <div class="font-bold">FROM</div>
                <div>Dansoman Nova Point</div>
              </div>
              <div class="flex justify-between colorText1">
                <div class="font-bold">TELEPHONE</div>
                <div>+233 5543231233</div>
              </div>
            </div>

            <div class="hr"></div>

            <div class="text-sm flex justify-between leading-2">
              <div class="colorText1">
                <div class="font-bold">TO</div>
                <div>Nii Laryea</div>
                <div>No.2 Ordorkor</div>
                <div>GS-0757-3391</div>
              </div>
              <div class="colorText1">
                <div><img src="../assets/icons/qrCode.png" /></div>
              </div>
            </div>

            <div class="line1"></div>

            <div class="text-sm pt-3 pb-3">
              <div class="pb-3">
                <div class="flex justify-between">
                  <div>3 kg LPG Refil</div>
                  <div>1</div>
                  <div>GHS 30.00</div>
                </div>
                <div class="flex justify-between">
                  <div class="font-bold">RFID</div>
                  <div>1111112345</div>
                </div>
              </div>
              <div class="">
                <div class="flex justify-between">
                  <div>12 kg LPG Refil</div>
                  <div>1</div>
                  <div>GHS 75.00</div>
                </div>
                <div class="flex justify-between">
                  <div class="font-bold">RFID</div>
                  <div>1111112366</div>
                </div>
              </div>
            </div>

            <div class="line1"></div>

            <div class="pt-5">
              <div
                class="bg-input-grey flex justify-between rounded-xl p-2 colorText1"
              >
                <div class="flex">
                  <div>
                    <img src="../assets/icons/Ellipse.png" />
                  </div>
                  <div class="text-base p-3">MTN</div>
                </div>
                <div>
                  <div class="text-sm">AMOUNT</div>
                  <div class="text-lg text-green float-right">76.00</div>
                </div>
              </div>
            </div>
          </div>
          <div class="pt-6">
            <div
              class="bg-green p-5 flex justify-center text-white text-lg rounded-lg"
            >
              <button class="focus:outline-none">Complete Transaction</button>
            </div>
          </div>
        </div>
        <!-- Transaction -->
      </div>
    </div>
    <!-- Page Content -->
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
.hWrapper {
  background-color: rgba(196, 196, 196, 0.35);
}
.colorText {
  color: #939598;
}
.colorText1 {
  color: #0f283b;
}
.hr {
  background-color: #0f283b;
  height: 2px;
}
.line {
  background-color: #0f283b;
  height: 1px;
}
.line1 {
  background-color: #0f283b;
  height: 1.5px;
}
</style>