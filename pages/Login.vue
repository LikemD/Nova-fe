<template>
  <div>
    <body class="bg-dark-green">
      <section
        class="flex flex-col justify-center content-center items-center h-screen w-screen"
      >
        <div class="card bg-white w-auto h-auto border rounded-2xl">
          <img src="../assets/icons/Nova Logo 1.png" class="mx-auto mt-5" />
          <div class="form flex flex-col">
            <form>
              <div class="flex flex-col">
                <label
                  for="username"
                  class="font-poppins text-xs leading-4 font-normal mx-9 mt-10 focus:outline-none"
                  >Username</label
                >
                <input type="text" name="username" class="mx-9" />
              </div>
              <div class="flex flex-col">
                <label
                  for="password"
                  class="font-poppins text-xs leading-4 font-normal mx-9 mt-10 focus:outline-none"
                  >Password</label
                >
                <input type="text" name="password" class="mx-9 password" />
              </div>
              <div
                class="flex flex-col justify-center content-center items-center"
              >
                <button
                  class="bg-dark-green text-white mt-9 w-56 border rounded-3xl font-poppins text-xs leading-4 font-normal p-3.5"
                >
                  LOGIN
                </button>
                <button
                  class="bg-transparent border-transparent text-orange font-poppins text-xs leading-4 font-normal label mt-3.5 mb-8"
                >
                  Forgot Password?
                </button>
              </div>
            </form>
          </div>
        </div>
      </section>
      <div>
        <img
          src="../assets/icons/Nova Cylinder Image.75x.png"
          class="absolute bottom-12 right-16"
        />
        <img
          src="../assets/icons/Nova Cylinder ImageSmall.75x.png"
          class="absolute bottom-12 right-10"
        />
      </div>
    </body>
  </div>
</template>

<script>
export default {}
</script>
<style scoped>
input[type='text'] {
  width: 15.375rem;
  border: none;
  border-bottom: 1px solid #000;
}

.password {
  background-image: url(../assets/icons/Vector.png);
  background-repeat: no-repeat;
  background-position: right;
}
</style>
