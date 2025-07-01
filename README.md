<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Cumpleaños Papá</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js" defer></script>
</head>
<body class="bg-blue-100 text-blue-900 font-sans">
  <header class="bg-gradient-to-r from-blue-400 to-blue-600 text-white p-10 text-center shadow-xl">
    <h1 class="text-5xl font-extrabold animate-bounce">¡Feliz Cumpleaños Papá!</h1>
    <p class="text-xl mt-4">Queremos desearte lo más bonito para tu cumpleaños, que la pases demasiado bien y que sepas que te amamos muchisimo, muchas gracias por todo tu esfuerzo.</p>
  </header>  <!-- Sección del carrusel de fotos con reemplazo fácil -->  <section class="p-8">
    <h2 class="text-3xl font-bold mb-6 text-center">Galería de Recuerdos</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6"><!-- Imagen 1 -->
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad1.jpg" alt="Descripción 1" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Somos nosotros, estoy seguro de que todos agradecen lo mucho que te haz esforzado por ls familia.</p>
    </div>
  </div>

  <!-- Imagen 2 -->
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad2.jpg" alt="Descripción 2" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Una foto de hace poco, la pasamos muy bien, fue un bonito recuerdo.</p>
    </div>
  </div>

  <!-- Imagen 3 -->
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad3.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Otra vez nosotros, ahora con la gorda más gorda, cuando era una pequeñita, aun asi sigue siendo adorable.</p>
    </div>
  </div>

  <!-- Repite este bloque hasta imagen 10 -->
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad4.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Soy yo chiquito, junto al perro con más paciencia del mundo.</p>
  </div>
</div>
      <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad5.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Una foto de nosotros en la iglesia, cuando fuimos a santiago.</p>
  </div>
</div>
      <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad6.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Que bonito ir a la playa en familia...</p>
  </div>
        <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad7.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">La primera vez que sali del pais, siempre se pasa muy bien en familia.</p>
  </div>
          <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad8.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Una foto del dia del patrimonio en La Serena.</p>
  </div>
            <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad9.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Honestamente no recuerdo esa foto pero se ve bonita.</p>
  </div>
<div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad10.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Fotito en el cerro Santa Lucia.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad11.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">El tatita y la carmen.</p>
  </div>
    <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad12.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Una foto de los mejores padres del mundo entero, siempre nos dan y enseñan lo mejor.</p>
  </div>
      <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad13.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">S.</p>
  </div>
        
<div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dad14.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Una foto de nosotros en la iglesia, cuando fuimos a santiago.</p>
  </div>
  </section>  <!-- Sección de mascotas -->  <section class="p-8 bg-blue-200 rounded-xl shadow-lg mx-4 my-6">
    <h2 class="text-3xl font-bold mb-4 text-center">Tus Mascotas También Te Felicitan</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="bg-white p-6 rounded-lg shadow-md transform transition-transform hover:scale-105">
        <h3 class="text-2xl font-semibold mb-2">🐶 Pancha,Thomas, Bigti y Zara</h3>
        <p>Eso 4 son los mejores (y más flojos) guardianes de la casa, en especial el más virgen. todos ellos te desean un bonito cumpleaños, te aman demasiado</p>
        <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog1.jpg" alt="Panchita" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">
        <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog2.jpg" alt="Thomas" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">
        <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog3.jpg" alt="Bigtiboy" class="w-full h-auto" />
    </button>
          <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog4.jpg" alt="Panchita" class="w-full h-auto" />
    </button>
            <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog5.jpg" alt="Panchita" class="w-full h-auto" />
    </button>
              <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="dog6.jpg" alt="Panchita" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium"></p>
  </div>
</div>
      </p>
  </div>
</div>
      </p>
  </div>
</div>
      </div>
      <div class="bg-white p-6 rounded-lg shadow-md transform transition-transform hover:scale-105">
        <h3 class="text-2xl font-semibold mb-2">🐱 Zara</h3>
        <p>La loca Zarita, siempre seria...y aun asi, los ama a todos (quizas menos a mi).
  <div class="bg-white rounded-lg shadow-md overflow-hidden transform transition-transform hover:scale-105" x-data="{ open: false }">
    <button class="w-full" @click="open = !open">
      <img src="zara.jpg" alt="Descripción 3" class="w-full h-auto" />
    </button>
    <div class="p-4 bg-blue-50" x-show="open" x-transition>
      <p class="text-blue-900 font-medium">Zarita</p>
  </div>
</div>      </p>
      </div>
    </div>
  </section>  <!-- Sección de recuerdos desplegables -->  <section class="p-8 mx-4">
    <h2 class="text-3xl font-bold mb-6 text-center">Lo que nunca olvidare...</h2>
    <div class="space-y-4" x-data="{ open: null }">
      <div class="border border-blue-300 rounded-lg overflow-hidden shadow">
        <button class="w-full px-6 py-4 bg-blue-300 text-left font-semibold text-lg hover:bg-blue-400 transition-colors" @click="open === 1 ? open = null : open = 1">Los Bonitos Viajes Familiares</button>
        <div class="px-6 py-4 bg-blue-100" x-show="open === 1" x-transition>
          <p>El olor a tu camioneta, sandwichs hechos por la Mamita, poco espacio, esas cosas son las que hacen momentos inolvidables nuestros viajes, sea donde sea, siempre la pasamos muy bien.</p>
        </div>
      </div>
      <div class="border border-blue-300 rounded-lg overflow-hidden shadow">
        <button class="w-full px-6 py-4 bg-blue-300 text-left font-semibold text-lg hover:bg-blue-400 transition-colors" @click="open === 2 ? open = null : open = 2">Tus Enseñanzas</button>
        <div class="px-6 py-4 bg-blue-100" x-show="open === 2" x-transition>
          <p>Desde pequeños, nos haz enseñado a ser personas con valores, fuertes y empaticas, siempre dando el ejemplo y la cara por la familia.</p>
        </div>
      </div>
      <div class="border border-blue-300 rounded-lg overflow-hidden shadow">
        <button class="w-full px-6 py-4 bg-blue-300 text-left font-semibold text-lg hover:bg-blue-400 transition-colors" @click="open === 3 ? open = null : open = 3">Momentos de padre e hijo</button>
        <div class="px-6 py-4 bg-blue-100" x-show="open === 3" x-transition>
          <p>Nunca olvidare la vez que fuimos los dos a la nieve, en tu campo. te pusiste a cocinar con ls parrilla a gas, usaste la nieve como agua, y vimos una pelicula mientras comiamos. o cuando nos "enseñaste a pescar", fue una linda experiencia, a pesar de que hayan sido cañas de madera, pero lo que queda fue el lindo recuerdo...</p>
        </div>
      </div>
    </div>
  </section>  <!-- Pie de página -->  <footer class="bg-gradient-to-r from-blue-600 to-blue-800 text-white text-center p-6 mt-10 shadow-inner">
    <p class="text-lg"></p>
  </footer>
        <audio id="musica" loop>
    <source src="pink.mp3" type="audio/mpeg">
    Tu navegador no soporta audio HTML5.
  </audio>

  <script>
    let musicaIniciada = false;

    function toggleGaleria() {
      const galeria = document.getElementById("galeria");
      galeria.classList.toggle("show");

      // Iniciar música al primer clic
      if (!musicaIniciada) {
        document.getElementById("musica").play();
        musicaIniciada = true;
      }
    }
  </script>
</body>
</html
