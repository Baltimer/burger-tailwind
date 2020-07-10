<template>
  <div class="home">
    <section class="relative overflow-hidden h-64 lg:h-88 xl:h-104 bg-gray-700">
      <img class="object-cover h-full w-full" src="@/assets/img/home-burger.jpg" alt="home-burger" />
    </section>
    <section class="text-gray-700 body-font">
      <div class="container px-5 py-12 mx-auto">
        <div class="text-center mb-20">
          <h1
            class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4"
          >Las mejores hamburguesas de Mallorca</h1>
          <p
            class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto"
          >Elegimos la carne más fresca y el pan recién horneado cada día para que puedas disfrutar de la hamburguesa perfecta en el momento perfecto.</p>
          <div class="flex mt-6 justify-center">
            <div class="w-16 h-1 rounded-full bg-indigo-500 inline-flex"></div>
          </div>
        </div>
        <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4">
          <div class="p-4 md:w-1/3 md:mb-0 mb-6 flex flex-col text-center items-center">
            <div
              class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0"
            >
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-10 h-10"
                viewBox="0 0 24 24"
              >
                <path d="M22 12h-4l-3 9L9 3l-3 9H2" />
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">La carne</h2>
              <p
                class="leading-relaxed text-base"
              >La carne es entregada cada día en nuestro restaurante por proveedores locales.</p>
            </div>
          </div>
          <div class="p-4 md:w-1/3 md:mb-0 mb-6 flex flex-col text-center items-center">
            <div
              class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0"
            >
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-10 h-10"
                viewBox="0 0 24 24"
              >
                <circle cx="6" cy="6" r="3" />
                <circle cx="6" cy="18" r="3" />
                <path d="M20 4L8.12 15.88M14.47 14.48L20 20M8.12 8.12L12 12" />
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">El pan</h2>
              <p
                class="leading-relaxed text-base"
              >El pan recién horneado es el secreto. Disfruta de su crujiente masa y sus ingredientes 100% naturales.</p>
            </div>
          </div>
          <div class="p-4 md:w-1/3 md:mb-0 mb-6 flex flex-col text-center items-center">
            <div
              class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0"
            >
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-10 h-10"
                viewBox="0 0 24 24"
              >
                <path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2" />
                <circle cx="12" cy="7" r="4" />
              </svg>
            </div>
            <div class="flex-grow">
              <h2 class="text-gray-900 text-lg title-font font-medium mb-3">El servicio</h2>
              <p
                class="leading-relaxed text-base"
              >El personal del restaurante está altamente cualificado para poder atender todas tus necesidades.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-700 body-font">
      <div class="container px-5 py-12 mx-auto">
        <div class="flex flex-col text-center w-full mb-20">
          <h2
            class="text-xs text-indigo-500 tracking-widest font-medium title-font mb-1"
          >NUESTRO COMPROMISO</h2>
          <h1
            class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900"
          >CARNE 100% DE ORIGEN LOCAL</h1>
          <p
            class="lg:w-2/3 mx-auto leading-relaxed text-base"
          >Compramos la carne directamente a proveedores locales, sin intermediarios. Gracias a ello, podemos mantener los precios más económicos y aprovechar la mejor calidad.</p>
        </div>
        <div class="flex flex-wrap">
          <div class="xl:w-1/4 lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-200">
            <h2 class="text-lg sm:text-xl text-gray-900 font-medium title-font mb-2">Hamburguesas</h2>
            <p
              class="leading-relaxed text-base mb-4"
            >Disfruta de una gran variedad de hamburguesas. Cada 3 meses renovamos la carta e introducimos nuevas recetas para que nunca te aburras.</p>
            <a class="text-indigo-500 inline-flex items-center">
              Conoce más
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-4 h-4 ml-2 mt-1"
                viewBox="0 0 24 24"
              >
                <path d="M5 12h14M12 5l7 7-7 7" />
              </svg>
            </a>
          </div>
          <div class="xl:w-1/4 lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-200">
            <h2 class="text-lg sm:text-xl text-gray-900 font-medium title-font mb-2">Entrantes</h2>
            <p class="leading-relaxed text-base mb-4">
              Disfruta de unos
              <span class="font-semibold">nachos corner</span> o unos
              <span class="font-semibold">fingers de pollo</span> mientras esperas tu deliciosa hamburguesa.
            </p>
            <a class="text-indigo-500 items-center mt-auto flex">
              Conoce más
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-4 h-4 ml-2 mt-1"
                viewBox="0 0 24 24"
              >
                <path d="M5 12h14M12 5l7 7-7 7" />
              </svg>
            </a>
          </div>
          <div class="xl:w-1/4 lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-200">
            <h2 class="text-lg sm:text-xl text-gray-900 font-medium title-font mb-2">Neptune</h2>
            <p
              class="leading-relaxed text-base mb-4"
            >Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.</p>
            <a class="text-indigo-500 inline-flex items-center">
              Learn More
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-4 h-4 ml-2 mt-1"
                viewBox="0 0 24 24"
              >
                <path d="M5 12h14M12 5l7 7-7 7" />
              </svg>
            </a>
          </div>
          <div class="xl:w-1/4 lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-200">
            <h2 class="text-lg sm:text-xl text-gray-900 font-medium title-font mb-2">Melanchole</h2>
            <p
              class="leading-relaxed text-base mb-4"
            >Fingerstache flexitarian street art 8-bit waistcoat. Distillery hexagon disrupt edison bulbche.</p>
            <a class="text-indigo-500 inline-flex items-center">
              Learn More
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-4 h-4 ml-2 mt-1"
                viewBox="0 0 24 24"
              >
                <path d="M5 12h14M12 5l7 7-7 7" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-700 body-font">
      <div class="container px-5 py-24 mx-auto flex flex-wrap">
        <div class="flex w-full mb-20 flex-wrap">
          <h1
            class="sm:text-3xl text-2xl font-medium title-font text-gray-900 lg:w-1/3 lg:mb-0 mb-4"
          >Galería</h1>
          <p
            class="lg:pl-6 lg:w-2/3 mx-auto leading-relaxed text-base"
          >Disfruta de una selección de las mejores instantáneas de nuestro restaurante.</p>
        </div>
        <div class="flex flex-wrap md:-m-2 -m-1">
          <div class="flex flex-wrap w-full md:w-1/2">
            <div class="md:p-2 p-1 w-1/2">
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block"
                src="https://dummyimage.com/500x300"
              />
            </div>
            <div class="md:p-2 p-1 w-1/2">
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block"
                src="https://dummyimage.com/501x301"
              />
            </div>
            <div class="md:p-2 p-1 w-full">
              <img
                alt="gallery"
                class="w-full h-full object-cover object-center block"
                src="https://dummyimage.com/600x360"
              />
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/2">
            <div class="md:p-2 p-1 w-full">
              <img
                alt="gallery"
                class="w-full h-full object-cover object-center block"
                src="https://dummyimage.com/601x361"
              />
            </div>
            <div class="md:p-2 p-1 w-1/2">
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block"
                src="https://dummyimage.com/502x302"
              />
            </div>
            <div class="md:p-2 p-1 w-1/2">
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block"
                src="https://dummyimage.com/503x303"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-700 body-font relative">
      <div class="container px-5 py-12 mx-auto flex sm:flex-no-wrap flex-wrap">
        <div
          class="lg:w-2/3 md:w-1/2 bg-gray-300 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative"
        >
          <iframe
            class="absolute inset-0"
            style="filter: grayscale(1) contrast(1.2) opacity(0.6);"
            title="map"
            marginheight="0"
            marginwidth="0"
            scrolling="no"
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1537.507968429657!2d2.6616494301549114!3d39.58179119431163!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x129793ced07b6155%3A0x72d06fa27104b3e2!2sTCB%20The%20C%C3%B3rner%20Burger!5e0!3m2!1sen!2sus!4v1594421264189!5m2!1sen!2sus"
            width="100%"
            height="100%"
            frameborder="0"
          ></iframe>
          <div class="bg-white relative flex flex-wrap py-6">
            <div class="lg:w-1/2 px-6">
              <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm">DIRECCIÓN</h2>
              <p
                class="leading-relaxed"
              >Jacinto Verdaguer, 33.</p>
              <p
                class="leading-relaxed"
              >Palma de Mallorca, Islas Baleares, 07004</p>
            </div>
            <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
              <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm">EMAIL</h2>
              <a class="text-indigo-500 leading-relaxed">info@thecornerburger.com</a>
              <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mt-4">TELEFONO</h2>
              <p class="leading-relaxed">666-55-44-33</p>
            </div>
          </div>
        </div>
        <div
          class="lg:w-1/3 md:w-1/2 bg-white flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0"
        >
          <h2 class="text-gray-900 text-lg mb-1 font-medium title-font">Sugerencias</h2>
          <p
            class="leading-relaxed mb-5 text-gray-600"
          >Tienes una sugerencias? No dudes en ponerte en contacto con nosotros.</p>
          <input
            class="bg-white rounded border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-4 py-2 mb-4"
            placeholder="Nombre"
            type="text"
          />
          <input
            class="bg-white rounded border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-4 py-2 mb-4"
            placeholder="Teléfono"
            type="email"
          />
          <textarea
            class="bg-white rounded border border-gray-400 focus:outline-none h-32 focus:border-indigo-500 text-base px-4 py-2 mb-4 resize-none"
            placeholder="Mensaje"
          ></textarea>
          <button
            class="text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg"
          >Enviar</button>
          <p
            class="text-xs text-gray-500 mt-3"
          >Sus datos no serán almacenados ni utilizados para otros fines más que para ponernos en contacto con usted si fuese necesario.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home"
};
</script>
