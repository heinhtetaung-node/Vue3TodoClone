<template>
  <div class="container mx-auto">
    <h1 class="mt-8 text-2xl">Todos</h1>

    <div class="mt-3">
      <div class="grid grid-cols-12 gap-4">
        <div class="col-span-6 space-y-4 overflow-y-auto px-1"
             style="height: 500px">
          <div class="p-8 bg-white shadow-md rounded flex items-center justify-between"">
            <div>
              <div> Sample Todo </div>
              <div class="text-gray-500 text-sm">2020/01/01</div>
            </div>
            <div class="space-x-2">
              <button class="px-2 text-red-600" title="Remove todo">&times;</button>
              <button class="px-2 text-green-600" title="Mark as done">&check;</button>
              <button class="px-2 text-orange-600" title="Mark as undone">&#8630;</button>
            </div>
          </div>
          <div class="px-8 py-16 bg-white text-gray-700 shadow-md rounded text-sm">
            You dont have any task to do.
          </div>
        </div>

        <div class="col-span-6">
          <div class="p-8 bg-white shadow-md rounded">
            <h2 class="text-xl">Add a todo</h2>
            <input type="text"
                   class="p-2 mt-4 border rounded w-full">
          </div>
        </div>
      </div>
    </div>
  </div>

</template>