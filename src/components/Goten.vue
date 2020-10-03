<template>
  <div class="space-y-6">
    <div class="p-16 py-16 md:px-4">
      <div class="goten-image w-full">
        <img
          class="object-cover rounded-full shadow-xl"
          src="../assets/goten.jpg"
          alt="goten"
        />
      </div>
    </div>
    <div>
      <p class="text-center text-2xl text-gray-100">โกเท็นสุดหล่อ</p>
    </div>
    <div class="space-x-4 text-center font-bold text-xl">
      <a href="https://www.facebook.com/chaowat.intarapanit">Facebook</a>
      <a href="https://www.facebook.com/chaowat.intarapanit">Line</a>
      <a href="https://www.instagram.com/goten_ar/">Instargram</a>
      <p class="text-sm text-gray-100 font-light">หล่อเท่</p>
    </div>
  </div>
</template>

<style scoped>
.goten-image {
  animation: circle 10s linear infinite;
}
@keyframes circle {
  from {
    -webkit-transform: rotate(0deg);
    -o-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  to {
    -webkit-transform: rotate(360deg);
    -o-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}
</style>

