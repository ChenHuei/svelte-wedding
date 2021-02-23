<section
  class="banner relative w-full h-screen bg-fixed bg-cover bg-no-repeat bg-center"
>
  <div
    class="banner-info absolute top-1/2 left-1/2 flex flex-col justify-center items-center bg-white"
  >
    <h4 class="text-3xl font-bold mb-2">Huei & Bei</h4>
    <h4 class="text-3xl">Ｄecember, 11, 2021</h4>
  </div>
</section>

<style lang="scss">
  .banner {
    background-image: url("https://images.unsplash.com/photo-1460978812857-470ed1c77af0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1458&q=80");

    &-info {
      width: 715px;
      height: 640px;
      transform: translate(-50%, -50%);
      clip-path: polygon(
        0% 15%,
        15% 15%,
        15% 0%,
        85% 0%,
        85% 15%,
        100% 15%,
        100% 85%,
        85% 85%,
        85% 100%,
        15% 100%,
        15% 85%,
        0% 85%
      );
    }
  }
</style>
