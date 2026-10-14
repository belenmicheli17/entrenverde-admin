<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="robots" content="noindex, nofollow">
<meta name="theme-color" content="#1F5C2E">
<meta name="apple-mobile-web-app-capable" content="yes">
<title>Panel</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --verde: #1F5C2E;
    --verde-medio: #2E7D42;
    --verde-claro: #E8F4EC;
    --mostaza: #C9A84C;
    --mostaza-hover: #B8923E;
    --crema: #F5F0E8;
    --crema-card: #FDFAF5;
    --texto: #1A2E1D;
    --texto-suave: #5A6E5C;
    --borde: #DDD8CF;
    --borde-suave: #EDE8DE;
    --rojo: #C0392B;
    --rojo-claro: #FBEAE8;
    --serif: 'Playfair Display', Georgia, serif;
    --sans: 'Inter', system-ui, sans-serif;
  }
  * { box-sizing: border-box; }
  html, body { margin: 0; }
  body { font-family: var(--sans); color: var(--texto); background: var(--crema); -webkit-font-smoothing: antialiased; }
  button, input, select { font: inherit; color: inherit; }
  button { cursor: pointer; }
  [hidden] { display: none !important; }
  .sr { position: absolute; width: 1px; height: 1px; overflow: hidden; clip: rect(0 0 0 0); white-space: nowrap; }
  :focus-visible { outline: 2px solid var(--mostaza); outline-offset: 2px; }

  /* Interruptor */
  .sw { appearance: none; -webkit-appearance: none; width: 40px; height: 24px; border-radius: 12px; background: #C9C4BA; position: relative; margin: 0; flex: none; cursor: pointer; transition: background .15s; }
  .sw::after { content: ""; position: absolute; top: 3px; left: 3px; width: 18px; height: 18px; border-radius: 50%; background: #fff; transition: left .15s; }
  .sw:checked { background: var(--verde-medio); }
  .sw:checked::after { left: 19px; }
  .sw:disabled { opacity: .5; cursor: wait; }

  /* Botones y campos */
  .btn { height: 48px; padding: 0 20px; border-radius: 10px; font-size: 15px; font-weight: 600; border: 1px solid transparent; }
  .btn-primario { background: var(--verde); color: #fff; }
  .btn-primario:hover { background: var(--verde-medio); }
  .btn-borde { background: var(--crema-card); border-color: var(--borde); color: var(--verde); }
  .btn-borde:hover { border-color: var(--verde); }
  .btn:disabled { opacity: .55; cursor: not-allowed; }
  .input { height: 50px; border: 1px solid var(--borde); background: var(--crema-card); border-radius: 10px; padding: 0 14px; font-size: 16px; min-width: 0; }
  .campo { display: flex; flex-direction: column; gap: 6px; font-size: 13px; font-weight: 600; color: var(--texto-suave); }
  .msg-error { background: var(--rojo-claro); color: var(--rojo); border-radius: 10px; padding: 12px 14px; font-size: 14px; line-height: 1.4; }

  /* ─── Ingreso ─── */
  .login { min-height: 100vh; display: flex; flex-wrap: wrap; }
  .login-marca { flex: 1 1 420px; background: var(--verde); color: var(--crema); padding: 56px; display: flex; flex-direction: column; justify-content: space-between; gap: 40px; min-height: 320px; }
  .kicker { font-size: 14px; letter-spacing: .08em; text-transform: uppercase; opacity: .8; }
  .login-marca h1 { font-family: var(--serif); font-size: clamp(44px, 6vw, 64px); font-weight: 600; line-height: 1.05; margin: 0 0 22px; max-width: 8em; }
  .raya { width: 64px; height: 4px; background: var(--mostaza); margin-bottom: 22px; }
  .login-marca p { margin: 0; font-size: 18px; line-height: 1.55; max-width: 380px; opacity: .92; }
  .login-pie { font-size: 13px; opacity: .7; }
  .login-lado { flex: 1 1 420px; display: flex; align-items: center; justify-content: center; padding: 40px; }
  .login-form { width: 100%; max-width: 380px; display: flex; flex-direction: column; gap: 20px; }
  .titulo { font-family: var(--serif); font-size: 34px; font-weight: 600; margin: 0; }
  .bajada { margin: 8px 0 0; font-size: 15px; color: var(--texto-suave); }
  .clave-fila { display: flex; gap: 8px; }
  .clave-fila .input { flex: 1; }
  .recordar { display: flex; align-items: center; gap: 12px; min-height: 44px; font-size: 14px; font-weight: 500; cursor: pointer; }
  .nota { margin: 0; font-size: 12px; color: var(--texto-suave); line-height: 1.5; }

  /* ─── Panel ─── */
  .app { display: flex; min-height: 100vh; }
  .lateral { flex: 0 0 236px; background: var(--verde); color: var(--crema); padding: 28px 18px; display: flex; flex-direction: column; gap: 6px; position: sticky; top: 0; height: 100vh; }
  .lateral .marca { font-family: var(--serif); font-size: 24px; font-weight: 600; padding: 0 10px; line-height: 1.2; }
  .lateral .sub { font-size: 12px; opacity: .75; padding: 4px 10px 22px; }
  .nav-item { display: flex; align-items: center; gap: 8px; width: 100%; padding: 12px 10px; border-radius: 10px; font-size: 15px; text-align: left; background: none; border: 0; color: inherit; }
  .nav-item.activo { background: rgba(255,255,255,.14); font-weight: 600; }
  .nav-item[aria-disabled="true"] { cursor: default; opacity: .8; }
  .tag { font-size: 11px; background: var(--mostaza); color: var(--texto); border-radius: 6px; padding: 2px 7px; font-weight: 600; }
  .lateral .espacio { flex: 1; }
  .lateral .salir { font-size: 14px; opacity: .85; }

  .topbar-m { display: none; }
  .principal { flex: 1; min-width: 0; padding: 32px 40px 48px; display: flex; flex-direction: column; gap: 22px; }
  .cabecera { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 16px; }
  .cabecera h1 { font-family: var(--serif); font-size: 34px; font-weight: 600; margin: 0; }
  .resumen { font-size: 14px; color: var(--texto-suave); margin-top: 4px; }
  .cab-der { display: flex; align-items: center; gap: 14px; }
  .estado { font-size: 13px; border-radius: 20px; padding: 7px 14px; font-weight: 500; background: var(--verde-claro); color: var(--verde-medio); white-space: nowrap; }
  .estado.guardando { background: #EFEBE3; color: var(--texto-suave); }
  .estado.error { background: var(--rojo-claro); color: var(--rojo); }
  .btn-agregar { background: var(--mostaza); color: var(--texto); }

  .filtros { display: flex; flex-wrap: wrap; align-items: center; gap: 12px; }
  .buscar { flex: 1 1 260px; max-width: 360px; }
  .buscar .input, .filtro-cat select { height: 46px; font-size: 15px; width: 100%; }
  .filtro-cat select { padding: 0 12px; }
  .chips-filtro { display: flex; flex-wrap: wrap; gap: 8px; }
  .chip-f { height: 46px; padding: 0 18px; border-radius: 23px; border: 1px solid var(--borde); background: var(--crema-card); font-size: 14px; font-weight: 500; }
  .chip-f[aria-pressed="true"] { background: var(--verde); border-color: var(--verde); color: #fff; font-weight: 600; }
  .ayuda { font-size: 13px; color: var(--texto-suave); margin: 0; line-height: 1.5; }

  .tabla { background: var(--crema-card); border: 1px solid var(--borde); border-radius: 14px; overflow-x: auto; }
  .tabla-inner { min-width: 860px; }
  .fila { display: grid; grid-template-columns: 24px 56px minmax(150px, 1fr) minmax(200px, 1.6fr) 72px 72px 72px 76px; gap: 12px; align-items: center; padding: 14px 20px; border-bottom: 1px solid var(--borde-suave); background: var(--crema-card); }
  #lista .fila:last-child { border-bottom: 0; }
  .fila.encabezado { border-bottom: 1px solid var(--borde); font-size: 12px; font-weight: 600; color: var(--texto-suave); text-transform: uppercase; letter-spacing: .04em; line-height: 1.25; }
  .fila.encabezado .c { text-align: center; }
  .fila.oculto .info, .fila.oculto .foto { opacity: .55; }
  .grip { width: 24px; height: 44px; padding: 0; border: 0; background: transparent; cursor: grab; display: flex; align-items: center; justify-content: center; touch-action: none; }
  .grip:disabled { cursor: default; opacity: .3; }
  .sortable-ghost { opacity: .35; }
  .sortable-chosen { box-shadow: 0 8px 24px rgba(0,0,0,.12); }
  .foto { position: relative; width: 48px; height: 48px; border-radius: 10px; background: var(--verde-claro); color: var(--verde); font-family: var(--serif); font-size: 22px; font-weight: 600; display: flex; align-items: center; justify-content: center; overflow: hidden; }
  .foto img { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: contain; background: #fff; }
  .foto img.rota { display: none; }
  .nombre { font-weight: 600; font-size: 15px; line-height: 1.3; }
  .meta { font-size: 13px; color: var(--texto-suave); margin-top: 3px; }
  .badge { display: inline-block; font-size: 11px; font-weight: 600; border-radius: 6px; padding: 2px 6px; margin-left: 6px; vertical-align: 1px; background: #EFEBE3; color: var(--texto-suave); }
  .vars { display: flex; flex-wrap: wrap; gap: 6px; }
  .chip { height: 34px; padding: 0 12px; border-radius: 8px; font-size: 13px; font-weight: 600; border: 1px solid var(--borde); background: #fff; white-space: nowrap; }
  .chip:hover { border-color: var(--verde); }
  .chip.oferta { background: var(--mostaza); border-color: var(--mostaza-hover); }
  .chip.inactiva { opacity: .55; border-style: dashed; text-decoration: line-through; }
  .toggles { display: contents; }
  .tg { display: flex; justify-content: center; align-items: center; gap: 8px; min-height: 44px; cursor: pointer; }
  .tg-m { display: none; font-size: 12px; font-weight: 500; }
  .btn-editar { display: block; width: 100%; text-align: center; border: 1px solid var(--verde); color: var(--verde); background: transparent; border-radius: 8px; padding: 9px 0; font-size: 14px; font-weight: 600; }
  .btn-editar:disabled { border-color: var(--borde); color: #8E9A8F; cursor: not-allowed; }
  .vacio { padding: 40px 20px; text-align: center; color: var(--texto-suave); line-height: 1.6; }
  .tabbar { display: none; }

  /* Ventana de variante */
  dialog { border: 0; border-radius: 16px; padding: 0; width: calc(100% - 32px); max-width: 440px; background: var(--crema-card); color: var(--texto); box-shadow: 0 24px 60px rgba(0,0,0,.35); }
  dialog::backdrop { background: rgba(26,46,29,.55); }
  .dlg { padding: 28px; display: flex; flex-direction: column; gap: 16px; }
  .dlg h2 { font-family: var(--serif); font-size: 26px; font-weight: 600; margin: 0; }
  .dlg .sub { font-size: 14px; color: var(--texto-suave); margin-top: 4px; }
  .precio-fila { display: flex; align-items: center; border: 1px solid var(--borde); background: #fff; border-radius: 10px; height: 50px; padding-left: 14px; }
  .precio-fila span { font-weight: 600; color: var(--texto-suave); }
  .precio-fila input { border: 0; background: transparent; height: 100%; flex: 1; min-width: 0; padding: 0 10px 0 6px; font-size: 18px; font-weight: 600; outline: none; }
  .precio-fila:focus-within { outline: 2px solid var(--mostaza); outline-offset: 1px; }
  .fila-sw { display: flex; justify-content: space-between; align-items: center; gap: 12px; min-height: 52px; border-bottom: 1px solid var(--borde-suave); font-size: 15px; font-weight: 500; cursor: pointer; }
  .fila-sw small { display: block; font-size: 12px; font-weight: 400; color: var(--texto-suave); margin-top: 2px; }
  .acciones { display: flex; justify-content: flex-end; gap: 10px; flex-wrap: wrap; padding-top: 4px; }

  .toast { position: fixed; left: 50%; bottom: 24px; transform: translateX(-50%); background: var(--texto); color: #fff; padding: 12px 18px; border-radius: 10px; font-size: 14px; max-width: calc(100% - 32px); box-shadow: 0 8px 24px rgba(0,0,0,.2); z-index: 20; }

  /* ─── Celu ─── */
  @media (max-width: 760px) {
    .login-marca { padding: 32px 28px; min-height: 240px; justify-content: flex-end; gap: 12px; }
    .login-marca p, .login-pie { display: none; }
    .login-marca h1 { font-size: 44px; margin-bottom: 18px; }
    .raya { margin-bottom: 0; }
    .login-lado { padding: 28px; align-items: flex-start; }

    .app { flex-direction: column; padding-bottom: 64px; }
    .lateral { display: none; }
    .topbar-m { display: flex; align-items: center; justify-content: space-between; background: var(--verde); color: var(--crema); padding: 14px 16px; }
    .topbar-m .marca { font-family: var(--serif); font-size: 22px; font-weight: 600; }
    .topbar-m button { background: none; border: 0; color: inherit; font-size: 14px; min-height: 44px; padding: 0 4px; }
    .principal { padding: 16px 16px 24px; gap: 14px; }
    .cabecera h1 { font-size: 26px; }
    .cabecera .btn-agregar { display: none; }
    .buscar, .filtro-cat { flex-basis: 100%; max-width: none; }
    .chips-filtro { flex-wrap: nowrap; overflow-x: auto; width: 100%; padding-bottom: 4px; }
    .chip-f { flex: none; height: 44px; }

    .tabla { background: transparent; border: 0; overflow: visible; }
    .tabla-inner { min-width: 0; }
    #lista { display: flex; flex-direction: column; gap: 12px; }
    .fila.encabezado { display: none; }
    .fila { grid-template-columns: 24px 1fr auto; grid-template-areas: "grip info editar" "vars vars vars" "tg tg tg"; border: 1px solid var(--borde); border-radius: 14px; padding: 14px; gap: 10px; }
    #lista .fila:last-child { border-bottom: 1px solid var(--borde); }
    .grip { grid-area: grip; }
    .foto { display: none; }
    .info { grid-area: info; }
    .vars { grid-area: vars; }
    .celda-editar { grid-area: editar; }
    .toggles { display: flex; grid-area: tg; justify-content: space-between; border-top: 1px solid var(--borde-suave); padding-top: 4px; }
    .tg-m { display: inline; }
    .btn-editar { padding: 11px 16px; }

    .tabbar { display: grid; position: fixed; left: 0; right: 0; bottom: 0; height: 64px; background: var(--crema-card); border-top: 1px solid var(--borde); grid-template-columns: repeat(4, 1fr); z-index: 10; }
    .tab { display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 2px; font-size: 13px; color: var(--texto-suave); background: none; border: 0; }
    .tab.activo { background: var(--verde-claro); color: var(--verde); font-weight: 700; }
    .tab .tag { font-size: 9px; padding: 1px 5px; }
    .toast { bottom: 80px; }
  }
</style>
</head>
<body>

<!-- ═══ INGRESO ═══ -->
<div id="vistaLogin" class="login" hidden>
  <section class="login-marca">
    <div class="kicker">Panel de administración</div>
    <div>
      <h1 data-tienda></h1>
      <div class="raya"></div>
      <p>Cargá productos, precios y stock de tu tienda sin abrir el Google Sheet.</p>
    </div>
    <div class="login-pie">Acceso privado</div>
  </section>
  <main class="login-lado">
    <form id="formLogin" class="login-form" novalidate>
      <div>
        <h2 class="titulo">Ingresar</h2>
        <p class="bajada">Escribí la contraseña del panel.</p>
      </div>
      <div class="campo">
        <label for="clave">Contraseña</label>
        <div class="clave-fila">
          <input id="clave" class="input" type="password" autocomplete="current-password" placeholder="Tu contraseña">
          <button type="button" id="btnMostrar" class="btn btn-borde" aria-controls="clave">Mostrar</button>
        </div>
      </div>
      <label class="recordar"><input id="recordar" type="checkbox" class="sw" checked> Recordarme en este dispositivo</label>
      <div id="loginError" class="msg-error" role="alert" hidden></div>
      <button id="btnEntrar" class="btn btn-primario" type="submit" style="height: 52px; font-size: 16px">Entrar</button>
      <p class="nota">Esta página es solo para el equipo de <span data-tienda></span>.</p>
    </form>
  </main>
</div>

<!-- ═══ PANEL ═══ -->
<div id="vistaPanel" class="app" hidden>
  <nav class="lateral" aria-label="Menú">
    <div class="marca" data-tienda></div>
    <div class="sub">Panel de administración</div>
    <button class="nav-item activo" aria-current="page">Productos</button>
    <button class="nav-item" aria-disabled="true" title="Llega en la próxima etapa">Agregar producto <span class="tag">pronto</span></button>
    <button class="nav-item" aria-disabled="true" title="Llega más adelante">Pedidos <span class="tag">pronto</span></button>
    <button class="nav-item" aria-disabled="true" title="Llega más adelante">Ajustes <span class="tag">pronto</span></button>
    <div class="espacio"></div>
    <button class="nav-item salir" data-salir>Cerrar sesión</button>
  </nav>

  <div class="topbar-m">
    <span class="marca" data-tienda></span>
    <button data-salir>Salir</button>
  </div>

  <main class="principal">
    <header class="cabecera">
      <div>
        <h1>Productos</h1>
        <div id="resumen" class="resumen">&nbsp;</div>
      </div>
      <div class="cab-der">
        <span id="estado" class="estado" role="status">Cambios guardados</span>
        <button class="btn btn-agregar" disabled title="Llega en la próxima etapa">+ Agregar producto</button>
      </div>
    </header>

    <div class="filtros">
      <label class="buscar">
        <span class="sr">Buscar producto</span>
        <input id="buscar" class="input" type="search" placeholder="Buscar por nombre o marca" autocomplete="off">
      </label>
      <label class="filtro-cat">
        <span class="sr">Categoría</span>
        <select id="categoria" class="input"><option value="">Todas las categorías</option></select>
      </label>
      <div class="chips-filtro" role="group" aria-label="Filtrar">
        <button class="chip-f" data-tipo="todos" aria-pressed="true">Todos</button>
        <button class="chip-f" data-tipo="sinstock" aria-pressed="false">Sin stock</button>
        <button class="chip-f" data-tipo="ocultos" aria-pressed="false">Ocultos</button>
        <button class="chip-f" data-tipo="oferta" aria-pressed="false">En oferta</button>
        <button class="chip-f" data-tipo="top" aria-pressed="false">Más vendidos</button>
      </div>
    </div>

    <p class="ayuda">Tocá un precio para cambiarlo o marcarlo en oferta (los dorados están en oferta). Los interruptores se guardan solos. <span id="ayudaOrden"></span></p>

    <section class="tabla" aria-label="Productos">
      <div class="tabla-inner">
        <div class="fila encabezado" aria-hidden="true">
          <div></div><div></div><div>Producto</div><div>Variantes y precios</div>
          <div class="c">En stock</div><div class="c">Visible</div><div class="c">Más vendido</div><div></div>
        </div>
        <div id="lista"></div>
      </div>
    </section>
  </main>

  <nav class="tabbar" aria-label="Secciones">
    <button class="tab activo" aria-current="page">Productos</button>
    <button class="tab" aria-disabled="true">Agregar <span class="tag">pronto</span></button>
    <button class="tab" aria-disabled="true">Pedidos <span class="tag">pronto</span></button>
    <button class="tab" aria-disabled="true">Ajustes <span class="tag">pronto</span></button>
  </nav>
</div>

<!-- ═══ VENTANA: VARIANTE ═══ -->
<dialog id="dlgVariante" aria-labelledby="dvTitulo">
  <form id="formVariante" class="dlg" novalidate>
    <div>
      <h2 id="dvTitulo">Variante</h2>
      <div id="dvProducto" class="sub"></div>
    </div>
    <div class="campo">
      <label for="dvPrecio">Precio</label>
      <div class="precio-fila"><span>$</span><input id="dvPrecio" type="text" inputmode="numeric" autocomplete="off"></div>
    </div>
    <div>
      <label class="fila-sw"><span>Oferta de la semana<small>Aparece destacada en la tienda.</small></span><input id="dvOferta" type="checkbox" class="sw"></label>
      <label class="fila-sw"><span>Activa<small>Si la apagás, esta cantidad no se ve en la tienda.</small></span><input id="dvActiva" type="checkbox" class="sw"></label>
    </div>
    <div id="dvError" class="msg-error" role="alert" hidden></div>
    <div class="acciones">
      <button type="button" id="dvCancelar" class="btn btn-borde">Cancelar</button>
      <button type="submit" id="dvGuardar" class="btn btn-primario">Guardar</button>
    </div>
  </form>
</dialog>

<div id="toast" class="toast" role="status" hidden></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/Sortable/1.15.2/Sortable.min.js"></script>
<script>
/* ════════════════════════════════════════════════════════════════
   CONFIGURACIÓN DE LA TIENDA
   Lo único que hay que cambiar para usar este panel en otra tienda.
   ════════════════════════════════════════════════════════════════ */
const CONFIG = {
  tienda: 'En Tren Verde',
  // Dirección del script de guardado del panel (termina en /exec):
  api: 'PEGAR_ACA_LA_URL_DEL_SCRIPT_DEL_PANEL'
};

(function () {
  'use strict';

  const $ = s => document.querySelector(s);
  const CLAVE_TOKEN = 'panel_token';
  const GRIP = '<svg width="14" height="20" viewBox="0 0 14 20" aria-hidden="true"><g fill="#8A9A8C"><circle cx="4" cy="4" r="1.6"/><circle cx="10" cy="4" r="1.6"/><circle cx="4" cy="10" r="1.6"/><circle cx="10" cy="10" r="1.6"/><circle cx="4" cy="16" r="1.6"/><circle cx="10" cy="16" r="1.6"/></g></svg>';

  let token = leerToken();
  let datos = { productos: [], variantes: [], categorias: [] };
  const filtro = { texto: '', cat: '', tipo: 'todos' };
  let sortable = null;
  let pendientes = 0;
  let huboError = false;
  let editando = null;

  // ─── Utilidades ───
  const esc = s => String(s == null ? '' : s).replace(/[&<>"']/g, c => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]));
  const num = v => typeof v === 'number' ? Math.round(v) : (parseInt(String(v == null ? '' : v).replace(/[^0-9]/g, ''), 10) || 0);
  const precioTxt = v => '$' + num(v).toLocaleString('es-AR');
  const SI = v => String(v == null ? '' : v).trim().toUpperCase() === 'SI';
  const normal = s => String(s == null ? '' : s).normalize('NFD').replace(/[̀-ͯ]/g, '').toLowerCase();
  const prod = id => datos.productos.find(p => String(p.id) === String(id));
  const varsDe = id => datos.variantes.filter(v => String(v.producto_id) === String(id));
  const tieneOferta = id => varsDe(id).some(v => SI(v.oferta_semana) && SI(v.activo));
  const catNombre = id => { const c = datos.categorias.find(c => String(c.id) === String(id)); return c ? c.nombre : 'Sin categoría'; };

  function miniatura(url) {
    const s = String(url || '');
    const m = s.match(/\/d\/([\w-]{20,})/) || s.match(/[?&]id=([\w-]{20,})/);
    return m ? 'https://drive.google.com/thumbnail?id=' + m[1] + '&sz=w120' : s;
  }

  function leerToken() {
    try { return localStorage.getItem(CLAVE_TOKEN) || sessionStorage.getItem(CLAVE_TOKEN) || ''; } catch (e) { return ''; }
  }
  function guardarToken(t, recordar) {
    token = t;
    try {
      localStorage.removeItem(CLAVE_TOKEN);
      sessionStorage.removeItem(CLAVE_TOKEN);
      (recordar ? localStorage : sessionStorage).setItem(CLAVE_TOKEN, t);
    } catch (e) { /* sin almacenamiento: la sesión dura mientras la página esté abierta */ }
  }
  function borrarToken() {
    token = '';
    try { localStorage.removeItem(CLAVE_TOKEN); sessionStorage.removeItem(CLAVE_TOKEN); } catch (e) {}
  }

  let timerToast = null;
  function aviso(msg) {
    const t = $('#toast');
    t.textContent = msg;
    t.hidden = false;
    clearTimeout(timerToast);
    timerToast = setTimeout(() => { t.hidden = true; }, 5000);
  }

  // ─── Conexión con el script ───
  async function api(accion, extra) {
    if (!/^https:\/\/script\.google\.com\//.test(CONFIG.api)) {
      throw new Error('Falta configurar la dirección del script (CONFIG.api) en el archivo del panel.');
    }
    let res;
    try {
      res = await fetch(CONFIG.api, { method: 'POST', body: JSON.stringify(Object.assign({ accion: accion, token: token }, extra || {})) });
    } catch (e) {
      throw new Error('No hay conexión con el catálogo. Revisá internet y probá de nuevo.');
    }
    let j;
    try { j = await res.json(); } catch (e) {
      throw new Error('El script respondió algo inesperado. ¿Está implementado como aplicación web con acceso para "Cualquier usuario"?');
    }
    if (!j.ok) {
      const err = new Error(j.error || 'Algo salió mal.');
      err.codigo = j.codigo;
      if (j.codigo === 'auth' && accion !== 'login') { borrarToken(); mostrarLogin(j.error); }
      throw err;
    }
    return j.data;
  }

  // ─── Estado de guardado ───
  function empezar() { pendientes++; pintarEstado(); }
  function terminar(ok, msg, silencioso) {
    pendientes = Math.max(0, pendientes - 1);
    if (!ok) { huboError = true; if (!silencioso) aviso(msg); }
    else if (pendientes === 0) huboError = false;
    pintarEstado();
  }
  function pintarEstado() {
    const e = $('#estado');
    e.className = 'estado';
    if (pendientes) { e.classList.add('guardando'); e.textContent = 'Guardando…'; }
    else if (huboError) { e.classList.add('error'); e.textContent = 'No se pudo guardar'; }
    else e.textContent = 'Cambios guardados';
  }
  window.addEventListener('beforeunload', e => { if (pendientes) { e.preventDefault(); e.returnValue = ''; } });

  // ─── Ingreso ───
  function mostrarLogin(msg) {
    $('#vistaPanel').hidden = true;
    $('#vistaLogin').hidden = false;
    const e = $('#loginError');
    e.textContent = msg || '';
    e.hidden = !msg;
    setTimeout(() => $('#clave').focus(), 50);
  }

  $('#btnMostrar').addEventListener('click', () => {
    const i = $('#clave');
    const ver = i.type === 'password';
    i.type = ver ? 'text' : 'password';
    $('#btnMostrar').textContent = ver ? 'Ocultar' : 'Mostrar';
  });

  $('#formLogin').addEventListener('submit', async ev => {
    ev.preventDefault();
    const clave = $('#clave').value;
    const err = $('#loginError');
    if (!clave) { err.textContent = 'Escribí la contraseña.'; err.hidden = false; return; }
    const btn = $('#btnEntrar');
    btn.disabled = true;
    btn.textContent = 'Entrando…';
    err.hidden = true;
    try {
      const recordar = $('#recordar').checked;
      const r = await api('login', { clave: clave, recordar: recordar });
      guardarToken(r.token, recordar);
      $('#clave').value = '';
      entrar();
    } catch (e) {
      err.textContent = e.message;
      err.hidden = false;
    } finally {
      btn.disabled = false;
      btn.textContent = 'Entrar';
    }
  });

  async function salir() {
    try { await api('logout'); } catch (e) {}
    borrarToken();
    datos = { productos: [], variantes: [], categorias: [] };
    mostrarLogin();
  }
  document.querySelectorAll('[data-salir]').forEach(b => b.addEventListener('click', salir));

  // ─── Carga ───
  function entrar() {
    $('#vistaLogin').hidden = true;
    $('#vistaPanel').hidden = false;
    cargar();
  }

  async function cargar() {
    $('#lista').innerHTML = '<div class="vacio">Cargando catálogo…</div>';
    try {
      datos = await api('listar');
      llenarCategorias();
      render();
      pintarEstado();
    } catch (e) {
      if (e.codigo === 'auth') return;
      $('#lista').innerHTML = '<div class="vacio">' + esc(e.message) + '<br><br><button class="btn btn-borde" id="btnReintentar">Reintentar</button></div>';
      $('#btnReintentar').addEventListener('click', cargar);
    }
  }

  function llenarCategorias() {
    const sel = $('#categoria');
    const cats = datos.categorias.slice().sort((a, b) => num(a.orden) - num(b.orden));
    sel.innerHTML = '<option value="">Todas las categorías</option>' +
      cats.map(c => '<option value="' + esc(c.id) + '">' + esc(c.nombre) + '</option>').join('');
    sel.value = filtro.cat;
  }

  // ─── Lista ───
  function visibles() {
    const t = normal(filtro.texto.trim());
    return datos.productos.filter(p => {
      if (filtro.cat && String(p.categoria_id) !== filtro.cat) return false;
      if (t && !normal(p.nombre + ' ' + p.marca).includes(t)) return false;
      switch (filtro.tipo) {
        case 'sinstock': return !SI(p.stock);
        case 'ocultos': return !SI(p.activo);
        case 'oferta': return tieneOferta(p.id);
        case 'top': return SI(p.mas_vendidos);
        default: return true;
      }
    });
  }

  const puedeOrdenar = () => !!filtro.cat && filtro.tipo === 'todos' && !filtro.texto.trim();

  function actualizarResumen() {
    const ps = datos.productos;
    const sin = ps.filter(p => !SI(p.stock)).length;
    const oc = ps.filter(p => !SI(p.activo)).length;
    const of = ps.filter(p => tieneOferta(p.id)).length;
    $('#resumen').textContent = ps.length + ' productos · ' + sin + ' sin stock · ' + oc + ' ocultos · ' + of + ' en oferta';
  }

  function filaHTML(p, orden) {
    const id = String(p.id);
    const nombre = esc(p.nombre);
    const inicial = esc((String(p.nombre || '?').trim().charAt(0) || '?').toUpperCase());
    const src = miniatura(p.foto_url);
    const visible = SI(p.activo);

    const chips = varsDe(id).map(v =>
      '<button type="button" class="chip' + (SI(v.oferta_semana) ? ' oferta' : '') + (SI(v.activo) ? '' : ' inactiva') + '" data-fila="' + v.fila + '"' +
      ' aria-label="' + esc(v.cantidad_label) + ', ' + esc(precioTxt(v.precio)) + (SI(v.oferta_semana) ? ', en oferta' : '') + (SI(v.activo) ? '' : ', oculta') + '. Editar">' +
      esc(v.cantidad_label) + ' · ' + esc(precioTxt(v.precio)) + '</button>'
    ).join('') || '<span class="meta">Sin variantes</span>';

    const tg = (campo, etiqueta, valor) =>
      '<label class="tg"><input type="checkbox" class="sw" data-campo="' + campo + '"' + (SI(valor) ? ' checked' : '') +
      ' aria-label="' + etiqueta + ': ' + nombre + '"><span class="tg-m">' + etiqueta + '</span></label>';

    return '<div class="fila' + (visible ? '' : ' oculto') + '" data-id="' + esc(id) + '">' +
      '<button type="button" class="grip" aria-label="Arrastrar para ordenar: ' + nombre + '"' + (orden ? '' : ' disabled') + '>' + GRIP + '</button>' +
      '<div class="foto" aria-hidden="true">' + inicial + (src ? '<img src="' + esc(src) + '" alt="" loading="lazy">' : '') + '</div>' +
      '<div class="info"><div class="nombre">' + nombre + (visible ? '' : '<span class="badge">Oculto</span>') + '</div>' +
      '<div class="meta">' + esc(p.marca || 'Sin marca') + ' · ' + esc(catNombre(p.categoria_id)) + '</div></div>' +
      '<div class="vars">' + chips + '</div>' +
      '<div class="toggles">' + tg('stock', 'Stock', p.stock) + tg('activo', 'Visible', p.activo) + tg('mas_vendidos', 'Más vendido', p.mas_vendidos) + '</div>' +
      '<div class="celda-editar"><button type="button" class="btn-editar" disabled title="Llega en la próxima etapa">Editar</button></div>' +
      '</div>';
  }

  function render() {
    actualizarResumen();
    const orden = puedeOrdenar();
    $('#ayudaOrden').textContent = orden
      ? 'Arrastrá el agarre de la izquierda para cambiar el orden en la tienda.'
      : 'Para cambiar el orden, elegí una categoría y dejá el filtro en "Todos".';

    if (sortable) { sortable.destroy(); sortable = null; }
    const lista = visibles();
    const cont = $('#lista');
    if (!lista.length) {
      cont.innerHTML = '<div class="vacio">No hay productos con ese filtro.</div>';
      return;
    }
    cont.innerHTML = lista.map(p => filaHTML(p, orden)).join('');
    if (orden && window.Sortable) {
      sortable = Sortable.create(cont, {
        handle: '.grip',
        draggable: '.fila',
        forceFallback: true,
        fallbackTolerance: 3,
        animation: 150,
        ghostClass: 'sortable-ghost',
        chosenClass: 'sortable-chosen',
        onEnd: alSoltar
      });
    }
  }

  function refrescarFila(id, campoFoco) {
    const el = $('#lista').querySelector('.fila[data-id="' + CSS.escape(String(id)) + '"]');
    const p = prod(id);
    if (!el || !p) return;
    el.outerHTML = filaHTML(p, puedeOrdenar());
    if (campoFoco) {
      const nuevo = $('#lista').querySelector('.fila[data-id="' + CSS.escape(String(id)) + '"] input[data-campo="' + campoFoco + '"]');
      if (nuevo) nuevo.focus();
    }
  }

  // Fotos que no cargan: queda la inicial.
  document.addEventListener('error', e => {
    if (e.target && e.target.tagName === 'IMG' && e.target.closest('.foto')) e.target.classList.add('rota');
  }, true);

  // ─── Interruptores ───
  $('#lista').addEventListener('change', e => {
    const input = e.target;
    if (!input.matches('input.sw[data-campo]')) return;
    cambiarCampo(input.closest('.fila').dataset.id, input.dataset.campo, input.checked, input);
  });

  async function cambiarCampo(id, campo, marcado, input) {
    const p = prod(id);
    if (!p) return;
    const antes = p[campo];
    p[campo] = marcado ? 'SI' : 'NO';
    input.disabled = true;
    const teniaFoco = document.activeElement === input;
    empezar();
    try {
      await api('campoProducto', { id: id, campo: campo, valor: p[campo] });
      terminar(true);
    } catch (e) {
      p[campo] = antes;
      if (e.codigo !== 'auth') terminar(false, e.message); else terminar(false, '', true);
    } finally {
      refrescarFila(id, teniaFoco ? campo : '');
      actualizarResumen();
    }
  }

  // ─── Variantes ───
  $('#lista').addEventListener('click', e => {
    const chip = e.target.closest('.chip');
    if (chip) abrirVariante(chip.closest('.fila').dataset.id, Number(chip.dataset.fila));
  });

  function abrirVariante(id, fila) {
    const v = datos.variantes.find(x => x.fila === fila && String(x.producto_id) === String(id));
    const p = prod(id);
    if (!v || !p) return;
    editando = { v: v, p: p };
    $('#dvTitulo').textContent = 'Variante ' + v.cantidad_label;
    $('#dvProducto').textContent = p.nombre + (p.marca ? ' · ' + p.marca : '');
    $('#dvPrecio').value = num(v.precio).toLocaleString('es-AR');
    $('#dvOferta').checked = SI(v.oferta_semana);
    $('#dvActiva').checked = SI(v.activo);
    $('#dvError').hidden = true;
    $('#dlgVariante').showModal();
    $('#dvPrecio').select();
  }

  $('#dvPrecio').addEventListener('input', e => {
    const n = num(e.target.value);
    e.target.value = n ? n.toLocaleString('es-AR') : '';
  });

  $('#dvCancelar').addEventListener('click', () => $('#dlgVariante').close());

  $('#formVariante').addEventListener('submit', async ev => {
    ev.preventDefault();
    if (!editando) return;
    const err = $('#dvError');
    const precio = num($('#dvPrecio').value);
    if (precio <= 0) { err.textContent = 'Escribí un precio mayor a 0.'; err.hidden = false; return; }
    const btn = $('#dvGuardar');
    btn.disabled = true;
    btn.textContent = 'Guardando…';
    err.hidden = true;
    const ed = editando;
    empezar();
    try {
      const r = await api('variante', {
        fila: ed.v.fila, productoId: String(ed.p.id), label: ed.v.cantidad_label,
        precio: precio, oferta: $('#dvOferta').checked, activo: $('#dvActiva').checked
      });
      Object.assign(ed.v, { fila: r.fila, precio: r.precio, oferta_semana: r.oferta, activo: r.activo });
      terminar(true);
      $('#dlgVariante').close();
      refrescarFila(ed.p.id);
      actualizarResumen();
    } catch (e) {
      terminar(false, e.message, true);
      if (e.codigo !== 'auth') { err.textContent = e.message; err.hidden = false; }
      else $('#dlgVariante').close();
    } finally {
      btn.disabled = false;
      btn.textContent = 'Guardar';
    }
  });

  // ─── Orden ───
  async function alSoltar() {
    const idsCat = Array.from($('#lista').querySelectorAll('.fila')).map(el => el.dataset.id);
    let k = 0;
    const nuevo = datos.productos.map(p => String(p.categoria_id) === filtro.cat ? idsCat[k++] : String(p.id));
    const antes = datos.productos.map(p => String(p.id));
    if (nuevo.join('|') === antes.join('|')) return;

    const porId = {};
    datos.productos.forEach(p => { porId[String(p.id)] = p; });
    const anterior = datos.productos;
    datos.productos = nuevo.map(id => porId[id]);
    empezar();
    try {
      await api('reordenar', { ids: nuevo });
      terminar(true);
    } catch (e) {
      datos.productos = anterior;
      if (e.codigo !== 'auth') { terminar(false, e.message); render(); } else terminar(false, '', true);
    }
  }

  // ─── Filtros ───
  let timerBuscar = null;
  $('#buscar').addEventListener('input', e => {
    clearTimeout(timerBuscar);
    timerBuscar = setTimeout(() => { filtro.texto = e.target.value; render(); }, 150);
  });
  $('#categoria').addEventListener('change', e => { filtro.cat = e.target.value; render(); });
  document.querySelectorAll('.chip-f').forEach(b => b.addEventListener('click', () => {
    document.querySelectorAll('.chip-f').forEach(x => x.setAttribute('aria-pressed', String(x === b)));
    filtro.tipo = b.dataset.tipo;
    render();
  }));

  // ─── Inicio ───
  document.title = 'Panel · ' + CONFIG.tienda;
  document.querySelectorAll('[data-tienda]').forEach(el => { el.textContent = CONFIG.tienda; });
  if (token) entrar(); else mostrarLogin();
})();
</script>
</body>
</html>
