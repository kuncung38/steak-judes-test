<script setup>
import GarpuSendokComponentVue from '../components/GarpuSendokComponent.vue';
</script>

<template>
  <main>
    <img id="awan" src="@/assets/awan-05.svg" alt="awan" />
    <img id="main-logo" src="@/assets/mpok-04.svg" alt="main-logo" />
    <h1 style="font-family: 'NexaBlack', sans-serif;"
      class="font-black text-white text-4xl leading-[2.5rem] mt-[-2.75rem]">
      MENJADI
      PENGUSAHA
      SUKSES
    </h1>
    <div class="h-fit flex flex-row justify-between overflow-hidden">
      <img class="relative right-[11rem]" src="@/assets/makanan_piring-07.svg" alt="steak" />
      <img class="relative right-[11rem]" src="@/assets/makanan_piring-06.svg" alt="fries" />
    </div>
    <p class="text-3xl font-medium">KAMI ADALAH</p>
    <p class="text-3xl font-bold">STEAK MPOK JUDES</p>
    <p class="text-base font-semibold mt-6 px-16">KAMI BERGERAK DI BIDANG F&B DAN SUDAH BERPENGALAMAN</p>

    <!-- <GarpuSendokComponentVue /> -->
    <div class="w-[100] my-24">
      <img src="@/assets/garpusendok.svg" alt="garpu-sendok" class="h-full scale-[1.4]" />
    </div>

    <p class="text-3xl font-extrabold">VISI DAN MISI</p>
    <p class="text-3xl font-extrabold">STEAK MPOK JUDES</p>

    <p class="text-[0.9rem] font-[500] mt-3 px-6">MEMPERKENALKAN MASAKAN WESTERN KEPADA SELURUH KALANGAN MASYARAKAT DENGAN
      HARGA YANG TERJANGKAU
    </p>

    <img src="@/assets/orang-dan-logo.svg" alt="orang-dan-logo" />

    <p class="text-3xl font-extrabold">MENU ANDALAN STEAK JUDES</p>

  </main>
</template>

<style scoped>
main {
  background: #d80000;
  position: relative;
  overflow-x: hidden;
}

#awan {
  position: absolute;
  top: 0;
  z-index: 1;
  opacity: 0.6;
}

h1,
img {
  z-index: 2;
}

#main-logo {
  scale: 0.8;
}
</style>