# nyacho1.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía: El Mosaico de Talentos 8vo C</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@400;500;700&family=Afacad:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* Aplicamos las fuentes del tema de la presentación */
        body {
            font-family: 'Afacad', sans-serif;
            background-color: #f0f4f8; /* Fondo suave */
        }
        h1, h2, h3 {
            font-family: 'Comfortaa', cursive;
        }
        /* Estilos para los campos de texto */
        .form-input {
            width: 100%;
            border: 1px solid #cbd5e1;
            border-radius: 8px;
            padding: 10px 12px;
            font-family: 'Afacad', sans-serif;
            font-size: 16px;
            transition: all 0.2s ease;
        }
        .form-input:focus {
            outline: none;
            border-color: #3b82f6;
            box-shadow: 0 0 0 2px rgba(59, 130, 246, 0.3);
        }
        .form-textarea {
            min-height: 100px;
        }
        /* Estilos para la tabla editable */
        .editable-table td {
            border: 1px solid #e2e8f0;
            padding: 12px;
            background-color: #f8fafc;
            min-width: 150px;
        }
        .editable-table td:focus {
            outline: 2px solid #3b82f6;
            background-color: #fff;
            z-index: 10;
            position: relative;
        }
        /* Ocultar el botón al imprimir */
        @media print {
            .no-print {
                display: none !important;
            }
        }
    </style>
