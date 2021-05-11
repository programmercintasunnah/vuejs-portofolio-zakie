<template>
  <b-container class="bg">
    <div>
      <b-card
        overlay
        :img-src="require('../assets/bgku.jpg')"
        img-alt="Card Image"
        text-variant="white"
        title=""
        img-width="900"
        img-height="250"
        sub-title=""
      >
       <div class="fotoku">
          <b-avatar
            :src="require('../assets/zakie.png')"
            size="15rem"
          ></b-avatar>
          <!-- <b-avatar :src=image size="20rem"></b-avatar> -->
        </div>
      a
      </b-card>
    </div>
    <b-jumbotron>
      <template #lead>
       
      </template>
      <h4 class="nama mt-5">MUHAMMAD ZAKIE, S.T</h4>
      <h6 class="nama mt-2">Web Developer</h6>
      <hr class="my-4" />
      <!-- <b-button variant="primary" href="#">Save</b-button>
      <b-button variant="success" href="#">Do Something Else</b-button> -->
      <div>
          
        <b-list-group>
            <h3>Media Sosial</h3>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="facebook"
              animation="fade"
              font-scale="2"
              variant="info"
            ></b-icon>
          <b-link href="https://web.facebook.com/muhammad.zakie.1675">Muhammad Zakie</b-link>
          </b-list-group-item>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="instagram"
              animation="throb"
              font-scale="2"
              variant="danger"
            ></b-icon>
            <b-link href="https://www.instagram.com/muhammadzakie22">@muhammadzakie22</b-link>
            
          </b-list-group-item>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="instagram"
              animation="spin"
              font-scale="2"
              variant="danger"
            ></b-icon>
            <b-link href="https://www.instagram.com/programmercintasunnah/">@programmercintasunnah</b-link>
          </b-list-group-item>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="github"
              animation="spin-pulse"
              font-scale="2"
              variant=""
            ></b-icon>
              <b-link href="https://github.com/muhammadzakie">@muhammadzakie</b-link>
          </b-list-group-item>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="github"
              animation="spin-reverse"
              font-scale="2"
              variant=""
            ></b-icon>
             <b-link href="https://github.com/programmercintasunnah">@programmercintasunnah</b-link>
          </b-list-group-item>
          <b-list-group-item
            class="d-flex justify-content-between align-items-center"
          >
            <b-icon
              icon="twitter"
              animation="cylon"
              font-scale="2"
              variant="info"
            ></b-icon>
             <b-link href="https://twitter.com/muhammadzakie22">@muhammadzakie22</b-link>
          </b-list-group-item>
        </b-list-group>
      </div>
    </b-jumbotron>
  </b-container>
</template>

<script>
import image from "../assets/logo.png";

export default {
  data: function () {
    return {
      image: image,
    };
  },
};
</script>

<style>
/* .bg {
  background-color: antiquewhite;
} */
.nama {
  text-align: center;
}
.fotoku {
  margin-top: 50px;
  text-align: center;
}
#header {
  margin-top: 10px;
}
</style>