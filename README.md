<!-- Interactive Mobile Hub -->
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&amp;family=JetBrains+Mono:wght@400;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "secondary-container": "#45474a",
                        "outline": "#919191",
                        "on-secondary": "#1a1c1f",
                        "tertiary-fixed": "#5c5f63",
                        "surface-tint": "#c6c6c6",
                        "on-tertiary-fixed": "#ffffff",
                        "inverse-primary": "#5d5f5f",
                        "secondary-fixed": "#c6c6ca",
                        "on-surface-variant": "#c6c6c6",
                        "primary-fixed-dim": "#454747",
                        "surface-container": "#1e2022",
                        "on-tertiary": "#191c1f",
                        "secondary-fixed-dim": "#aaabaf",
                        "primary-container": "#d4d4d4",
                        "surface-variant": "#333537",
                        "surface-container-high": "#282a2c",
                        "on-background": "#e2e2e5",
                        "surface-container-low": "#1a1c1e",
                        "on-secondary-container": "#e2e2e6",
                        "on-error": "#690005",
                        "outline-variant": "#474747",
                        "on-tertiary-fixed-variant": "#e1e2e7",
                        "surface": "#121416",
                        "inverse-on-surface": "#2f3133",
                        "surface-bright": "#37393b",
                        "surface-container-highest": "#333537",
                        "primary": "#ffffff",
                        "on-surface": "#e2e2e5",
                        "on-tertiary-container": "#000000",
                        "on-error-container": "#ffdad6",
                        "tertiary": "#e1e2e7",
                        "error": "#ffb4ab",
                        "on-primary": "#1a1c1c",
                        "tertiary-fixed-dim": "#44474b",
                        "surface-dim": "#121416",
                        "on-secondary-fixed-variant": "#3a3b3f",
                        "inverse-surface": "#e2e2e5",
                        "secondary": "#c6c6ca",
                        "tertiary-container": "#8e9195",
                        "on-secondary-fixed": "#1a1c1f",
                        "error-container": "#93000a",
                        "primary-fixed": "#5d5f5f",
                        "on-primary-fixed-variant": "#e2e2e2",
                        "on-primary-fixed": "#ffffff",
                        "on-primary-container": "#000000",
                        "surface-container-lowest": "#0c0e10",
                        "background": "#121416"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "fontFamily": {
                        "headline": ["Inter"],
                        "body": ["Inter"],
                        "label": ["Inter"],
                        "mono": ["JetBrains Mono"]
                    }
                }
            }
        }
    </script>
