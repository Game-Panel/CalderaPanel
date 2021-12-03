<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-900">
    <div class="col-span-12">
      <div class="overflow-auto lg:overflow-visible ">
        <table class="table text-gray-400 border-separate space-y-6 text-sm">
          <thead class="bg-gray-800 text-gray-500">
          <tr>
            <th class="p-3">Name</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Action</th>
          </tr>
          </thead>
          <tbody>
          <tr class="bg-gray-800">
            <td class="p-3">
              <div class="flex align-items-center">
                <img class="h-12 w-12 object-cover" src="https://th.bing.com/th/id/R.691cd51deb84f6c8481fc902a99d9a5d?rik=5q3OcZTrwhSllg&riu=http%3a%2f%2fvignette3.wikia.nocookie.net%2fgmod%2fimages%2f3%2f36%2fGMod_Logo.png%2frevision%2flatest%3fcb%3d20160506003715&ehk=0qUEBmhhlfF6lNjxMUaBA1p2dOFTL7UQGjcL2vKWv7c%3d&risl=&pid=ImgRaw&r=0" alt="egg icon">
                <div class="ml-3">
                  <div class="">Agent Arthur</div>
                  <div class="text-gray-500">Arthur's agent server</div>
                </div>
              </div>
            </td>
            <td class="p-3 font-bold">
              20.00$
            </td>
            <td class="p-3">
              <span class="bg-green-400 text-gray-50 rounded-md px-2">available</span>
            </td>
            <td class="p-3 ">
              <RouterLink to="/server/1/view" class="text-gray-400 hover:text-gray-100 mr-2">
                <i class="material-icons-outlined text-base">visibility</i>
              </RouterLink>
            </td>
          </tr>
          <tr class="bg-gray-800">
            <td class="p-3">
              <div class="flex align-items-center">
                <img class="h-12 w-12 object-cover" src="https://th.bing.com/th/id/R.691cd51deb84f6c8481fc902a99d9a5d?rik=5q3OcZTrwhSllg&riu=http%3a%2f%2fvignette3.wikia.nocookie.net%2fgmod%2fimages%2f3%2f36%2fGMod_Logo.png%2frevision%2flatest%3fcb%3d20160506003715&ehk=0qUEBmhhlfF6lNjxMUaBA1p2dOFTL7UQGjcL2vKWv7c%3d&risl=&pid=ImgRaw&r=0" alt="egg icon">
                <div class="ml-3">
                  <div class="">Agent Arthur</div>
                  <div class="text-gray-500">Arthur's agent server</div>
                </div>
              </div>
            </td>
            <td class="p-3 font-bold">
              20.00$
            </td>
            <td class="p-3">
              <span class="bg-red-400 text-gray-50 rounded-md px-2">required payment</span>
            </td>
            <td class="p-3 ">
              <RouterLink to="/server/1/view" class="text-gray-400 hover:text-gray-100 mr-2">
                <i class="material-icons-outlined text-base">visibility</i>
              </RouterLink>
            </td>
          </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.table {
  border-spacing: 0 15px;
}

i {
  font-size: 1rem !important;
}

.table tr {
  border-radius: 20px;
}

tr td:nth-child(n+5),
tr th:nth-child(n+5) {
  border-radius: 0 .625rem .625rem 0;
}

tr td:nth-child(1),
tr th:nth-child(1) {
  border-radius: .625rem 0 0 .625rem;
}
</style>
