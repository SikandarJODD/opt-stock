<script>
  import Stock from "$lib/stock.gif";
  import Stock2 from "$lib/stock2.gif";
</script>

<section class="text-gray-600 body-font border-b-2 border" id="products">
  <div class="container px-5 py-12  md:py-24 mx-auto">
    <div class="text-center mb-10">
      <h1 class="sm:text-4xl font-bold text-3xl  title-font text-gray-900 mb-4">
        Learn with our AI
      </h1>
      <p
        class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500 hidden md:block"
      >
        Blue bottle crucifix vinyl post-ironic four dollar toast vegan
        taxidermy. Gastropub indxgo juice poutine, ramps microdosing banh mi
        pug.
      </p>
      <div class="flex mt-6 justify-center">
        <div class="w-24 h-1 rounded-full bg-blue-500 inline-flex" />
      </div>
    </div>
    <div
      class="flex flex-wrap sm:-m-4 -mx-4 mb-10 -mt-4 md:space-y-0 space-y-6 text-center justify-center align-middle "
    >
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center  rounded-full bg-blue-100 text-blue-500 mb-5 flex-shrink-0"
        >
          <img src={Stock} alt="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Stock Analysis
          </h2>

          <!-- svelte-ignore a11y-missing-attribute -->
          <a class="mt-3 text-blue-500 inline-flex items-center"
            >Comming Soon
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-4 h-4 ml-2"
              viewBox="0 0 24 24"
            >
              <path d="M5 12h14M12 5l7 7-7 7" />
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-blue-100 text-blue-500 mb-5 flex-shrink-0"
        >
          <img
            src="https://cdn-icons-png.flaticon.com/512/2737/2737448.png"
            alt=""
          />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            <u>Trained AI</u> For Mistakes Analysis
          </h2>

          <!-- svelte-ignore a11y-missing-attribute -->
          <a class="mt-3 text-blue-500 inline-flex items-center"
            >Comming Soon
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-4 h-4 ml-2"
              viewBox="0 0 24 24"
            >
              <path d="M5 12h14M12 5l7 7-7 7" />
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-blue-100 text-blue-500 mb-5 flex-shrink-0"
        >
          <img
            src="https://cdn-icons-png.flaticon.com/512/2207/2207346.png"
            alt=""
          />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Neptune
          </h2>

          <!-- svelte-ignore a11y-missing-attribute -->
          <a class="mt-3 text-blue-500 inline-flex items-center"
            >Learning Path & Charts
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-4 h-4 ml-2"
              viewBox="0 0 24 24"
            >
              <path d="M5 12h14M12 5l7 7-7 7" />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</section>
