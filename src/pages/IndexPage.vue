<template>
  <div class="c1 text-white q-pa-sm q-ma-xs no-box-shadow">
    <div class="streaming-items">
      <h5>Streaming Goes here!</h5>
    </div>
  </div>
  <div>
    <div class="row q-px-md">
      <div class="cam-container q-pa-md">
        <div class="cam-container-border q-pa-xs">
          <div class="row justify-evenly item-center cam-el q-pa-sm">
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 1" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 2" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 3" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 4" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 5" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 6" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 7" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 8" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 9" />
            </div>
            <div class="q-px-xs q-my-xs qbtn-size">
              <q-btn size="sm" color="white" text-color="white" label="Cam 10" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 1" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 2" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 3" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 4" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 5" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 6" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 7" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 8" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 9" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 10" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 1" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 2" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 3" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 4" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 5" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 6" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 7" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 8" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 9" />
            </div>
            <div class="q-px-xs q-my-xs">
              <q-btn size="sm" color="white" text-color="white" label="Cam 10" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="row no-wrap justify-between footer-seciton bg-black q-px-md q-py-sm">
    <img src="../assets/VCR_pms285_logo.jpg" />
    <img src="../assets/FG_Badge_Logo.png" />
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
<style>
.footer-seciton {
  width: 100%;
  height: 65px;
  position: fixed;
  bottom: 82px;
}

.qimage-section {
  height: 100%;
  width: 100%;
}

.text-color {
  color: #ffffff;
}

.bg-color {
  color: #4f4f58;
}

img.q-img__image.q-img__image--with-transition.q-img__image--loaded {
  width: auto;
}

.section-no-wrap {
  flex-wrap: nowrap;
}

.cam-el {
  border-radius: 5px;
  background-color: #262231;
}

.c1 {
  display: flex;
  width: 100%;
  justify-content: center;
}

.cam-container {
  border-radius: 10px;
  background: rgb(146, 147, 151);
  background: -moz-linear-gradient(180deg, rgba(146, 147, 151, 1) 0%, rgba(79, 79, 85, 1) 100%);
  background: -webkit-linear-gradient(180deg, rgba(146, 147, 151, 1) 0%, rgba(79, 79, 85, 1) 100%);
  background: linear-gradient(180deg, rgba(146, 147, 151, 1) 0%, rgba(79, 79, 85, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#929397", endColorstr="#4f4f55", GradientType=1);
}

.cam-container-border {
  border-radius: 7px;
  background: rgb(99, 95, 110);
  background: -moz-linear-gradient(180deg, rgba(99, 95, 110, 1) 0%, rgba(99, 95, 110, 1) 47%, rgba(73, 69, 83, 1) 100%);
  background: -webkit-linear-gradient(180deg, rgba(99, 95, 110, 1) 0%, rgba(99, 95, 110, 1) 47%, rgba(73, 69, 83, 1) 100%);
  background: linear-gradient(180deg, rgba(99, 95, 110, 1) 0%, rgba(99, 95, 110, 1) 47%, rgba(73, 69, 83, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#635f6e", endColorstr="#494553", GradientType=1);
}

.cam-el .q-btn {
  background: #4f4f59 !important;
}
</style>
