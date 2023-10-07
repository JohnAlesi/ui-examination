<template>
  <!--Side Column-->
  <div class="flex-flex-col gap-y-4 w-full lg:w-4/12">
    <div class="bg-white rounded shadow mb-4">
      <div class="flex items-center justify-between py-4 px-5 text-gray-700">
        <p class="font-semibold">Video Introduction</p>
      </div>
      <img src="/video.jpg" class="w-full object-contain p-0" />
    </div>
    <div class="bg-white rounded shadow mb-4">
  <div class="px-3 py-4 text-center">
    <p class="font-semibold text-gray-700">Profile Completion <span class="pl-8 font font-semibold text-green-500 w-1/2"> 100%</span></p>
    <div class="flex items-center justify-center">
      <div class="overflow-hidden text-xs flex rounded-full bg-gray-200 w-full" style="height: 8px;">
        <div class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-green-500" style="width: 100%;"></div>
      </div>
    </div>
    <p class="text-green-500 text-center mt-4">Well done, Reyven!</p>
    <div class="flex items-center justify-center">
      <img src="/award.jpg" width="140" class="items-center flex flex-col justify-center" />
    </div>
    <p class="text-gray-700 text-justify">You have one of the strongest professional profiles in our talent pool. Expect progress on your application at any time soon.</p>
  </div>
</div>

    <div class="bg-white rounded shadow mt-6 md:mt-0">
      <div class="px-3 py-4">
        <p class="font-semibold text-gray-700">Profile Completion <span
            class="pl-8 font font-semibold text-green-500 w-1/2"> 50%</span></p>
        <div class="flex items-center">
          <div class="overflow-hidden text-xs flex rounded-full bg-gray-200 w-full" style="height: 8px;">
            <div class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-green-500"
              style="width: 50%;" />
          </div>
        </div>
      </div>
      <div class=" relative px-3 pb-8">
        <div class="flex items-center w-full text-gray-700">
          <svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="chevron-up" role="img"
            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
            class="cursor-pointer svg-inline--fa fa-chevron-up fa-fw">
            <path fill="currentColor"
              d="M244.7 116.7c6.2-6.2 16.4-6.2 22.6 0l192 192c6.2 6.2 6.2 16.4 0 22.6s-16.4 6.2-22.6 0L256 150.6 75.3 331.3c-6.2 6.2-16.4 6.2-22.6 0s-6.2-16.4 0-22.6l192-192z"
              class=""></path>
          </svg>
          <span class="font-normal mr-auto ml-2">Hide Recommendations</span>
        </div>
        <div class="mt-3 ml-7">
          <p class="text-gray-700 mb-1">Fill-up the following items to strengthen your profile. This can help us in
            matching your profile and increase your chances of landing into your desired role.</p>
          <ul class="text-base ml-6 list-disc text-gray-700">
            <li>Share
              <span class="text-primary font-semibold clickable">Date of Birth</span>
            </li>
            <li>Specify
              <span class="text-primary font-semibold clickable">Current Monthly Salary</span>
            </li>
            <li>Add one(1)
              <span class="text-primary font-semibold clickable">Character Reference</span>
            </li>
            <li>Add
              <span class="text-primary font-semibold clickable">Current Address</span>
            </li>
            <li>Add atleast five(5) items in
              <span class="text-primary font-semibold clickable">Other Skills </span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>