<template>
  <div class="LandingPage">
    <div class="checkoutBlock">
      <div class="heading">Checkout</div>
      <div class="steps">
        <div :class="tab === 0 ? 'step active' : 'step'">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px" viewBox="0 0 482.9 482.9" style="enable-background:new 0 0 482.9 482.9;" xml:space="preserve" > <g> <g> <path d="M239.7,260.2c0.5,0,1,0,1.6,0c0.2,0,0.4,0,0.6,0c0.3,0,0.7,0,1,0c29.3-0.5,53-10.8,70.5-30.5    c38.5-43.4,32.1-117.8,31.4-124.9c-2.5-53.3-27.7-78.8-48.5-90.7C280.8,5.2,262.7,0.4,242.5,0h-0.7c-0.1,0-0.3,0-0.4,0h-0.6    c-11.1,0-32.9,1.8-53.8,13.7c-21,11.9-46.6,37.4-49.1,91.1c-0.7,7.1-7.1,81.5,31.4,124.9C186.7,249.4,210.4,259.7,239.7,260.2z     M164.6,107.3c0-0.3,0.1-0.6,0.1-0.8c3.3-71.7,54.2-79.4,76-79.4h0.4c0.2,0,0.5,0,0.8,0c27,0.6,72.9,11.6,76,79.4    c0,0.3,0,0.6,0.1,0.8c0.1,0.7,7.1,68.7-24.7,104.5c-12.6,14.2-29.4,21.2-51.5,21.4c-0.2,0-0.3,0-0.5,0l0,0c-0.2,0-0.3,0-0.5,0    c-22-0.2-38.9-7.2-51.4-21.4C157.7,176.2,164.5,107.9,164.6,107.3z" /> <path d="M446.8,383.6c0-0.1,0-0.2,0-0.3c0-0.8-0.1-1.6-0.1-2.5c-0.6-19.8-1.9-66.1-45.3-80.9c-0.3-0.1-0.7-0.2-1-0.3    c-45.1-11.5-82.6-37.5-83-37.8c-6.1-4.3-14.5-2.8-18.8,3.3c-4.3,6.1-2.8,14.5,3.3,18.8c1.7,1.2,41.5,28.9,91.3,41.7    c23.3,8.3,25.9,33.2,26.6,56c0,0.9,0,1.7,0.1,2.5c0.1,9-0.5,22.9-2.1,30.9c-16.2,9.2-79.7,41-176.3,41    c-96.2,0-160.1-31.9-176.4-41.1c-1.6-8-2.3-21.9-2.1-30.9c0-0.8,0.1-1.6,0.1-2.5c0.7-22.8,3.3-47.7,26.6-56    c49.8-12.8,89.6-40.6,91.3-41.7c6.1-4.3,7.6-12.7,3.3-18.8c-4.3-6.1-12.7-7.6-18.8-3.3c-0.4,0.3-37.7,26.3-83,37.8    c-0.4,0.1-0.7,0.2-1,0.3c-43.4,14.9-44.7,61.2-45.3,80.9c0,0.9,0,1.7-0.1,2.5c0,0.1,0,0.2,0,0.3c-0.1,5.2-0.2,31.9,5.1,45.3    c1,2.6,2.8,4.8,5.2,6.3c3,2,74.9,47.8,195.2,47.8s192.2-45.9,195.2-47.8c2.3-1.5,4.2-3.7,5.2-6.3    C447,415.5,446.9,388.8,446.8,383.6z" /> </g> </g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> </svg>
          <span class="stepName">DETAIL</span>
        </div>
        <div :class="tab === 1 ? 'step active' : 'step'">
          <svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve" > <g> <g> <path d="M458.667,85.333H53.333C23.936,85.333,0,109.269,0,138.667v234.667c0,29.397,23.936,53.333,53.333,53.333h405.333 c29.397,0,53.333-23.936,53.333-53.333V138.667C512,109.269,488.064,85.333,458.667,85.333z M490.667,373.333 c0,17.643-14.357,32-32,32H53.333c-17.643,0-32-14.357-32-32V138.667c0-17.643,14.357-32,32-32h405.333c17.643,0,32,14.357,32,32 V373.333z" /> </g> </g> <g> <g> <path d="M501.333,149.333H10.667C4.779,149.333,0,154.112,0,160v64c0,5.888,4.779,10.667,10.667,10.667h490.667 c5.888,0,10.667-4.779,10.667-10.667v-64C512,154.112,507.221,149.333,501.333,149.333z M490.667,213.333H21.333v-42.667h469.333 V213.333z" /> </g> </g> <g> <g> <path d="M202.667,298.667h-128c-5.888,0-10.667,4.779-10.667,10.667S68.779,320,74.667,320h128 c5.888,0,10.667-4.779,10.667-10.667S208.555,298.667,202.667,298.667z" /> </g> </g> <g> <g> <path d="M202.667,341.333h-128C68.779,341.333,64,346.112,64,352c0,5.888,4.779,10.667,10.667,10.667h128 c5.888,0,10.667-4.779,10.667-10.667C213.333,346.112,208.555,341.333,202.667,341.333z" /> </g> </g> <g> <g> <path d="M416,277.333h-21.333c-17.643,0-32,14.357-32,32v21.333c0,17.643,14.357,32,32,32H416c17.643,0,32-14.357,32-32v-21.333 C448,291.691,433.643,277.333,416,277.333z M426.667,330.667c0,5.888-4.779,10.667-10.667,10.667h-21.333 c-5.888,0-10.667-4.779-10.667-10.667v-21.333c0-5.888,4.779-10.667,10.667-10.667H416c5.888,0,10.667,4.779,10.667,10.667 V330.667z" /> </g> </g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> <g></g> </svg>
          <span class="stepName">PAYMENT</span>
        </div>
        <div :class="tab === 2 ? 'step active' : 'step'">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Layer_1" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <g> <g> <path d="M504.502,75.496c-9.997-9.998-26.205-9.998-36.204,0L161.594,382.203L43.702,264.311c-9.997-9.998-26.205-9.997-36.204,0    c-9.998,9.997-9.998,26.205,0,36.203l135.994,135.992c9.994,9.997,26.214,9.99,36.204,0L504.502,111.7    C514.5,101.703,514.499,85.494,504.502,75.496z"/> </g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> <g> </g> </svg>
          <span class="stepName">SUCCESS</span>
        </div>
      </div>
      <detail v-if="tab === 0" @next="handlePageChange" />
      <payment v-else-if="tab === 1" @next="handlePageChange" />
      <success v-else />
    </div>
  </div>
