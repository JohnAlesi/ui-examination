<template>
  <div>
    <Nav />
    <div
      class="block gap-4 relative mx-auto w-full lg:py-6 lg:flex xl:w-11/12 3xl:w-10/12"
    >
      <SideBar />
      <!--Banner Starts here-->
      <div class="w-full lg:w-11/12 3xl:w-11/12">
        <Banner />
        <!--Profile Details Starts here-->
        <div class="flex flex-col gap-x-4 lg:flex-row">
          <!--General Details starts here-->
          <div class="bg-white rounded shadow w-full h-min lg:w-11/12">
            <!--First column-->
            <GenTitle />
            <!--2nd Column-->
            <GeneralDetails />
            <!--3rd Column-->
            <ProfessionalStatus />
            <!--4th-->
            <Preferences />
          </div>
          <!--Side Column-->
          <SideColumn />
        </div>
      </div>
    </div>
  </div>
</template>
