<script>
  $: isHover = 1;
</script>

<div class="hero min-h-screen heroImg border-t-2 border-emerald-500">
  <div
    class="hero-content flex-col lg:flex-row-reverse code backdrop-blur-[5px] rounded-2xl border-2 border-slate-900  p-4 mx-4  lg:p-8 shadow-2xl shadow-slate-600 h-96 md:h-[400px] lg:h-[500px] "
  >
    <div>
      <h1
        class="text-5xl font-bold text-center text-black txt transition-all duration-200 "
      >
        Option Analysis
      </h1>
      <p class="py-6 md:text-xl text-slate-900 txt text-center">
        You can use this tool to analyze the option prices and find the best
        option for your strategy. You Can Learn from Charts & Previous Mistakes
        and Make Better Decisions.
      </p>
      <div class="text-center ">
        <a href="/#products">
          <button
            class="btn btn-primary hover:bg-transparent hover:text-black  text-center"
            >Get Started</button
          >
        </a>
      </div>
    </div>
  </div>
</div>

<style lang="postcss">
  .heroImg {
    background-image: url("https://images.pexels.com/photos/6801648/pexels-photo-6801648.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1");
    background-size: cover;
    background-position: center;
  }
  .code {
    background: #f8f8f817 !important;
  }
  /* .imgShadow:hover {
    box-shadow: 7px 7px #000b47;
  } */
  .txt {
    text-shadow: 0px 0px 5px #000b4753;
  }
</style>
