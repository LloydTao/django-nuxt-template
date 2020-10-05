<template>
  <section class="py-8">
    <div class="w-full max-w-sm mx-auto">
      <form>
        <div class="mb-4">
          <input
            class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            type="text"
            placeholder="Email"
          />
        </div>
        <div class="mb-4">
          <input
            class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            type="password"
            placeholder="Password"
          />
        </div>
        <div class="mb-4">
          <label class="text-gray-500">
            <input class="mr-2 leading-tight" type="checkbox" />
            <span class="text-sm">Send me your newsletter!</span>
          </label>
        </div>
        <div class="mb-4">
          <button
            class="inline-block w-full py-4 px-8 leading-none text-white bg-indigo-500 hover:bg-indigo-600 rounded shadow"
          >
            Sign up
          </button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
export default {}
</script>
