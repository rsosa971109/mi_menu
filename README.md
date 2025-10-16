<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú de Antojitos</title>
    <!-- Carga de Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Usamos la fuente Inter, que es moderna y clara */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #FEF3C7; /* Fondo amarillo muy suave */
        }
    </style>
</head>
<body class="min-h-screen p-4 sm:p-8">

    <!-- Encabezado del Menú -->
    <header class="text-center mb-10 mt-4">
        <h1 class="text-4xl sm:text-5xl font-extrabold text-[#D97706] drop-shadow-lg">
            Nuestro Menú
        </h1>
        <p class="text-xl text-[#78350F] mt-2 italic">
            ¡Sabores Tradicionales y Antojitos Únicos!
        </p>
    </header>

    <!-- Contenedor de la Rejilla del Menú -->
    <main class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            
            <!-- TARJETA DE PRODUCTO: Trancas de Relleno -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
                <img src="img/1.png" alt="">
                
                <br>
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center" >PANUCHOS DE POLLO</h2>
                    
                
            </div>

            <!-- TARJETA DE PRODUCTO: Panuchos de Relleno -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
                <img src="img/3.png" alt="" class="w-[400px] rounded-lg shadow-md mx-auto">
                <br>
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center">PANUCHOS DE RELLENO</h2>
                   
                
            </div>

            <!-- TARJETA DE PRODUCTO: Tranca de Pollo -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
               <img src="img/4.png" alt="" class="w-[400px] rounded-lg shadow-md mx-auto">
                
               <br>
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center">TRANCA DE POLLO</h2>
                    
            </div>

            <!-- TARJETA DE PRODUCTO: Panuchos de Pollo -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
                <img src="img/2.png" alt="" class="w-[250px] rounded-lg shadow-md mx-auto">
                <br>
                
                
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center">HAMBURGUESITAS</h2>
                    
            </div>

            <!-- TARJETA DE PRODUCTO: Panuchos de Carne Molida -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
               <img src="img/6.png" alt="" class="w-[250px] rounded-lg shadow-md mx-auto">
               <br>
                
                
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center">PANUCHOS DE CARNE MOLIDA </h2>
                   
            </div>

            <!-- TARJETA DE PRODUCTO: Hamburguesitas -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
                <img src="img/5.png" alt="" class="w-[250px] rounded-lg shadow-md mx-auto">
                
              <br>
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2 text-center">TRANCAS DE RELLENO</h2>
                    
            </div>

            <!-- TARJETA DE PRODUCTO: Empanadas de Queso y Mixtas -->
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden hover:shadow-3xl transition-transform duration-300 transform hover:scale-[1.02] border-4 border-[#FBBF24]">
                <!-- Espacio para la Foto -->
                <div class="h-48 w-full bg-gray-200 flex items-center justify-center text-gray-500 font-bold text-lg" style="background-image: url('https://placehold.co/600x400/F59E0B/FFFFFF?text=FOTO+DE+EMPANADAS'); background-size: cover; background-position: center;">
                    <!-- Puedes reemplazar este div por tu etiqueta <img> -->
                </div>
                
                <div class="p-5">
                    <h2 class="text-2xl font-bold text-[#D97706] mb-2">Empanadas (Queso y Mixtas)</h2>
                    <p class="text-gray-700 mb-3">Elige entre queso derretido o la opción mixta con queso y algún guiso especial.</p>
                    
                </div>
            </div>

        </div>
    </main>
    
    <!-- Pie de página simple -->
    <footer class="text-center mt-10 p-4 text-gray-600">
        <p>&copy; 2025 Menú de Antojitos. ¡Gracias por tu preferencia!</p>
    </footer>

</body>
</html>
