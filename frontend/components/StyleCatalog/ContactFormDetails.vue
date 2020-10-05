<template>
  <section class="py-12 px-4">
    <h2 class="text-3xl mb-8 text-center font-heading">
      Contact the Scranton team
    </h2>
    <div class="w-full max-w-2xl mx-auto mb-12">
      <form>
        <div class="flex mb-4 -mx-2">
          <div class="w-1/2 px-2">
            <input
              class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
              type="email"
              placeholder="Email"
            />
          </div>
          <div class="w-1/2 px-2">
            <select
              class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            >
              <option>-- Select product --</option>
              <option>Product 1</option>
              <option>Product 2</option>
              <option>Product 3</option>
            </select>
          </div>
        </div>
        <div class="mb-4">
          <textarea
            class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none"
            placeholder="Write something..."
            rows="5"
          ></textarea>
        </div>
        <div>
          <button
            class="inline-block w-full py-4 px-8 leading-none text-white bg-indigo-500 hover:bg-indigo-600 rounded shadow"
          >
            Submit
          </button>
        </div>
      </form>
    </div>
    <div class="flex flex-col lg:flex-row lg:justify-center -mx-4">
      <div class="px-4">
        <img
          class="inline-block w-8 h-8 pr-2"
          src="placeholders/icons/home.svg"
          alt=""
        /><span>1725 Slough Avenue, Scranton</span>
      </div>
      <div class="px-4">
        <img
          class="inline-block w-8 h-8 pr-2"
          src="placeholders/icons/mobile.svg"
          alt=""
        /><span>555-111-555</span>
      </div>
      <div class="px-4">
        <img
          class="inline-block w-8 h-8 pr-2"
          src="placeholders/icons/message.svg"
          alt=""
        /><span>scranton@dundermifflin.com</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>
