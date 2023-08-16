<script setup>
import BigMenuText from '../components/BigMenuText.vue';
import SmallMenuText from '../components/SmallMenuText.vue'
import SmallerMenuText from '../components/SmallerMenuText.vue'
import GarpuSendokComponentVue from '../components/GarpuSendokComponent.vue';
import MenuPic from '../components/MenuPic.vue';

import FloatingButtonWhatsapp from '../components/FloatingButtonWhatsapp.vue'
</script>

<template>
  <main>
    <img id="awan" src="@/assets/awan-05.webp" alt="awan" />
    <img id="main-logo" src="@/assets/mpok-04.webp" alt="main-logo" />
    <h1 style="font-family: 'NexaBlack', sans-serif;"
      class="font-black text-white text-4xl leading-[2.5rem] mt-[-2.75rem] mx-10">
      MENJADI
      PENGUSAHA
      SUKSES
    </h1>
    <div class="h-fit flex flex-row justify-between overflow-hidden">
      <img class="relative right-[11rem]" src="@/assets/makanan-piring-07.webp" alt="steak" />
      <img class="relative right-[11rem]" src="@/assets/makanan-piring-06.webp" alt="fries" />
    </div>
    <p class="text-3xl font-medium">KAMI ADALAH</p>
    <p class="text-3xl font-bold">STEAK MPOK JUDES</p>
    <p class="text-base font-semibold mt-6 px-16">KAMI BERGERAK DI BIDANG F&B DAN SUDAH BERPENGALAMAN</p>

    <GarpuSendokComponentVue />
    <!-- <div class="w-[100] my-24">
      <img src="@/assets/garpusendok.svg" alt="garpu-sendok" class="h-full scale-[1.4]" />
    </div> -->

    <p class="text-3xl font-extrabold">VISI DAN MISI</p>
    <p class="text-3xl font-extrabold">STEAK MPOK JUDES</p>

    <p class="text-[0.9rem] font-[500] mt-3 px-6">MEMPERKENALKAN MASAKAN WESTERN KEPADA SELURUH KALANGAN MASYARAKAT DENGAN
      HARGA YANG TERJANGKAU
    </p>

    <img src="@/assets/orang-dan-logo.webp" alt="orang-dan-logo" />

    <p class="text-3xl font-extrabold mb-6">MENU ANDALAN STEAK JUDES</p>

    <div class="mb-16">
      <MenuPic :imgPath="'https://i.ibb.co/ZSGTYrD/steak.webp'" :textTitle="'STEAK'" />
      <MenuPic :imgPath="'https://i.ibb.co/ZfpB7Y3/makaroni.webp'" :textTitle="'MAC & CHEESE'" />
      <MenuPic :imgPath="'https://i.ibb.co/Dt7M7wD/steakchicken.webp'" :textTitle="'CHICKEN STEAK'" />
      <MenuPic :imgPath="'https://i.ibb.co/2NK7yWy/carbonara.webp'" :textTitle="'SPAGHETTI CARBONARA'" />
      <MenuPic :imgPath="'https://i.ibb.co/dM5FwdV/bolognese.webp'" :textTitle="'SPAGHETTI BOLOGNESE'" />
    </div>

    <h1 class="text-6xl font-extrabold px-8 mb-8">ALL MENUS</h1>

    <BigMenuText :title="'STEAK'" />
    <SmallMenuText :title="'CHICKEN STEAK'" />
    <SmallMenuText :title="'SIRLOIN STEAK'" />
    <SmallMenuText :title="'CHICKEN CRISPY STEAK'" class="mb-2" />
    <SmallerMenuText :title="'PILIHAN SAUS'" />
    <SmallerMenuText :title="'BBQ, BLACKPEPPER, MUSHROOM'" class="mb-4" />

    <BigMenuText :title="'POTATO'" />
    <SmallMenuText :title="'FRENCH FIRES'" />
    <SmallMenuText :title="'POTATO WEDGES'" class="mb-4" />

    <BigMenuText :title="'PASTA'" />
    <SmallMenuText :title="'SPAGHETTI BOLOGNESE'" />
    <SmallMenuText :title="'SPAGHETTI CARBONARA'" />
    <SmallMenuText :title="`MAC N' CHEESE`" />
    <SmallMenuText :title="'MACARONI CARBONARA'" class="mb-16" />

    <SmallerMenuText :title="'HANYA DENGAN'" />
    <h1 class="text-6xl font-extrabold px-8">75 JUTA</h1>
    <SmallerMenuText :title="'KALIAN SUDAH DAPAT BERGABUNG MENJADI MITRA KAMI'" class="mb-8" />

    <BigMenuText :title="'DAN MENDAPATKAN'" />
    <SmallerMenuText :title="'BOOTH KONTAINER'" />
    <SmallerMenuText :title="'PAPAN MENU LED'" />
    <SmallerMenuText :title="'PANGANGAN STEAK'" />
    <SmallerMenuText :title="'KOMPOR'" />
    <SmallerMenuText :title="'JEPITAN DAGING'" />
    <SmallerMenuText :title="'PENGORENGAN'" />
    <SmallerMenuText :title="'TEFLON PASTA'" />
    <SmallerMenuText :title="'SPATULA'" />
    <SmallerMenuText :title="'BOX UNTUK SAUCE STEAK'" />
    <SmallerMenuText :title="'CENTONG'" />
    <SmallerMenuText :title="'BOTOL SAUS'" />
    <SmallerMenuText :title="'COLANDER(SARINGAN)'" />

    <img src="@/assets/daging-logo.webp" />

    <BigMenuText :title="'FREE BAHAN BAKU UNTUK 200 PORSI'" class="mb-16" />

    <img src="@/assets/contact-us.webp" />

    <FloatingButtonWhatsapp />
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