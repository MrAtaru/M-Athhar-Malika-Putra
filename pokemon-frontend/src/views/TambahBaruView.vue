<template>
  <nav class="bg-white border-gray-200 dark:bg-gray-900">
    <div class="max-w-screen-2xl flex flex-wrap items-center justify-between mx-auto p-3">
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
        >
          <li>
            <router-link to="/">
              <div class="justify-start items-center gap-5 flex bg-red-600">
                <div class="w-8 h-8 relative">
                  <svg xmlns="http://www.w3.org/2000/svg" class="back-nav" width="32" height="33" viewBox="0 0 32 33" fill="none">
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M19.7533 3.23114L6.99968 16.5645L19.7533 29.8978L21.334 28.3858L10.0266 16.5645L21.334 4.7431L19.7533 3.23114Z"
                      fill="white"
                    />
                  </svg>
                </div>
                <div class="text-white bg-red-600 text-[28px] font-semibold capitalize">tambah baru</div>
              </div>
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <br />
  <br />
  <div class="a">
    <div class="a w-1440 h-[1100.56px] pb-[60px] bg-neutral-50 flex-col justify-start items-center gap-10 inline-flex">
      <div class="w-[1148px] justify-center items-start gap-[100px] inline-flex">
        <div class="flex-col justify-center items-center gap-[25.13px] inline-flex">
          <div class="w-60 h-60 relative">
            <div class="w-60 h-60 left-0 top-0 absolute bg-stone-50 rounded-full"></div>
            <div class="w-[60px] h-[60px] left-[89.50px] top-[90.06px] absolute">
              <div class="w-[60px] h-[52.50px] left-[0.01px] top-[3.75px] absolute"></div>
            </div>
          </div>
          <div class="w-60 h-60 bg-stone-50 rounded-full">
            <div class="w-14 h-14 relative">
              <div class="w-14 h-14 left-20 top-5 absolute">
                <svg xmlns="http://www.w3.org/2000/svg" class="img-tambah" width="61" height="61" viewBox="0 0 61 61" fill="none">
                  <g clip-path="url(#clip0_1616_8859)">
                    <path
                      d="M23.0078 21.2535C23.0078 22.7454 22.4152 24.1761 21.3603 25.231C20.3054 26.2859 18.8747 26.8785 17.3828 26.8785C15.891 26.8785 14.4602 26.2859 13.4053 25.231C12.3504 24.1761 11.7578 22.7454 11.7578 21.2535C11.7578 19.7617 12.3504 18.331 13.4053 17.2761C14.4602 16.2212 15.891 15.6285 17.3828 15.6285C18.8747 15.6285 20.3054 16.2212 21.3603 17.2761C22.4152 18.331 23.0078 19.7617 23.0078 21.2535Z"
                      fill="#E51C23"
                    />
                    <path
                      d="M8.00781 4.3786C6.01869 4.3786 4.11103 5.16878 2.70451 6.5753C1.29799 7.98182 0.507813 9.88948 0.507812 11.8786V49.3786C0.507813 51.3677 1.29799 53.2754 2.70451 54.6819C4.11103 56.0884 6.01869 56.8786 8.00781 56.8786H53.0078C54.9969 56.8786 56.9046 56.0884 58.3111 54.6819C59.7176 53.2754 60.5078 51.3677 60.5078 49.3786V11.8786C60.5078 9.88948 59.7176 7.98182 58.3111 6.5753C56.9046 5.16878 54.9969 4.3786 53.0078 4.3786H8.00781ZM53.0078 8.1286C54.0024 8.1286 54.9562 8.52369 55.6595 9.22695C56.3627 9.93021 56.7578 10.884 56.7578 11.8786V36.2536L42.5941 28.9524C42.2424 28.7762 41.8442 28.7151 41.4559 28.7777C41.0676 28.8403 40.7088 29.0234 40.4303 29.3011L26.5178 43.2136L16.5428 36.5686C16.1827 36.3288 15.7507 36.221 15.3201 36.2634C14.8895 36.3057 14.4868 36.4957 14.1803 36.8011L4.25781 45.6286V11.8786C4.25781 10.884 4.6529 9.93021 5.35616 9.22695C6.05942 8.52369 7.01325 8.1286 8.00781 8.1286H53.0078Z"
                      fill="#E51C23"
                    />
                  </g>
                  <defs>
                    <clipPath id="clip0_1616_8859">
                      <rect width="60" height="60" fill="white" transform="translate(0.5 0.628601)" />
                    </clipPath>
                  </defs>
                </svg>
              </div>
            </div>
          </div>
          <div class="text-center text-red-600 text-2xl font-semibold capitalize">tambah image</div>
        </div>
        <div class="grow shrink basis-0 flex-col justify-start items-start gap-8 inline-flex">
          <div
            class="self-stretch h-[677.78px] px-10 py-8 bg-white rounded-[20px] shadow flex-col justify-start items-start gap-5 flex"
          >
            <div class="text-red-600 text-[32px] font-semibold capitalize">Informasi umum</div>
            <div class="self-stretch h-[549.78px] flex-col justify-start items-start gap-5 flex">
              <div class="self-stretch h-[74.76px] flex-col justify-start items-start gap-[14.76px] flex">
                <div class="w-[243.47px] text-stone-500 text-xl font-medium capitalize">Nomor</div>
                <div class="w-[243.47px] text-stone-700 text-2xl font-semibold capitalize">#</div>
              </div>
              <div class="self-stretch h-[98.76px] flex-col justify-start items-start gap-[14.76px] flex">
                <div class="w-[243.47px] text-stone-500 text-xl font-medium capitalize">Nama</div>
                <div class="">
                  <input
                    class="text-stone-700 text-2xl bg-stone-50 border-0 font-semibold rounded-md capitalize"
                    type="text"
                    name=""
                    id=""
                  />
                </div>
              </div>
              <div class="self-stretch h-[98.76px] flex-col justify-start items-start gap-[14.76px] flex">
                <div class="w-[243.47px] text-stone-500 text-xl font-medium capitalize">types</div>
                <div class="self-stretch p-3 bg-stone-50 rounded-md justify-between items-center gap-1 inline-flex">
                  <div class="text-stone-700 text-2xl font-semibold capitalize"></div>
                  <div class="w-6 h-6 relative"></div>
                </div>
              </div>
              <div class="self-stretch h-[98.76px] flex-col justify-start items-start gap-[14.76px] flex">
                <div class="w-[243.47px] text-stone-500 text-xl font-medium capitalize">classification</div>
                <div class="self-stretch p-3 bg-stone-50 rounded-md justify-start items-center gap-1 inline-flex">
                  <div class="text-stone-700 text-2xl font-semibold capitalize"></div>
                  <div class="grow shrink basis-0 text-stone-500 text-xl font-medium capitalize"></div>
                  <div class="w-6 h-6 relative"></div>
                </div>
              </div>
              <div class="self-stretch h-[98.76px] flex-col justify-start items-start gap-[14.76px] flex">
                <div class="w-[243.47px] text-stone-500 text-xl font-medium capitalize">resistant</div>
                <div class="self-stretch p-3 bg-stone-50 rounded-md justify-between items-center gap-1 inline-flex">
                  <div class="text-stone-700 text-2xl font-semibold capitalize"></div>
                  <div class="w-6 h-6 relative"></div>
                </div>
              </div>
            </div>
          </div>
          <div class="self-stretch h-48 px-10 py-8 bg-white rounded-[20px] shadow flex-col justify-start items-start gap-5 flex">
            <div class="text-red-600 text-[32px] font-semibold capitalize">Evolution</div>
            <router-link to="/tambah-evolusi" class="">
              <div
                class="btn-evo self-stretch h-16 p-[22.13px] bg-red-600 rounded-[11.07px] justify-center items-center gap-[14.76px] inline-flex"
              >
                <div class="w-7 h-7 relative">
                  <div class="w-[2.80px] h-[22.40px] left-[12.60px] top-[2.80px] absolute bg-white"></div>
                  <div class="w-[22.40px] h-[2.80px] left-[2.80px] top-[12.60px] absolute bg-white"></div>
                </div>
                <div class="text-white text-2xl font-bold capitalize">tambah</div>
              </div>
            </router-link>
          </div>
        </div>
      </div>
      <div class="w-[1148px] pt-5 justify-end items-center gap-10 inline-flex">
        <div
          class="w-[200px] h-[73.78px] p-5 rounded-[11.07px] border border-red-600 justify-center items-center gap-[14.76px] flex"
        >
          <div class="text-red-600 text-2xl font-bold capitalize">Batal</div>
        </div>
        <div class="w-[200px] h-[73.78px] p-5 bg-neutral-400 rounded-[11.07px] justify-center items-center gap-[14.76px] flex">
          <div class="text-white text-2xl font-bold capitalize">tambah</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.back-nav {
  width: 32px;
  height: 32px;
  background-color: #e51c23;
}
nav {
  background-color: #e51c23;
}
.img-tambah {
  width: 60px;
  height: 60px;
  flex-shrink: 0;
}
.a {
  display: flex;
  width: 1440px;
  padding-bottom: 0px;
  flex-direction: column;
  align-items: center;
  gap: 40px;
}
.btn-evo {
  width: 800px;
  height: auto;
}
input {
  width: 800px;
}
</style>
