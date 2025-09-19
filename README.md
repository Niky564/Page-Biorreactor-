<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biorreactores: Innovación en Biotecnología</title>
    <!-- Incluir el CDN de Tailwind CSS para el estilo -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .nav-link {
            transition: all 0.3s ease-in-out;
        }
        .nav-link:hover {
            transform: translateY(-2px);
            color: #B88BFF; /* color lila en hover */
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Encabezado y Menú de Navegación -->
    <header class="bg-white text-gray-800 shadow-lg sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex flex-col md:flex-row justify-between items-center">
            <h1 class="text-3xl font-bold text-[#B88BFF]">Biorreactores</h1>
            <nav class="mt-4 md:mt-0">
                <ul class="flex flex-wrap justify-center space-x-4 sm:space-x-6 text-xl">
                    <li><a href="#inicio" onclick="showSection('inicio')" class="text-gray-700 font-semibold nav-link hover:text-[#00BFFF]">Inicio</a></li>
                    <li><a href="#historia" onclick="showSection('historia')" class="text-gray-700 font-semibold nav-link hover:text-[#00BFFF]">Historia</a></li>
                    <li><a href="#aplicaciones" onclick="showSection('aplicaciones')" class="text-gray-700 font-semibold nav-link hover:text-[#00BFFF]">Aplicaciones</a></li>
                    <li><a href="#conclusion" onclick="showSection('conclusion')" class="text-gray-700 font-semibold nav-link hover:text-[#00BFFF]">Conclusión</a></li>
                    <li><a href="#recursos" onclick="showSection('recursos')" class="text-gray-700 font-semibold nav-link hover:text-[#00BFFF]">Recursos</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-4 py-10">
        <!-- Sección de Inicio (Portadilla Interactiva) -->
        <section id="inicio" class="section-content bg-white p-8 sm:p-12 rounded-2xl shadow-xl mb-12 text-gray-800 flex items-center justify-center min-h-[70vh]">
            <div class="flex flex-col md:flex-row items-center gap-8">
                <div class="w-full text-center">
                    <h2 class="text-5xl md:text-6xl font-extrabold text-[#00BFFF] mb-4 drop-shadow-md">Biorreactores</h2>
                    <p class="text-xl md:text-2xl text-gray-700 leading-relaxed mb-6">
                        La ingeniería que da vida.
                    </p>
                    <button onclick="showSection('historia')" class="bg-[#B88BFF] text-black font-bold py-3 px-8 rounded-full shadow-lg transition-transform hover:scale-105">
                        Explorar
                    </button>
                </div>
            </div>
        </section>
        
        <!-- Sección de Historia -->
        <section id="historia" class="section-content bg-gray-200 p-8 sm:p-12 rounded-2xl shadow-xl mb-12 hidden text-gray-800">
            <h2 class="text-3xl font-bold text-[#B88BFF] mb-6 text-center">Historia y Contexto de los Biorreactores</h2>
            <div class="grid md:grid-cols-2 gap-8 items-center">
                <div>
                    <p class="text-lg text-gray-700 leading-relaxed mb-4">
                        La idea de un biorreactor no es nueva; sus orígenes se remontan al siglo XIX con los primeros intentos de fermentación industrial. Sin embargo, el desarrollo de biorreactores modernos y a gran escala se aceleró durante el siglo XX, impulsado por la necesidad de producir antibióticos como la penicilina durante la Segunda Guerra Mundial.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Desde entonces, la tecnología ha evolucionado drásticamente. Los diseños iniciales, a menudo simples tanques, han dado paso a sistemas altamente sofisticados que controlan variables como la temperatura, el pH, el oxígeno disuelto y la agitación con gran precisión, permitiendo una producción más eficiente y controlada.
                    </p>
                </div>
                <div>
                    <img src="https://placehold.co/400x300/9CA3AF/1F2937?text=Historia" alt="Diagrama de la evolución de un biorreactor" class="rounded-xl shadow-lg w-full">
                </div>
            </div>
        </section>

        <!-- Sección de Aplicaciones -->
        <section id="aplicaciones" class="section-content bg-white p-8 sm:p-12 rounded-2xl shadow-xl mb-12 hidden text-gray-800">
            <h2 class="text-3xl font-bold text-[#00BFFF] mb-6 text-center">Aplicaciones en el Mundo Actual</h2>
            <p class="text-lg text-gray-700 leading-relaxed mb-8">
                Los biorreactores son herramientas indispensables en diversas industrias, impulsando la innovación y la producción de bienes esenciales.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-100 p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Industria Farmacéutica</h3>
                    <p class="text-gray-600">Producción de vacunas, anticuerpos monoclonales y terapias génicas.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Alimentos y Bebidas</h3>
                    <p class="text-gray-600">Fermentación de yogur, cerveza, vino y la producción de enzimas para procesado de alimentos.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Biocombustibles y Bioenergía</h3>
                    <p class="text-gray-600">Cultivo de algas y microorganismos para la producción de biocombustibles sostenibles.</p>
                </div>
            </div>
        </section>

        <!-- Sección de Conclusión -->
        <section id="conclusion" class="section-content bg-gray-200 p-8 sm:p-12 rounded-2xl shadow-xl mb-12 hidden text-gray-800">
            <h2 class="text-3xl font-bold text-[#B88BFF] mb-6 text-center">Una Reflexión Final</h2>
            <p class="text-lg text-gray-700 leading-relaxed">
                En esencia, los biorreactores no son solo máquinas; son los catalizadores de un futuro biotecnológico. Permiten la manipulación de procesos biológicos a escala industrial, lo que ha transformado la medicina, la agricultura y la energía. Su continua evolución nos acercará a soluciones más sostenibles y eficientes para los desafíos globales.
            </p>
        </section>

        <!-- Sección de Recursos -->
        <section id="recursos" class="section-content bg-white p-8 sm:p-12 rounded-2xl shadow-xl mb-12 hidden text-gray-800">
            <h2 class="text-3xl font-bold text-[#00BFFF] mb-6 text-center">Recursos y Referencias</h2>
            <ul class="list-disc list-inside space-y-2 text-lg text-gray-700">
                <li><a href="https://es.wikipedia.org/wiki/Biorreactor" class="text-blue-600 hover:underline">Wikipedia - Biorreactor</a></li>
                <li><a href="https://www.nature.com" class="text-blue-600 hover:underline">Revista Nature - Biotecnología</a></li>
                <li><a href="https://www.bioprocessintl.com/" class="text-blue-600 hover:underline">BioProcess International</a></li>
            </ul>
        </section>
        
    </main>

    <!-- Pie de página -->
    <footer class="bg-white text-gray-800 p-6 rounded-t-2xl shadow-inner">
        <div class="container mx-auto text-center text-sm">
            <p>Alumno: Mía Nikole Meoño Hernández</p>
            <p>Feria Científica</p>
            <p>Año: 2025</p>
        </div>
    </footer>

    <!-- Script para la funcionalidad de las secciones -->
    <script>
        function showSection(sectionId) {
            // Ocultar todas las secciones
            const sections = document.querySelectorAll('.section-content');
            sections.forEach(section => {
                section.style.display = 'none';
            });
            
            // Mostrar la sección seleccionada
            const selectedSection = document.getElementById(sectionId);
            if (selectedSection) {
                selectedSection.style.display = 'block';
            }
        }
    </script>

</body>
</html>
