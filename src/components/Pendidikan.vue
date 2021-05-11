<template>
  <b-container class="mt-5">
    <H3>PENDIDIKAN</H3>
    <ul class="list-unstyled">
      <b-media tag="li">
        <template #aside>
          <b-img :src="sd" width="64" alt="placeholder"></b-img>
        </template>
        <h5 class="mt-0 mb-1">SDN 015 KOTO PERAMBAHAN</h5>
        <p class="mb-0">
          Sekolah ini terletak di dusun perambagan, desa koto perambahan,
          kecamatan kampa, kabupaten kampar, provinsi riau. saya disini
          bersekolah selama 6 tahun.
        </p>
      </b-media>

      <b-media tag="li" class="my-4">
        <template #aside>
          <b-img :src="mts" width="64" alt="placeholder"></b-img>
        </template>

        <h5 class="mt-0 mb-1">MTsN KAMPAR</h5>
        <p class="mb-0">
          Madrasah ini namanya sekarang berubah menjadi MTsN 4 Kampar, saya
          bersekolah disini selama 3 tahun.
        </p>
      </b-media>

      <b-media tag="li">
        <template #aside>
          <b-img :src="sma" width="64" alt="placeholder"></b-img>
        </template>

        <h5 class="mt-0 mb-1">SMAN 1 KAMPAR TIMUR</h5>
        <p class="mb-0">
          Saya sekolah disini selama 3 tahun dengan mengambil jurusan IPA. saya
          masih ingat tanggal wisudah saya yaitu pada kamis, 27 april 2017.
        </p>
      </b-media>
      <b-media tag="li" class="my-4">
        <template #aside>
          <b-img :src="uin" width="64" alt="placeholder"></b-img>
        </template>

        <h5 class="mt-0 mb-1">UIN SUSKA RIAU</h5>
        <p class="mb-0">
          Saya kuliah disini dengan mengambil jurusan teknik informatika dan
          sekarang saya semester 8 dan insyaallah akan seminar sidang pada bukan
          syawwal 1442 h ini. skripsi saya tentang teknologi blokchain dengan
          studi kasusu e-voting
        </p>
      </b-media>
    </ul>
  </b-container>
</template>

<script>
import sd from "../assets/sdn015.jpeg";
import mts from "../assets/mtsn.jpeg";
import sma from "../assets/sman.jpeg";
import uin from "../assets/logo_uin.jpg";

export default {
  data: function () {
    return {
      sd: sd,
      mts: mts,
      sma: sma,
      uin: uin,
    };
  },
};
</script>

<style>
</style>