<style>
        body { font-family: 'Inter', sans-serif; background-color: #121416; color: #e2e2e5; }
        .material-symbols-outlined { font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24; }
        .glass-panel { background: rgba(55, 57, 59, 0.6); backdrop-filter: blur(20px); }
        .milled-surface { background: linear-gradient(145deg, #1e2022, #121416); }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="antialiased overflow-x-hidden">
<!-- Top Navigation Anchor -->
<header class="fixed top-0 w-full z-50 bg-[#121416] flex items-center justify-between px-6 h-16 w-full">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-white" data-icon="precision_manufacturing">precision_manufacturing</span>
<h1 class="text-white font-inter tracking-tight font-bold uppercase text-lg font-black tracking-tighter">PROMPT_LAB</h1>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#C6C6CA] cursor-pointer" data-icon="search">search</span>
<div class="w-8 h-8 rounded-full bg-surface-container-highest border border-outline-variant/15 flex items-center justify-center overflow-hidden">
<img class="w-full h-full object-cover" data-alt="Cybernetic profile avatar with blue glowing circuits on a dark metallic surface" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAmK_KxeDj1IX8a2FshcP2W3pIX66JlCPgjmTHodcMLBIsvu5MDV55Sf6zrXNWCoTyfXb6u0gS7gSPdrmI3mnr-MH3cp5NVsYlZXJ-_88pI5Yc5JjAFX5meYy3j2o6A2lOeXlroSDAgx9i55znaryigtbEDQgea6gyog3mnPQ_if2dFbwNSD85jlTQWB5AlJBOCmml9hFExTzE-sxL36cO7Df3nceqcCe1JDletF4mqrf5GKvSQg7Kxp67JQhJ90QcXJLaoastBD6c"/>
</div>
</div>
</header>
<!-- Desktop Sidebar (Hidden on Mobile) -->
<aside class="h-screen w-64 fixed left-0 top-0 hidden md:block bg-[#1A1C1E] flex flex-col p-4 space-y-2">
<div class="text-xl font-bold text-white mb-8 px-2">CORE_NAV</div>
<nav class="flex flex-col space-y-1">
<a class="bg-[#1E2022] text-white rounded flex items-center gap-3 p-3 transition-all duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="architecture">architecture</span>
<span class="font-inter text-sm font-medium tracking-wide">Construct</span>
</a>
<a class="text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded flex items-center gap-3 p-3 transition-all duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="history">history</span>
<span class="font-inter text-sm font-medium tracking-wide">History</span>
</a>
<a class="text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded flex items-center gap-3 p-3 transition-all duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="star">star</span>
<span class="font-inter text-sm font-medium tracking-wide">Favorites</span>
</a>
<a class="text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded flex items-center gap-3 p-3 transition-all duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="menu_book">menu_book</span>
<span class="font-inter text-sm font-medium tracking-wide">Glossary</span>
</a>
</nav>
</aside>
<!-- Main Canvas -->
<main class="pt-20 pb-24 md:pl-72 px-4 min-h-screen">
<!-- Dashboard Data Ribbon -->
<section class="w-full bg-surface-container-highest rounded-lg mb-8 p-3 flex justify-around items-center overflow-x-auto whitespace-nowrap gap-6 no-scrollbar">
<div class="flex flex-col">
<span class="text-[10px] text-on-surface-variant uppercase tracking-widest font-bold">Active_Nodes</span>
<span class="text-primary font-mono text-lg">12.80</span>
</div>
<div class="w-px h-8 bg-outline-variant/30"></div>
<div class="flex flex-col">
<span class="text-[10px] text-on-surface-variant uppercase tracking-widest font-bold">Latency_MS</span>
<span class="text-primary font-mono text-lg">42</span>
</div>
<div class="w-px h-8 bg-outline-variant/30"></div>
<div class="flex flex-col">
<span class="text-[10px] text-on-surface-variant uppercase tracking-widest font-bold">Token_Flux</span>
<span class="text-primary font-mono text-lg">0.998</span>
</div>
</section>
<!-- Bento Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-3 gap-4">
<!-- Main Construct Card (Priority) -->
<div class="md:col-span-2 bg-surface-container rounded-xl p-6 relative overflow-hidden flex flex-col justify-between min-h-[280px]">
<div class="relative z-10">
<span class="text-on-surface-variant text-[10px] uppercase tracking-widest font-bold mb-2 block">Primary Engine</span>
<h2 class="text-3xl font-extrabold tracking-tighter text-white mb-4 leading-none">TERMINAL<br/>ARCHITECT</h2>
<p class="text-on-surface-variant text-sm max-w-xs mb-6">Initialize visual code structures from semantic natural language parameters.</p>
</div>
<div class="relative z-10">
<button class="bg-primary text-on-primary px-5 py-2.5 rounded-md font-bold text-sm tracking-tight flex items-center gap-2 active:scale-95 transition-transform">
                        INITIALIZE CONSTRUCT
                        <span class="material-symbols-outlined text-sm" data-icon="arrow_forward">arrow_forward</span>
</button>
</div>
<!-- Background Image Decoration -->
<div class="absolute right-0 bottom-0 top-0 w-1/2 opacity-40">
<img class="w-full h-full object-cover" data-alt="Abstract 3D crystalline structure in monochrome shades of graphite and silver, with sharp edges and dramatic lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBzuvWB_-DweiutZmGjxTbunYaEnkI9kSMUie0TaVjJT1aKVYygfycMtNwKWAb_Keqtb35J9tsqaIUoxwNp-Z8sKrNQ6sOupMoata5BzWI6YQ7A9Eqzb55ojLq3J9D-SaKzdbeU_5NAVS4jHes3k9QwjdHva3xE9mB_1aTMlnGOYwtAWtUsuNZ93b9DyYvkWXVD7-NgAH01qP0I9r2HC71-LItwCtwnpW59pvTURq7E2Rfd9QkGZauulh2AszF1_dv6cc-Vt_axfEo"/>
</div>
<div class="absolute inset-0 bg-gradient-to-r from-surface-container via-surface-container/80 to-transparent"></div>
</div>
<!-- Quick Favorites Card -->
<div class="bg-surface-container-low rounded-xl p-5 flex flex-col gap-4">
<div class="flex justify-between items-center">
<h3 class="text-sm font-bold uppercase tracking-widest text-white">Saved_Presets</h3>
<span class="material-symbols-outlined text-on-surface-variant text-lg" data-icon="star">star</span>
</div>
<div class="space-y-3">
<div class="p-3 bg-surface-container rounded-lg border-l-2 border-primary flex items-center justify-between">
<span class="text-xs font-mono">Neural_Net_V4</span>
<span class="material-symbols-outlined text-xs text-on-surface-variant" data-icon="more_vert">more_vert</span>
</div>
<div class="p-3 bg-surface-container rounded-lg border-l-2 border-outline-variant flex items-center justify-between">
<span class="text-xs font-mono">Quantum_API_Shell</span>
<span class="material-symbols-outlined text-xs text-on-surface-variant" data-icon="more_vert">more_vert</span>
</div>
<div class="p-3 bg-surface-container rounded-lg border-l-2 border-outline-variant flex items-center justify-between">
<span class="text-xs font-mono">Glass_UI_Template</span>
<span class="material-symbols-outlined text-xs text-on-surface-variant" data-icon="more_vert">more_vert</span>
</div>
</div>
</div>
<!-- JSON to Text Transformer Card -->
<div class="md:col-span-1 bg-surface-container rounded-xl p-6 flex flex-col gap-4 border border-outline-variant/10">
<div class="flex items-center gap-3">
<div class="p-2 bg-secondary-container rounded-lg">
<span class="material-symbols-outlined text-white" data-icon="data_object">data_object</span>
</div>
<h3 class="text-sm font-bold uppercase tracking-widest text-white">JSON_TO_TEXT</h3>
</div>
<div class="bg-surface-container-lowest rounded p-4 font-mono text-[11px] text-on-surface-variant min-h-[120px] relative">
<div class="flex items-center gap-1 mb-2">
<span class="text-error">"status"</span>: <span class="text-secondary">"ready"</span>,
                    </div>
<div class="flex items-center gap-1 mb-2">
<span class="text-error">"buffer"</span>: <span class="text-primary">1024</span>,
                    </div>
<div class="flex items-center gap-1">
<span class="text-error">"origin"</span>: <span class="text-secondary">"local_host"</span>
</div>
<button class="absolute bottom-3 right-3 p-2 bg-primary rounded-full text-on-primary active:scale-90 transition-transform">
<span class="material-symbols-outlined text-sm" data-icon="swap_horiz">swap_horiz</span>
</button>
</div>
<p class="text-[10px] text-on-surface-variant">Convert complex JSON schemas into readable technical documentation strings.</p>
</div>
<!-- Glossary / Knowledge Base Card -->
<div class="md:col-span-2 bg-surface-container-high rounded-xl p-6 flex items-center gap-6">
<div class="hidden sm:block w-24 h-24 rounded-lg overflow-hidden shrink-0">
<img class="w-full h-full object-cover grayscale opacity-50" data-alt="Extreme macro of a sleek laptop keyboard with dark keys and white glowing backlights" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD61GMMQwAl_IC5_PPPsVuQjiencjdbvR0miKUfTWdgGuhsx6vpMkL62FYMeBz9ScDfKuRd5jVPTlxlLwDHQc5Ifjp4enbKe7EnML0oxAQclSQkOZiqU_OlQYJF0208fxCnA-umsVPuLtIKxKYbXaW7mJogm8ZhTEU3Jtq5LC0Ijwv3pxSQU_sh9wxMPgc0tv_JZIXBd9zBcakWRTM5dr2YHRCjntxHkAs2OPVPPQeyKzKE1xS1OlusvKGlT9MdrxrdjV-hRMd5s80"/>
</div>
<div class="flex-grow">
<h3 class="text-white font-bold mb-2">CORE_GLOSSARY</h3>
<p class="text-on-surface-variant text-xs mb-4">Master the syntax of the Architect. 250+ technical definitions updated daily.</p>
<div class="flex gap-2">
<span class="bg-surface-container px-2 py-1 rounded text-[9px] font-mono text-secondary-fixed">#SYNTAX</span>
<span class="bg-surface-container px-2 py-1 rounded text-[9px] font-mono text-secondary-fixed">#LOGIC</span>
<span class="bg-surface-container px-2 py-1 rounded text-[9px] font-mono text-secondary-fixed">#FLUX</span>
</div>
</div>
<span class="material-symbols-outlined text-primary ml-auto" data-icon="chevron_right">chevron_right</span>
</div>
</div>
</main>
<!-- Bottom Navigation Shell (Mobile Only) -->
<nav class="fixed bottom-0 w-full z-50 md:hidden bg-[#1A1C1E] flex justify-around items-center px-4 h-16 w-full border-t border-[#474747]/15 shadow-[0_-4px_24px_-4px_rgba(0,0,0,0.12)]">
<a class="flex flex-col items-center justify-center text-white bg-[#1E2022] rounded-lg py-1 w-full active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="architecture">architecture</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Construct</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="history">history</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">History</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="star">star</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Favorites</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="menu_book">menu_book</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Glossary</span>
</a>
</nav>
<!-- Contextual Floating Action Button -->
<button class="fixed bottom-20 right-6 md:right-8 md:bottom-8 w-14 h-14 bg-primary text-on-primary rounded-full shadow-xl flex items-center justify-center z-40 active:scale-95 transition-transform">
<span class="material-symbols-outlined" data-icon="add">add</span>
</button>
</body></html>

<!-- Interactive Desktop Hub -->
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&amp;family=JetBrains+Mono:wght@400;700&amp;family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "secondary-container": "#45474a",
                        "outline": "#919191",
                        "on-secondary": "#1a1c1f",
                        "tertiary-fixed": "#5c5f63",
                        "surface-tint": "#c6c6c6",
                        "on-tertiary-fixed": "#ffffff",
                        "inverse-primary": "#5d5f5f",
                        "secondary-fixed": "#c6c6ca",
                        "on-surface-variant": "#c6c6c6",
                        "primary-fixed-dim": "#454747",
                        "surface-container": "#1e2022",
                        "on-tertiary": "#191c1f",
                        "secondary-fixed-dim": "#aaabaf",
                        "primary-container": "#d4d4d4",
                        "surface-variant": "#333537",
                        "surface-container-high": "#282a2c",
                        "on-background": "#e2e2e5",
                        "surface-container-low": "#1a1c1e",
                        "on-secondary-container": "#e2e2e6",
                        "on-error": "#690005",
                        "outline-variant": "#474747",
                        "on-tertiary-fixed-variant": "#e1e2e7",
                        "surface": "#121416",
                        "inverse-on-surface": "#2f3133",
                        "surface-bright": "#37393b",
                        "surface-container-highest": "#333537",
                        "primary": "#ffffff",
                        "on-surface": "#e2e2e5",
                        "on-tertiary-container": "#000000",
                        "on-error-container": "#ffdad6",
                        "tertiary": "#e1e2e7",
                        "error": "#ffb4ab",
                        "on-primary": "#1a1c1c",
                        "tertiary-fixed-dim": "#44474b",
                        "surface-dim": "#121416",
                        "on-secondary-fixed-variant": "#3a3b3f",
                        "inverse-surface": "#e2e2e5",
                        "secondary": "#c6c6ca",
                        "tertiary-container": "#8e9195",
                        "on-secondary-fixed": "#1a1c1f",
                        "error-container": "#93000a",
                        "primary-fixed": "#5d5f5f",
                        "on-primary-fixed-variant": "#e2e2e2",
                        "on-primary-fixed": "#ffffff",
                        "on-primary-container": "#000000",
                        "surface-container-lowest": "#0c0e10",
                        "background": "#121416"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "fontFamily": {
                        "headline": ["Inter"],
                        "body": ["Inter"],
                        "label": ["Inter"],
                        "mono": ["JetBrains Mono"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #121416;
            color: #e2e2e5;
            font-family: 'Inter', sans-serif;
        }
        .milled-shadow {
            box-shadow: 0 4px 24px -4px rgba(0,0,0,0.4);
        }
        .glass-panel {
            background: rgba(55, 57, 59, 0.6);
            backdrop-filter: blur(20px);
        }
    </style>
</head>
<body class="bg-surface selection:bg-primary selection:text-on-primary">
<!-- TopAppBar Shell -->
<header class="fixed top-0 w-full z-50 bg-[#121416] flex items-center justify-between px-6 h-16 w-full">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-white text-2xl" data-icon="precision_manufacturing">precision_manufacturing</span>
<h1 class="font-inter tracking-tight font-bold uppercase text-lg font-black tracking-tighter text-white">PROMPT_LAB</h1>
</div>
<div class="flex items-center gap-6">
<div class="hidden md:flex items-center gap-4">
<button class="text-[#C6C6CA] hover:bg-[#333537] transition-colors px-3 py-1 rounded text-sm font-medium cursor-pointer active:scale-95">SYSTEM_STATUS: NOMINAL</button>
<button class="text-white hover:bg-[#333537] transition-colors px-3 py-1 rounded text-sm font-medium cursor-pointer active:scale-95">v4.0.2-STABLE</button>
</div>
<div class="w-8 h-8 rounded bg-surface-container flex items-center justify-center border border-outline-variant/15">
<span class="material-symbols-outlined text-sm" data-icon="person">person</span>
</div>
</div>
</header>
<!-- Sidebar Navigation Shell -->
<aside class="h-screen w-64 fixed left-0 top-0 hidden md:block bg-[#1A1C1E] flex flex-col p-4 space-y-2 pt-20">
<div class="text-xl font-bold text-white mb-8 px-2">CORE_NAV</div>
<nav class="flex-1 space-y-1">
<a class="flex items-center gap-3 px-4 py-3 bg-[#1E2022] text-white rounded transition-all duration-200 ease-in-out cursor-pointer" href="#">
<span class="material-symbols-outlined" data-icon="architecture">architecture</span>
<span class="font-inter text-sm font-medium tracking-wide">Construct</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded transition-all duration-200 ease-in-out cursor-pointer" href="#">
<span class="material-symbols-outlined" data-icon="history">history</span>
<span class="font-inter text-sm font-medium tracking-wide">History</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded transition-all duration-200 ease-in-out cursor-pointer" href="#">
<span class="material-symbols-outlined" data-icon="star">star</span>
<span class="font-inter text-sm font-medium tracking-wide">Favorites</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-[#C6C6CA] hover:bg-[#1E2022] hover:text-white rounded transition-all duration-200 ease-in-out cursor-pointer" href="#">
<span class="material-symbols-outlined" data-icon="menu_book">menu_book</span>
<span class="font-inter text-sm font-medium tracking-wide">Glossary</span>
</a>
</nav>
<div class="mt-auto p-2 bg-surface-container rounded-lg">
<div class="text-[10px] uppercase tracking-widest text-outline mb-2">Power Consumption</div>
<div class="h-1 bg-surface-container-low w-full rounded-full overflow-hidden">
<div class="h-full bg-primary w-2/3"></div>
</div>
<div class="flex justify-between mt-1 font-mono text-[9px] text-outline">
<span>742 KW/H</span>
<span>82%</span>
</div>
</div>
</aside>
<!-- Main Content Stage -->
<main class="md:ml-64 pt-16 min-h-screen">
<!-- Data Ribbon Component -->
<section class="bg-surface-container-highest px-6 py-2 flex items-center justify-between border-y border-outline-variant/10">
<div class="flex gap-8 overflow-x-auto no-scrollbar">
<div class="flex items-center gap-2 whitespace-nowrap">
<span class="text-[10px] text-outline font-bold uppercase tracking-tighter">Latencies</span>
<span class="font-mono text-sm text-primary">12ms</span>
</div>
<div class="flex items-center gap-2 whitespace-nowrap">
<span class="text-[10px] text-outline font-bold uppercase tracking-tighter">Active Nodes</span>
<span class="font-mono text-sm text-primary">1,024</span>
</div>
<div class="flex items-center gap-2 whitespace-nowrap">
<span class="text-[10px] text-outline font-bold uppercase tracking-tighter">Throughput</span>
<span class="font-mono text-sm text-primary">8.4 GB/S</span>
</div>
<div class="flex items-center gap-2 whitespace-nowrap">
<span class="text-[10px] text-outline font-bold uppercase tracking-tighter">Sync Mode</span>
<span class="font-mono text-sm text-primary">QUARTZ</span>
</div>
</div>
<div class="flex items-center gap-2 text-[10px] text-outline font-bold uppercase">
<span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                LIVE_FEED
            </div>
</section>
<div class="p-8">
<!-- Bento Grid Dashboard (SCREEN_20) -->
<div class="grid grid-cols-12 gap-6">
<!-- Large 3D Viewport / Hero Section -->
<div class="col-span-12 lg:col-span-8 bg-surface-container rounded-xl overflow-hidden relative group">
<img class="w-full h-[450px] object-cover opacity-60 mix-blend-screen grayscale transition-transform duration-700 group-hover:scale-105" data-alt="Monochrome 3D wireframe architecture of a server room with glowing blue data streams and futuristic hardware silhouettes" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA1TkVSufW_98gtuJkikuthuUqvk018aLp6lL8ntzWa-SORZLVkFjnrVYeOXIHG-IcL7xuDqIT1jipsSDCTcgumg8u-npX_zSEE9IwZsDauSX37ocv-IC62Z39D9qN8eDF5SbFxXCfWynKhio5neWLy2ak146nMrrAB9s_nlewrQu8Yxx8ybeDano_GoG0vNWAj-RgpSFQKC9_ZkBNJbbsZzGtYgmupzQ5C8E-socUXTnIK1JNqVGCiD7peaOy59ZGyq_jtIh1lJBw"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface-container via-transparent to-transparent"></div>
<div class="absolute bottom-8 left-8 right-8">
<div class="flex items-end justify-between">
<div>
<h2 class="text-4xl font-bold tracking-tight mb-2">Terminal Architect v4</h2>
<p class="text-on-surface-variant max-w-md">Initialize high-performance neural nodes and orchestrate complex data flows within the obsidian core environment.</p>
</div>
<button class="bg-primary text-on-primary px-6 py-3 rounded-md font-bold text-sm tracking-wide active:scale-95 transition-transform">
                                INITIATE_CONSTRUCT
                            </button>
</div>
</div>
</div>
<!-- Secondary Metric Card -->
<div class="col-span-12 lg:col-span-4 bg-surface-container rounded-xl p-6 flex flex-col justify-between border border-outline-variant/5">
<div>
<div class="flex justify-between items-start mb-6">
<span class="material-symbols-outlined text-outline" data-icon="monitoring">monitoring</span>
<span class="text-[10px] bg-outline-variant/20 px-2 py-1 rounded text-outline">REAL_TIME</span>
</div>
<h3 class="text-sm font-bold uppercase tracking-widest text-outline mb-1">Architecture integrity</h3>
<div class="text-5xl font-black tracking-tighter mb-4">98.4<span class="text-lg text-outline ml-1">%</span></div>
</div>
<div class="space-y-4">
<div class="h-32 w-full flex items-end gap-1 px-1">
<div class="flex-1 bg-primary/20 h-1/2 rounded-t-sm"></div>
<div class="flex-1 bg-primary/20 h-2/3 rounded-t-sm"></div>
<div class="flex-1 bg-primary/40 h-3/4 rounded-t-sm"></div>
<div class="flex-1 bg-primary/60 h-1/2 rounded-t-sm"></div>
<div class="flex-1 bg-primary/30 h-4/5 rounded-t-sm"></div>
<div class="flex-1 bg-primary h-full rounded-t-sm"></div>
</div>
<p class="text-[11px] text-on-surface-variant leading-relaxed">No anomalies detected in the last 24 orbital cycles. Fabric stability remains optimal for expansion.</p>
</div>
</div>
<!-- Glossary Preview (SCREEN_5 Integration) -->
<div class="col-span-12 grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="bg-surface-container-low rounded-xl p-6 group hover:bg-surface-container transition-colors cursor-pointer border border-outline-variant/10">
<div class="flex items-center gap-3 mb-4">
<div class="w-10 h-10 rounded bg-surface-container-highest flex items-center justify-center">
<span class="material-symbols-outlined" data-icon="token">token</span>
</div>
<span class="font-mono text-xs text-outline">GLOS_01</span>
</div>
<h4 class="font-bold text-lg mb-2">Neural Linkage</h4>
<p class="text-sm text-on-surface-variant">The fundamental protocol for connecting disparate data nodes across the obsidian mesh network.</p>
</div>
<div class="bg-surface-container-low rounded-xl p-6 group hover:bg-surface-container transition-colors cursor-pointer border border-outline-variant/10">
<div class="flex items-center gap-3 mb-4">
<div class="w-10 h-10 rounded bg-surface-container-highest flex items-center justify-center">
<span class="material-symbols-outlined" data-icon="database">database</span>
</div>
<span class="font-mono text-xs text-outline">GLOS_02</span>
</div>
<h4 class="font-bold text-lg mb-2">Entropy Buffer</h4>
<p class="text-sm text-on-surface-variant">Prevents data decay by cycling temporal packets through a high-density graphite isolation chamber.</p>
</div>
<div class="bg-surface-container-low rounded-xl p-6 group hover:bg-surface-container transition-colors cursor-pointer border border-outline-variant/10">
<div class="flex items-center gap-3 mb-4">
<div class="w-10 h-10 rounded bg-surface-container-highest flex items-center justify-center">
<span class="material-symbols-outlined" data-icon="hub">hub</span>
</div>
<span class="font-mono text-xs text-outline">GLOS_03</span>
</div>
<h4 class="font-bold text-lg mb-2">Monolithic Mesh</h4>
<p class="text-sm text-on-surface-variant">A non-hierarchical structure where every element maintains its own milled identity and depth profile.</p>
</div>
</div>
<!-- Recent Construct History -->
<div class="col-span-12 lg:col-span-12 bg-surface-container rounded-xl overflow-hidden">
<div class="px-6 py-4 flex items-center justify-between border-b border-outline-variant/10">
<h3 class="font-bold text-sm uppercase tracking-widest">Active Constructs</h3>
<span class="material-symbols-outlined text-outline cursor-pointer" data-icon="filter_list">filter_list</span>
</div>
<div class="overflow-x-auto">
<table class="w-full text-left">
<thead class="bg-surface-container-low">
<tr>
<th class="px-6 py-3 text-[10px] font-bold uppercase tracking-widest text-outline">Construct ID</th>
<th class="px-6 py-3 text-[10px] font-bold uppercase tracking-widest text-outline">Protocol</th>
<th class="px-6 py-3 text-[10px] font-bold uppercase tracking-widest text-outline">Status</th>
<th class="px-6 py-3 text-[10px] font-bold uppercase tracking-widest text-outline">Resources</th>
<th class="px-6 py-3 text-[10px] font-bold uppercase tracking-widest text-outline text-right">Action</th>
</tr>
</thead>
<tbody class="divide-y divide-outline-variant/10">
<tr class="hover:bg-surface-container-high transition-colors">
<td class="px-6 py-4 font-mono text-sm">ARCH-7729-X</td>
<td class="px-6 py-4 text-sm">Graphite Obsidian</td>
<td class="px-6 py-4">
<span class="flex items-center gap-2 text-xs text-emerald-400">
<span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                                            STABILIZED
                                        </span>
</td>
<td class="px-6 py-4">
<div class="flex gap-1">
<span class="w-4 h-1 bg-primary rounded-full"></span>
<span class="w-4 h-1 bg-primary rounded-full"></span>
<span class="w-4 h-1 bg-outline-variant rounded-full"></span>
</div>
</td>
<td class="px-6 py-4 text-right">
<span class="material-symbols-outlined text-outline cursor-pointer hover:text-white" data-icon="open_in_new">open_in_new</span>
</td>
</tr>
<tr class="hover:bg-surface-container-high transition-colors">
<td class="px-6 py-4 font-mono text-sm">ARCH-8012-Y</td>
<td class="px-6 py-4 text-sm">Neural Sync</td>
<td class="px-6 py-4">
<span class="flex items-center gap-2 text-xs text-amber-400">
<span class="w-1.5 h-1.5 rounded-full bg-amber-400 animate-pulse"></span>
                                            SYNCING
                                        </span>
</td>
<td class="px-6 py-4">
<div class="flex gap-1">
<span class="w-4 h-1 bg-primary rounded-full"></span>
<span class="w-4 h-1 bg-primary rounded-full"></span>
<span class="w-4 h-1 bg-primary rounded-full"></span>
</div>
</td>
<td class="px-6 py-4 text-right">
<span class="material-symbols-outlined text-outline cursor-pointer hover:text-white" data-icon="open_in_new">open_in_new</span>
</td>
</tr>
<tr class="hover:bg-surface-container-high transition-colors">
<td class="px-6 py-4 font-mono text-sm">ARCH-2194-Z</td>
<td class="px-6 py-4 text-sm">Legacy Shell</td>
<td class="px-6 py-4">
<span class="flex items-center gap-2 text-xs text-outline">
<span class="w-1.5 h-1.5 rounded-full bg-outline"></span>
                                            DORMANT
                                        </span>
</td>
<td class="px-6 py-4">
<div class="flex gap-1">
<span class="w-4 h-1 bg-outline-variant rounded-full"></span>
<span class="w-4 h-1 bg-outline-variant rounded-full"></span>
<span class="w-4 h-1 bg-outline-variant rounded-full"></span>
</div>
</td>
<td class="px-6 py-4 text-right">
<span class="material-symbols-outlined text-outline cursor-pointer hover:text-white" data-icon="open_in_new">open_in_new</span>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</main>
<!-- BottomNavBar Shell (Mobile) -->
<nav class="fixed bottom-0 w-full z-50 md:hidden bg-[#1A1C1E] border-t border-[#474747]/15 shadow-[0_-4px_24px_-4px_rgba(0,0,0,0.12)] flex justify-around items-center px-4 h-16 w-full">
<a class="flex flex-col items-center justify-center text-white bg-[#1E2022] rounded-lg py-1 w-full active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="architecture">architecture</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Construct</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="history">history</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">History</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="star">star</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Favorites</span>
</a>
<a class="flex flex-col items-center justify-center text-[#C6C6CA] py-1 w-full hover:text-white active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="menu_book">menu_book</span>
<span class="font-inter text-[10px] uppercase font-bold tracking-widest">Glossary</span>
</a>
</nav>
<!-- FAB Shell -->
<button class="fixed bottom-24 right-8 w-14 h-14 bg-primary text-on-primary rounded-full shadow-2xl flex items-center justify-center md:bottom-8 group active:scale-90 transition-transform z-50">
<span class="material-symbols-outlined text-2xl" data-icon="add" style="font-variation-settings: 'FILL' 1;">add</span>
<span class="absolute right-full mr-4 bg-surface-container-highest px-3 py-1.5 rounded text-xs font-bold tracking-widest opacity-0 group-hover:opacity-100 transition-opacity pointer-events-none whitespace-nowrap border border-outline-variant/20">NEW_CONSTRUCT</span>
</button>
</body></html>

<!-- Product Specification & Flow Map -->
# Продукт: Terminal Architect (Graphite Edition)

## Описание
Интеллектуальная среда для инженеров и 3D-визуализаторов, позволяющая конвертировать промпты в структурированный JSON и обратно, управлять библиотекой лучших практик и обращаться к техническому словарю.

## Основные сценарии (Flows)
1. **Конвертация:** Ввод текста -> Перевод (опционально) -> Получение JSON -> Копирование/Экспорт.
2. **Обратная конвертация:** Ввод JSON -> Получение читаемого текста.
3. **Управление знаниями:** Просмотр избранных промптов -> Редактирование -> Поиск.
4. **Обучение и справочник:** Навигация по 3D глоссарию -> Изучение советов команды -> Добавление терминов в текущий промпт.

## Структура переходов
- **Нижняя панель (Mobile) / Боковое меню (Desktop):**
    - `CONSTRUCT` (Конвертер)
    - `HISTORY` (История)
    - `FAVORITES` (Избранное)
    - `GLOSSARY / REPO` (Глоссарий)
    - `SETTINGS / SYSTEM` (Настройки)

## Дизайн-код
- **Система:** Obsidian Core (Graphite Gray)
- **Цвета:** Глубокий графит, акценты белого и светло-серого.
- **Типографика:** Inter / JetBrains Mono.