</head>
<body class="p-4 md:p-8">

    <div class="max-w-4xl mx-auto bg-white p-8 md:p-12 rounded-2xl shadow-xl">
        
        <!-- Encabezado -->
        <div class="text-center border-b-2 border-gray-100 pb-6 mb-8">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-800">El Mosaico de Talentos</h1>
            <p class="text-2xl text-blue-600 font-semibold mt-2">8vo C</p>
        </div>

        <!-- Grupo -->
        <div class="mb-8 p-6 bg-gray-50 rounded-xl">
            <h2 class="text-2xl font-semibold text-gray-700 mb-4">Integrantes del Grupo</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <input type="text" placeholder="Integrante 1..." class="form-input">
                <input type="text" placeholder="Integrante 2..." class="form-input">
                <input type="text" placeholder="Integrante 3..." class="form-input">
                <input type="text" placeholder="Integrante 4..." class="form-input">
                <input type="text" placeholder="Integrante 5..." class="form-input">
                <input type="text" placeholder="Integrante 6..." class="form-input">
            </div>
        </div>

        <!-- Objetivo -->
        <div class="mb-8 prose prose-lg max-w-none">
            <h3>Objetivo de la Actividad (La Misión):</h3>
            <p>¡Hola! A menudo nos centramos solo en las notas, pero un curso es mucho más que eso. Un curso es como un gran "mosaico": cada uno de ustedes es una pieza única, con talentos, habilidades y cualidades que hacen que el grupo funcione.</p>
            <p>El objetivo de esta guía es <strong>crear un mapa de esos talentos</strong>. No es una competencia, sino una actividad para descubrir las fortalezas que tenemos. ¡Vamos a descubrir los "súper-poderes" escondidos en el 8vo C!</p>
        </div>

        <!-- Parte 1 -->
        <div class="mb-8 p-6 bg-lime-50 rounded-xl border border-lime-200">
            <h2 class="text-2xl font-semibold text-lime-800 mb-4">Parte 1: Nuestras Piezas (Auto-retrato Grupal)</h2>
            <p class="mb-4 text-gray-700">Cada integrante del grupo debe llenar su propio espacio. Piensen en qué pieza única traen al curso (Ej: "Soy bueno/a para escuchar", "Se me ocurren ideas creativas", "Hago reír a la gente").</p>
            
            <label for="talento1" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 1: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento1" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>

            <label for="talento2" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 2: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento2" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>

            <label for="talento3" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 3: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento3" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>

            <label for="talento4" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 4: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento4" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>

            <label for="talento5" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 5: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento5" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>

            <label for="talento6" class="block text-lg font-medium text-gray-800 mb-2 mt-4">Integrante 6: Mi Talento Secreto (o no tan secreto) es:</label>
            <textarea id="talento6" class="form-input form-textarea" placeholder="Escribe aquí tu talento..."></textarea>
        </div>

        <!-- Parte 2 -->
        <div class="mb-8 p-6 bg-purple-50 rounded-xl border border-purple-200">
            <h2 class="text-2xl font-semibold text-purple-800 mb-4">Parte 2: El Mosaico de mi Grupo (Retrato Grupal)</h2>
            <p class="mb-4 text-gray-700">Conversen y encuentren una cualidad positiva para CADA MIEMBRO de este grupo. ¡Hagan clic en las celdas para escribir!</p>
            
            <div class="overflow-x-auto">
                <table class="w-full text-left editable-table">
                    <thead class="bg-purple-100">
                        <tr>
                            <th class="p-3 text-lg font-semibold text-purple-900">Nombre de mi compañero/a</th>
                            <th class="p-3 text-lg font-semibold text-purple-900">La cualidad o "súper-poder" que vemos</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                        <tr>
                            <td contenteditable="true" data-placeholder="Nombre..."></td>
                            <td contenteditable="true" data-placeholder="Escribir cualidad..."></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- Parte 3 -->
        <div class="mb-8 p-6 bg-orange-50 rounded-xl border border-orange-200">
            <h2 class="text-2xl font-semibold text-orange-800 mb-4">Parte 3: El Gran Mosaico (¡El Curso Completo!)</h2>
            <p class="mb-4 text-gray-700">¡La parte más importante! Hagan una "Lluvia de Ideas de Talentos" sobre compañeros que <strong>NO</strong> están en su grupo. Elijan al menos 5.</p>
            
            <label for="gran-mosaico" class="block text-lg font-medium text-gray-800 mb-2">El Desafío del Detective Positivo:</label>
            <textarea id="gran-mosaico" class="form-input form-textarea" style="min-height: 250px;" placeholder="Ej: 'Javier: Es súper bueno para explicar matemáticas.' 'Antonia: Siempre incluye a los demás.' 'Martín: Dibuja increíble.'..."></textarea>
        </div>

        <!-- Botón de Imprimir -->
        <div class="text-center mt-12 p-6 bg-gray-50 rounded-lg border border-gray-200 no-print">
            <h3 class="text-2xl font-semibold text-gray-800 mb-4">Pasos para Entregar el Trabajo</h3>
            <p class="text-gray-600 mb-6 max-w-2xl mx-auto">Debes seguir 2 pasos. Primero, guarda tu trabajo como PDF. Luego, haz clic en el segundo botón para abrir tu email y adjuntar el PDF que acabas de guardar.</p>
            
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <!-- Paso 1: Guardar PDF -->
                <button onclick="window.print()" class="px-8 py-3 bg-blue-600 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-blue-700 transition-all focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2">
                    Paso 1: Guardar como PDF
                </button>

                <!-- Paso 2: Enviar por Email -->
                <!-- IMPORTANTE: Reemplaza "PON_AQUI_TU_CORREO@colegio.cl" con tu email real -->
                <a href="mailto:practica.dennischaparro@santasabina.cl?subject=Entrega:%20Mosaico%20de%20Talentos%208vo%20C"
                   target="_blank"
                   class="inline-block px-8 py-3 bg-green-600 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-green-700 transition-all focus:outline-none focus:ring-2 focus:ring-green-500 focus:ring-offset-2">
                    Paso 2: Enviar por Email
                </a>
            </div>
            <p class="text-sm text-gray-500 mt-4">Nota: El botón 'Enviar por Email' abrirá tu programa de correo. ¡No olvides adjuntar el PDF!</p>
        </div>

    </div>

</body>
</html>