</template>

<script>
import Detail from "../Detail/Detail";
import Payment from "../Payment/Payment";
import Success from "../Success/Success";
export default {
  components: { Detail, Payment, Success },
  name: "LandingPage",
  data() {
    return {
      tab: 0,
    };
  },
  methods: {
    handlePageChange(page) {
      this.tab = page;
    },
  },
};
</script>

<style lang="scss" scoped>
div[class="LandingPage"] {
  background-image: linear-gradient(45deg, #4e59f3, #6c46e8);
  min-height: 100vh;
  div[class="checkoutBlock"] {
    height: 80%;
    width: 500px;
    background-color: #ffffff;
    top: 50%;
    left: 50%;
    position: absolute;
    transform: translate(-50%, -50%);
    border-radius: 6px;
    div[class="heading"] {
      font-size: 1.5em;
      font-weight: 700;
      padding: 1.5em 2em;
    }
    div[class="steps"] {
      border: 1px solid #c5c5c5;
      padding: 1em;
      display: flex;
      align-items: center;
      justify-content: space-evenly;
      .step {
        display: flex;
        align-items: center;
        font-size: 1em;
        font-weight: 700;
        letter-spacing: 1px;
        color: #c0c0c0;
        svg {
          height: 25px;
          margin-right: 0.8em;
          stroke-width: 5%;
          fill: #c0c0c0;
        }
      }
      .active {
        color: #4e59f3;
        svg {
          fill: #4e59f3;
        }
      }
    }
  }
}
</style>
