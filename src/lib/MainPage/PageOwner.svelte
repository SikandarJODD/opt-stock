<script>
  import Owner from "$lib/owner.jpg";
</script>

<div class="bg-white  sm:py-8 lg:py-12" id="profile">
  <div class="mx-auto max-w-screen-2xl px-4 md:px-8  mb-5">
    <!-- quote - start -->
    <div class="flex flex-col items-center gap-4 md:gap-6">
      <div class="max-w-md text-center text-gray-600 lg:text-lg">
        “The Key to Trading Success is <span class=" text-slate-900"
          >Emotional Discipline</span
        > ”
      </div>

      <div class="flex flex-col items-center gap-2 sm:flex-row md:gap-3">
        <div
          class="h-12 w-12 overflow-hidden rounded-full bg-gray-100 shadow-lg md:h-14 md:w-14"
        >
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img
            src={Owner}
            loading="lazy"
            alt="Photo by Radu Florin"
            class="h-full w-full object-cover object-center"
          />
        </div>

        <div>
          <div
            class="text-center text-sm font-bold text-indigo-500 sm:text-left md:text-base"
          >
            Rahul Wagh
          </div>
          <p class="text-center text-sm text-gray-500 sm:text-left md:text-sm">
            Founder of Stockify
          </p>
        </div>
      </div>
    </div>
    <!-- quote - end -->
  </div>
</div>
