<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UINGO - Logística Inteligente para PyMEs</title>
    <!-- Tailwind CSS para diseño moderno -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .modal { transition: opacity 0.25s ease; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

    <!-- Navegación -->
    <nav class="sticky top-0 z-40 bg-white/90 backdrop-blur-md border-b border-slate-100 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <span class="bg-blue-600 text-white font-bold p-2 rounded-xl text-lg">✈</span>
                <span class="text-xl font-extrabold tracking-tight text-slate-900">UINGO</span>
            </div>
            <div class="hidden md:flex space-x-6 text-sm font-medium text-slate-600">
                <a href="#inicio" class="hover:text-blue-600">Inicio</a>
                <a href="#propuesta" class="hover:text-blue-600">Propuesta</a>
                <a href="#servicios" class="hover:text-blue-600">Servicios</a>
                <a href="#versatilidad" class="hover:text-blue-600">Versatilidad</a>
                <a href="#resenas" class="hover:text-blue-600">Reseñas</a>
                <a href="#faq" class="hover:text-blue-600">FAQ</a>
            </div>
            <div>
                <a href="#cotizador" class="bg-blue-600 hover:bg-blue-700 text-white font-medium px-5 py-2.5 rounded-full shadow-md transition-all text-sm flex items-center gap-2">
                    <span>📦 Cotizar envío</span>
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="inicio" class="relative overflow-hidden pt-12 pb-20 lg:pt-20 lg:pb-28 bg-gradient-to-b from-blue-50/50 to-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-7 space-y-6">
                <span class="inline-flex items-center gap-1.5 py-1 px-3 rounded-full text-xs font-semibold bg-blue-100 text-blue-700">
                    <span class="w-2 h-2 rounded-full bg-blue-600"></span> LOGÍSTICA INTELIGENTE PARA PyMEs
                </span>
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-slate-900 tracking-tight leading-tight">
                    Quédate tranquilo, <br><span class="text-blue-600">moviendo con UINGO</span>
                </h1>
                <p class="text-lg text-slate-600 max-w-xl">
                    Conecta con repartidores verificados. Tus clientes rastrean en tiempo real. Sin integraciones complejas. Solo crea pedidos y nosotros hacemos el resto.
                </p>
                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#cotizador" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3.5 rounded-xl shadow-lg shadow-blue-500/20 transition-all flex items-center gap-2">
                        📦 Cotizar envío
                    </a>
                    <a href="mailto:contacto@uingo.mx" class="bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 font-semibold px-6 py-3.5 rounded-xl transition-all flex items-center gap-2">
                        ✉ Contáctanos
                    </a>
                    <a href="https://wa.me/" target="_blank" class="bg-emerald-50 hover:bg-emerald-100 text-emerald-700 font-semibold px-6 py-3.5 rounded-xl transition-all flex items-center gap-2">
                        💚 WhatsApp →
                    </a>
                </div>
                <!-- Métricas Rápidas -->
                <div class="grid grid-cols-3 gap-4 pt-8 border-t border-slate-200/60">
                    <div>
                        <p class="text-2xl font-bold text-slate-900">94%</p>
                        <p class="text-xs text-slate-500">Entregas exitosas</p>
                    </div>
                    <div>
                        <p class="text-2xl font-bold text-slate-900">Lunes a Sábado</p>
                        <p class="text-xs text-slate-500">Disponibilidad</p>
                    </div>
                    <div>
                        <p class="text-2xl font-bold text-slate-900">100+</p>
                        <p class="text-xs text-slate-500">Traslados exitosos</p>
                    </div>
                </div>
            </div>
            <!-- Card Interactiva Visual -->
            <div class="lg:col-span-5">
                <div class="bg-white p-6 rounded-3xl shadow-2xl border border-slate-100 relative">
                    <div class="absolute -top-3 right-6 bg-emerald-100 text-emerald-800 text-xs font-bold px-3 py-1 rounded-full flex items-center gap-1">
                        <span class="w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse"></span> ENTREGADO HACE 5 MIN
                    </div>
                    <div class="flex items-center justify-between mb-4">
                        <span class="bg-blue-50 text-blue-700 text-xs font-semibold px-2.5 py-1 rounded-md">🔵 EN TRÁNSITO</span>
                        <span class="text-xs text-slate-400 font-medium">Pedido #4521</span>
                    </div>
                    <div class="text-right mb-2">
                        <span class="text-xs text-slate-400">ENTREGA ESTIMADA</span>
                        <p class="text-lg font-bold text-slate-800">15 min</p>
                    </div>
                    <!-- Simulación Mapa -->
                    <div class="bg-slate-100 h-28 rounded-2xl mb-4 relative overflow-hidden flex items-center justify-center border border-slate-200">
                        <div class="absolute inset-0 opacity-20 bg-[radial-gradient(#3b82f6_1px,transparent_1px)] [background-size:12px_12px]"></div>
                        <svg class="w-full h-full px-6" viewBox="0 0 200 60">
                            <path d="M10 50 Q 100 10 190 30" fill="none" stroke="#2563eb" stroke-width="3" stroke-dasharray="6,6"/>
                            <circle cx="10" cy="50" r="5" fill="#2563eb"/>
                            <circle cx="190" cy="30" r="6" fill="#10b981"/>
                        </svg>
                        <span class="absolute bottom-2 left-3 bg-white/90 px-2 py-0.5 rounded text-[10px] font-semibold text-slate-600 shadow-sm">📍 3.2 km restantes</span>
                    </div>
                    <div class="grid grid-cols-2 gap-3 mb-4">
                        <div class="bg-slate-50 p-2.5 rounded-xl border border-slate-100">
                            <span class="text-[10px] text-slate-400 block font-medium">CATEGORÍA</span>
                            <span class="text-xs font-bold text-slate-700">Electrónica</span>
                        </div>
                        <div class="bg-slate-50 p-2.5 rounded-xl border border-slate-100">
                            <span class="text-[10px] text-slate-400 block font-medium">PESO</span>
                            <span class="text-xs font-bold text-slate-700">2.5 kg</span>
                        </div>
                    </div>
                    <div class="flex items-center justify-between bg-blue-50/50 p-3 rounded-xl border border-blue-100/50">
                        <div class="flex items-center gap-3">
                            <div class="w-9 h-9 bg-blue-600 text-white rounded-full flex items-center justify-center font-bold text-xs">CM</div>
                            <div>
                                <span class="text-[10px] text-slate-400 block font-medium">REPARTIDOR</span>
                                <span class="text-xs font-bold text-slate-800 flex items-center gap-1">Carlos M. <span class="text-emerald-500">✓</span></span>
                            </div>
                        </div>
                        <div class="text-right">
                            <span class="text-xs font-bold text-amber-500">★ 4.9</span>
                            <span class="text-[10px] text-slate-400 block">(234)</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Propuesta de Valor -->
    <section id="propuesta" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-xs font-bold text-blue-600 tracking-widest uppercase mb-3">Propuesta de Valor</h2>
            <h3 class="text-3xl font-extrabold text-slate-900 mb-4">Tus clientes monitorean su pedido en tiempo real</h3>
            <p class="text-slate-600 max-w-2xl mx-auto mb-12">Sin integraciones complejas, sin configuraciones técnicas. Solo crea pedidos y nosotros hacemos el resto.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100 text-left hover:shadow-md transition-all">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center font-bold text-xl mb-4">⏱️</div>
                    <h4 class="text-lg font-bold text-slate-900 mb-2">Coordina tu pedido en minutos</h4>
                    <p class="text-sm text-slate-600 mb-4">Tus clientes reciben un link de seguimiento apenas creas el pedido. Cero trabajo extra.</p>
                    <span class="text-xs font-semibold text-blue-600">Listo en segundos</span>
                </div>
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100 text-left hover:shadow-md transition-all">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center font-bold text-xl mb-4">📍</div>
                    <h4 class="text-lg font-bold text-slate-900 mb-2">Rastreo en vivo</h4>
                    <p class="text-sm text-slate-600 mb-4">Ubicación exacta del repartidor, ETA actualizada y datos verificados del conductor.</p>
                    <span class="text-xs font-semibold text-blue-600">Reducir llamadas de soporte</span>
                </div>
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100 text-left hover:shadow-md transition-all">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center font-bold text-xl mb-4">🛡️</div>
                    <h4 class="text-lg font-bold text-slate-900 mb-2">Sin configuración</h4>
                    <p class="text-sm text-slate-600 mb-4">Tus clientes obtienen la mejor experiencia. Tú solo enfócate en tu negocio.</p>
                    <span class="text-xs font-semibold text-blue-600">Clientes tranquilos</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Cotizador de Servicios con Lógica Exacta -->
    <section id="cotizador" class="py-20 bg-slate-100">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-10">
                <span class="text-xs font-bold text-blue-600 tracking-widest uppercase">Plataforma Interactiva</span>
                <h2 class="text-3xl font-extrabold text-slate-900 mt-1">Cotizador de Envíos UINGO</h2>
                <p class="text-slate-600 text-sm mt-2">Calcula al instante tu tarifa según vehículo, distancia y necesidades especiales.</p>
            </div>

            <div class="bg-white p-8 rounded-3xl shadow-xl border border-slate-200">
                <form id="cotizadorForm" class="space-y-6">
                    <!-- Registro / Perfil -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Nombre o Razón Social</label>
                            <input type="text" id="nombreCliente" required placeholder="Ej. Mi Negocio / Juan Pérez" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Tipo de Perfil</label>
                            <select id="tipoPerfil" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                                <option value="Persona">Persona</option>
                                <option value="Empresa">Empresa</option>
                            </select>
                        </div>
                    </div>

                    <!-- Ubicaciones -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Ubicación de Recogida (Origen)</label>
                            <input type="text" id="origen" required placeholder="Colonia, Calle o Referencia" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Ubicación de Entrega (Destino)</label>
                            <input type="text" id="destino" required placeholder="Colonia, Calle o Referencia" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                        </div>
                    </div>

                    <!-- Selección de Vehículo y Distancia -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Selecciona la Unidad</label>
                            <select id="tipoUnidad" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                                <option value="moto">Moto</option>
                                <option value="carro">Carro</option>
                                <option value="camioneta">Camioneta 1.2 Tons</option>
                                <option value="camion">Camión 3 Tons</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Distancia estimada (Kilómetros)</label>
                            <input type="number" id="distanciaKm" min="1" value="5" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                        </div>
                    </div>

                    <!-- Cargadores Extras -->
                    <div id="cargadoresContainer" class="hidden bg-slate-50 p-4 rounded-xl border border-slate-200">
                        <label class="block text-xs font-bold text-slate-700 uppercase mb-1">¿Necesitas cargadores extras? ($300 c/u)</label>
                        <input type="number" id="cargadores" min="0" value="0" class="w-full px-4 py-2 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-blue-500 outline-none">
                    </div>

                    <!-- Botón Calcular -->
                    <button type="button" onclick="calcularCotizacion()" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3.5 rounded-xl shadow-lg transition-all text-sm">
                        Calcular Cotización Exacta
                    </button>
                </form>

                <!-- Resultado de Cotización -->
                <div id="resultadoCotizacion" class="hidden mt-8 p-6 bg-blue-50 border border-blue-200 rounded-2xl text-center">
                    <h3 class="text-xs font-bold text-blue-600 uppercase tracking-wider mb-1">Resumen del Servicio</h3>
                    <p id="detalleTexto" class="text-sm text-slate-700 mb-3"></p>
                    <p class="text-3xl font-extrabold text-blue-900 mb-4" id="montoTotal">$0.00 MXN</p>
                    <div class="flex flex-wrap justify-center gap-3">
                        <button onclick="enviarWhatsApp()" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold px-5 py-2.5 rounded-xl transition-all flex items-center gap-2">
                            💚 Solicitar por WhatsApp
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Servicios -->
    <section id="servicios" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-xs font-bold text-blue-600 tracking-widest uppercase mb-3">Servicios</h2>
            <h3 class="text-3xl font-extrabold text-slate-900 mb-4">Soluciones completas para tu logística</h3>
            <p class="text-slate-600 max-w-2xl mx-auto mb-12">Desde envíos personales hasta distribución empresarial, tenemos la solución perfecta para ti.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-left">
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100">
                    <h4 class="text-lg font-bold text-slate-900 mb-2">🚀 Envíos Express</h4>
                    <p class="text-sm text-slate-600">Entregas el mismo día para productos urgentes de cualquier tamaño.</p>
                </div>
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100">
                    <h4 class="text-lg font-bold text-slate-900 mb-2">📊 Logística PyME</h4>
                    <p class="text-sm text-slate-600">Soluciones empresariales con facturación y seguimiento completo.</p>
                </div>
                <div class="p-8 rounded-2xl bg-slate-50 border border-slate-100">
                    <h4 class="text-lg font-bold text-slate-900 mb-2">🚚 Múltiples Vehículos</h4>
                    <p class="text-sm text-slate-600">Motos, autos y pick-ups para todo tipo de mercancía.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Versatilidad de Cargas -->
    <section id="versatilidad" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-xs font-bold text-blue-600 tracking-widest uppercase mb-3">Versatilidad</h2>
            <h3 class="text-3xl font-extrabold text-slate-900 mb-4">Cualquier producto, de una sola forma</h3>
            <p class="text-slate-600 max-w-2xl mx-auto mb-12">Sin restricciones de tipo de mercancía. Desde materiales de construcción hasta plantas y muebles.</p>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center">
                <div class="p-4 bg-white rounded-xl border border-slate-200 font-semibold text-sm">🪴 Macetas y Plantas</div>
                <div class="p-4 bg-white rounded-xl border border-slate-200 font-semibold text-sm">🧰 Herramientas</div>
                <div class="p-4 bg-white rounded-xl border border-slate-200 font-semibold text-sm">🛋️ Muebles</div>
                <div class="p-4 bg-white rounded-xl border border-slate-200 font-semibold text-sm">🧱 Materiales de Construcción</div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="py-20 bg-white">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-xs font-bold text-blue-600 tracking-widest uppercase mb-3">FAQ</h2>
                <h3 class="text-3xl font-extrabold text-slate-900">Preguntas frecuentes</h3>
            </div>
            <div class="space-y-4">
                <details class="p-4 bg-slate-50 rounded-xl border border-slate-200 cursor-pointer">
                    <summary class="font-bold text-sm text-slate-800">¿Qué tipo de pedidos puedo solicitar con UINGO?</summary>
                    <p class="text-xs text-slate-600 mt-2">Cualquier paquete transportable, desde pequeños documentos en moto hasta carga pesada en pick-ups y camiones.</p>
                </details>
                <details class="p-4 bg-slate-50 rounded-xl border border-slate-200 cursor-pointer">
                    <summary class="font-bold text-sm text-slate-800">¿UINGO trabaja con negocios y PyMEs?</summary>
                    <p class="text-xs text-slate-600 mt-2">Sí, contamos con planes especiales, facturación electrónica y seguimiento en vivo integrado para comercios locales.</p>
                </details>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-6">
            <div>
                <span class="text-xl font-extrabold tracking-tight text-white">UINGO</span>
                <p class="text-xs text-slate-400 mt-1">Transformando la logística local con formalidad y velocidad.</p>
            </div>
            <div class="flex space-x-6 text-xs text-slate-400">
                <button onclick="abrirModal('terminosModal')" class="hover:underline">Términos y Condiciones</button>
                <button onclick="abrirModal('privacidadModal')" class="hover:underline">Aviso de Privacidad</button>
            </div>
        </div>
    </footer>

    <!-- Modal Términos -->
    <div id="terminosModal" class="modal opacity-0 pointer-events-none fixed inset-0 z-50 flex items-center justify-center bg-black/50 p-4">
        <div class="bg-white max-w-lg w-full p-6 rounded-2xl shadow-xl max-h-[80vh] overflow-y-auto">
            <h3 class="font-bold text-lg mb-3">Términos y Condiciones de Servicio</h3>
            <p class="text-xs text-slate-600 mb-4">UINGO Logística, Colima, México. Vigencia desde 2026. Plataforma tecnológica que conecta usuarios con socios conductores independientes bajo estrictos estándares de seguridad y cumplimiento normativo.</p>
            <button onclick="cerrarModal('terminosModal')" class="bg-blue-600 text-white text-xs px-4 py-2 rounded-xl">Entendido</button>
        </div>
    </div>

    <!-- Modal Privacidad -->
    <div id="privacidadModal" class="modal opacity-0 pointer-events-none fixed inset-0 z-50 flex items-center justify-center bg-black/50 p-4">
        <div class="bg-white max-w-lg w-full p-6 rounded-2xl shadow-xl max-h-[80vh] overflow-y-auto">
            <h3 class="font-bold text-lg mb-3">Aviso de Privacidad</h3>
            <p class="text-xs text-slate-600 mb-4">Responsable: UNGIO opera en Colima, México. Protegemos tus datos personales conforme a la LFPDPPP para fines de gestión logística, geolocalización y facturación.</p>
            <button onclick="cerrarModal('privacidadModal')" class="bg-blue-600 text-white text-xs px-4 py-2 rounded-xl">Entendido</button>
        </div>
    </div>

    <!-- Script de Cotización y Lógica -->
    <script>
        const tipoUnidadSelect = document.getElementById('tipoUnidad');
        const cargadoresContainer = document.getElementById('cargadoresContainer');

        tipoUnidadSelect.addEventListener('change', (e) => {
            if(e.target.value === 'camioneta' || e.target.value === 'camion') {
                cargadoresContainer.classList.remove('hidden');
            } else {
                cargadoresContainer.classList.add('hidden');
                document.getElementById('cargadores').value = 0;
            }
        });

        function calcularCotizacion() {
            const unidad = tipoUnidadSelect.value;
            const km = parseFloat(document.getElementById('distanciaKm').value) || 0;
            const cargadores = parseInt(document.getElementById('cargadores').value) || 0;
            let total = 0;
            let descripcionUnidad = "";

            if (unidad === 'moto') {
                descripcionUnidad = "Moto";
                total = 65; // Base hasta 7 km
                if (km > 7) {
                    let kmExtras = km - 7;
                    let bloquesDosKm = Math.ceil(kmExtras / 2);
                    total += bloquesDosKm * 20;
                }
            } else if (unidad === 'carro') {
                descripcionUnidad = "Carro";
                total = 120; // Base hasta 7 km
                if (km > 7) {
                    let kmExtras = km - 7;
                    let bloquesDosKm = Math.ceil(kmExtras / 2);
                    total += bloquesDosKm * 20;
                }
            } else if (unidad === 'camioneta') {
                descripcionUnidad = "Camioneta 1.2 Tons";
                // $400 base + por cada 2km extras $100
                total = 400;
                if (km > 2) {
                    let kmExtras = km - 2;
                    let bloquesDosKm = Math.ceil(kmExtras / 2);
                    total += bloquesDosKm * 100;
                }
                total += cargadores * 300;
            } else if (unidad === 'camion') {
                descripcionUnidad = "Camión 3 Tons";
                // $1000 base + por cada 2km extras $200
                total = 1000;
                if (km > 2) {
                    let kmExtras = km - 2;
                    let bloquesDosKm = Math.ceil(kmExtras / 2);
                    total += bloquesDosKm * 200;
                }
                total += cargadores * 300;
            }

            document.getElementById('detalleTexto').innerText = `Unidad: ${descripcionUnidad} | Distancia: ${km} km | Cargadores: ${cargadores}`;
            document.getElementById('montoTotal').innerText = `$${total.toFixed(2)} MXN`;
            document.getElementById('resultadoCotizacion').classList.remove('hidden');
        }

        function enviarWhatsApp() {
            const cliente = document.getElementById('nombreCliente').value || 'Cliente UINGO';
            const origen = document.getElementById('origen').value || 'Origen';
            const destino = document.getElementById('destino').value || 'Destino';
            const detalle = document.getElementById('detalleTexto').innerText;
            const monto = document.getElementById('montoTotal').innerText;

            const mensaje = `Hola, soy ${cliente}. Deseo confirmar un servicio.%0A- Origen: ${origen}%0A- Destino: ${destino}%0A- ${detalle}%0A- Total estimado: ${monto}`;
            window.open(`https://wa.me/?text=${mensaje}`, '_blank');
        }

        function abrirModal(id) {
            const m = document.getElementById(id);
            m.classList.remove('opacity-0', 'pointer-events-none');
        }
        function cerrarModal(id) {
            const m = document.getElementById(id);
            m.classList.add('opacity-0', 'pointer-events-none');
        }
    </script>
</body>
</html>
