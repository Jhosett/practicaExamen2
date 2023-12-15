<script setup>

</script>

<template>
  <div class="mx-[25%] my-[5%]">

    <div class="bg-blue-200 p-8 mx-auto w-[50%] mb-10">
      <p class="mt-2 mb-6 font-bold text-center text-2xl">CARRITO DE COMPRAS</p>
      <img class="w-[60%] h-[30%] mx-auto rounded-lg mb-3" src="https://m.media-amazon.com/images/I/615HyRBj-FL._AC_SY500_.jpg" alt="">
      <ul class="mb-4 text-center">
        <li>

        </li>
      </ul>
      <button class="bg-green-600 text-white font-semibold ml-[58%] py-1 px-3 text-lg rounded-md hover:bg-white hover:text-green-600 cursor-pointer">Continuar</button>
    </div>

    <div class="bg-blue-200 p-8 mx-auto w-[50%]">
      <p class="mt-2 mb-6 font-bold text-2xl">Datos del comprador</p>
      <label class="font-semibold text-gray-700 text-lg" for="nombre">Nombres y apellidos</label>
      <input class="py-1 w-[100%] pl-2 bg-slate-200 rounded-md mb-3" type="text" id="nombre">

      <label class="font-semibold text-gray-700 text-lg" for="correo">Correo electrónico</label>
      <input class="py-1 w-[100%] pl-2 bg-slate-200 rounded-md mb-3" type="text" id="correo">

      <label class="font-semibold text-gray-700 text-lg" for="dirección">dirección</label>
      <input class="py-1 w-[100%] pl-2 bg-slate-200 rounded-md mb-3" type="text" id="dirección">

      <label class="font-semibold text-gray-700 text-lg" for="mPago">Método de pago</label>
      <input class="py-1 w-[100%] pl-2 bg-slate-200 rounded-md mb-3" type="text" id="mPago">

      <button class="bg-green-600 text-white font-semibold ml-[66%] py-1 px-3 text-lg rounded-md hover:bg-white hover:text-green-600 cursor-pointer">Ordenar</button>

    </div>

  </div>
</template>


