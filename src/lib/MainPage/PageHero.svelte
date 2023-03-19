<script>
  $: isHover = 1;
</script>

<div class="hero min-h-screen heroImg border-t-2 border-emerald-500">
  <div
    class="hero-content flex-col lg:flex-row-reverse code backdrop-blur-sm rounded-2xl border-2 border-slate-900  p-4 mx-4  lg:p-8 shadow-2xl shadow-slate-600 h-96 md:h-[400px] lg:h-[500px] "
  >
    <!-- svelte-ignore a11y-missing-attribute -->
    <img
      src="https://img.freepik.com/free-vector/trading-linear-design_1284-36136.jpg?w=996&t=st=1679246561~exp=1679247161~hmac=ba3dc70dc5028383fe0f980613c87bc12b1da4627f36d42aa1d0a3bb60c56716"
      class="max-w-sm rounded-3xl hidden md:block transition-all duration-200  imgShadow border-2 border-slate-900 md:h-96 md:w-[450px] hover:-translate-y-3 hover:-translate-x-3"
      on:mouseenter={() => {
        isHover = 2;
      }}
      on:mouseleave={() => {
        isHover = 1;
      }}
    />
    <div>
      <h1
        class="text-5xl font-bold text-slate-900 transition-all duration-200 {isHover ===
        2
          ? 'text-5xl font-bold text-[#000] md:translate-x-56'
          : ' '} "
      >
        Box Office News!
      </h1>
      <p class="py-6 md:text-xl text-slate-900">
        Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda
        excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a
        id nisi.
      </p>
      <button class="btn btn-primary">Get Started</button>
    </div>
  </div>
</div>

<style lang="postcss">
  .heroImg {
    background-image: url("https://img.freepik.com/free-vector/trading-linear-design_1284-36136.jpg?w=996&t=st=1679246561~exp=1679247161~hmac=ba3dc70dc5028383fe0f980613c87bc12b1da4627f36d42aa1d0a3bb60c56716");
    background-size: cover;
    background-position: center;
  }
  .code {
    background: #1aa6f73e !important;
  }
  .imgShadow:hover {
    box-shadow: 7px 7px #000b47;
  }
</style>
