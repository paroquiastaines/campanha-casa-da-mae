<!--doctype html-->
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Campanha Casa da Mãe – Comunidade Nossa Senhora de Fátima</title>
  <meta name="description" content="Campanha Casa da Mãe – Reforma da parte exterior da Comunidade Nossa Senhora de Fátima. Participe com seu carnê ou PIX." />
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; }
    .gold { color:#B8860B }
  </style>
</head>
<body class="bg-gray-50 text-gray-900">
  <!-- Top Bar -->
  <header class="bg-gray-900 text-white text-sm">
    <div class="max-w-6xl mx-auto px-4 py-2 flex items-center justify-between gap-3">
      <div class="flex items-center gap-3">
        <img src="LOGO TIPO PARÓQUIA SANTA INÊS.png" alt="Paróquia Santa Inês" class="h-9 w-9 object-contain" />
        <p class="opacity-90 font-semibold">Campanha Casa da Mãe • Comunidade Nossa Senhora de Fátima</p>
      </div>
      <a href="#contribua" class="inline-flex items-center gap-2 px-3 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-600 transition">Quero contribuir</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="relative overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-br from-amber-50 to-white"></div>
    <div class="relative max-w-6xl mx-auto px-4 py-16 md:py-24 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-3xl md:text-5xl font-extrabold leading-tight">
          Campanha <span class="gold">Casa da Mãe</span>
        </h1>
        <p class="mt-4 text-lg md:text-xl text-gray-700">
          Reforma da parte exterior da Comunidade Nossa Senhora de Fátima.<br>
          Estamos melhorando a aparência exterior da nossa comunidade, renovando o espaço de fé para acolher melhor a todos. Conheça o projeto, veja a prestação de contas e participe com sua contribuição para essa obra na Casa da Mãe de Fátima.
        </p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#projeto" class="px-5 py-3 rounded-xl bg-gray-900 text-white hover:bg-black transition">Ver o projeto</a>
          <a href="#contribua" class="px-5 py-3 rounded-xl ring-1 ring-amber-500 text-amber-700 hover:bg-amber-50 transition">Como contribuir</a>
        </div>
        <div class="mt-6 text-sm text-gray-600">
          Endereço: Rua Narumi Nakayama, nº 701, Jardim Nossa Senhora de Fátima, Embu das Artes, SP
          <div class="mt-3">
            <a href="https://www.google.com/maps/@-23.6451801,-46.8188284,3a,75y,17.7h,92.35t/data=!3m7!1e1!3m5!1s-mO2knxajZljQtwNW8TNVA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-2.354190841221566%26panoid%3D-mO2knxajZljQtwNW8TNVA%26yaw%3D17.70397807261433!7i16384!8i8192?entry=ttu&g_ep=EgoyMDI1MDkxNy4wIKXMDSoASAFQAw%3D%3D" target="_blank" rel="noopener" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg ring-1 ring-gray-300 hover:bg-gray-100">
              Ver a igreja no Google Maps
            </a>
          </div>
        </div>
      </div>
      <div class="bg-white/80 backdrop-blur p-6 rounded-2xl shadow-sm ring-1 ring-gray-200">
        <h2 class="font-semibold text-lg">Meta da Campanha</h2>
        <div class="mt-3">
          <div class="flex items-baseline justify-between text-sm">
            <span>Arrecadado:</span>
            <span id="valArrecadado" class="font-semibold">R$ 0,00</span>
          </div>
          <div class="w-full h-3 mt-2 rounded-full bg-gray-200 overflow-hidden">
            <div id="barra" class="h-full bg-amber-500" style="width:0%"></div>
          </div>
          <div class="flex items-baseline justify-between text-sm mt-2">
            <span>Meta:</span>
            <span id="valMeta" class="font-semibold">R$ 0,00</span>
          </div>
          <p class="mt-3 text-sm text-gray-600" id="pctText">0% da meta alcançada</p>
        </div>
        <p class="mt-2 text-sm text-gray-600">Previsão de início: Outubro de 2025</p>
      </div>
    </div>
  </section>

  <!-- Projeto -->
  <section id="projeto" class="py-16">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold">O Projeto</h2>
      <p class="mt-4 text-gray-700 leading-relaxed">
        O projeto contempla a reforma da parte exterior da Comunidade Nossa Senhora de Fátima, incluindo pintura, renovação da fachada, melhorias estruturais e ambientação. A prestação de contas será publicada mensalmente neste site e nos avisos da missa.
      </p>

      <!-- Antes e Depois (somente 1 antes + 3 depois) -->
      <div class="mt-8">
        <h3 class="text-xl font-bold">Antes e Depois</h3>
        <div class="mt-4 grid lg:grid-cols-2 gap-4">
          <!-- Antes: fachada atual (azul) -->
          <div class="p-2 bg-white rounded-2xl ring-1 ring-gray-200">
            <img src="541324345_17920814385150257_7171119834513015353_n.jpg" alt="Antes – fachada atual" class="rounded-xl w-full object-cover" />
            <p class="text-center text-sm text-gray-600 mt-2">Antes – fachada atual</p>
          </div>

          <!-- Depois: renders do projeto (3 imagens) -->
          <div class="grid sm:grid-cols-2 gap-4">
            <div class="p-2 bg-white rounded-2xl ring-1 ring-gray-200 sm:col-span-2">
              <img src="541964442_17920814376150257_8278405201497224557_n.jpg" alt="Depois – lateral proposta" class="rounded-xl w-full object-cover" />
              <p class="text-center text-sm text-gray-600 mt-2">Depois – frente proposta</p>
            </div>
            <div class="p-2 bg-white rounded-2xl ring-1 ring-gray-200">
              <img src="541067320_17920814412150257_5394270482303569526_n.jpg" alt="Depois – hall/entrada proposta" class="rounded-xl w-full object-cover" />
              <p class="text-center text-sm text-gray-600 mt-2">Depois – hall/entrada proposta</p>
            </div>
            <div class="p-2 bg-white rounded-2xl ring-1 ring-gray-200">
              <img src="541911623_17920814406150257_8174984626225662675_n.jpg" alt="Depois – fachada proposta (frontal)" class="rounded-xl w-full object-cover" />
              <p class="text-center text-sm text-gray-600 mt-2">Depois – lateral proposta</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Vídeo da Campanha -->
  <section id="video" class="py-10">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold">Vídeo Explicativo Sobre a Campanha</h2>
      <p class="mt-2 text-gray-700">Assista ao vídeo onde nosso Padre Maciel, faz a apresentação do projeto Campanha Casa da Mãe e tira todas as dúvidas sobre como fazer a sua contribuição para a realização deste projeto.</p>

  <div class="mt-4 p-2 bg-black rounded-2xl ring-1 ring-gray-200">
    <video id="videoCampanha" class="w-full rounded-xl" controls playsinline poster="capa-video.jpg">
      <source src="video-campanha.mp4" type="video/mp4" />
      <source src="FDownloader.Net_AQNifLe-T2l9wchxzJj1lieaxRmJK75I4g3rnzIxzn7HSJIJJjVF1ExQHT-sgSVVvMeTLCEbnOe1VYLHohlJSEBl_720p_(HD) (1).mp4" type="video/mp4" />
      Seu navegador não suporta o elemento <code>video</code>.
    </video>
  </div>

  <!-- Como contribuir -->
  <section id="contribua" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold">Como Contribuir</h2>
      <div class="mt-8 grid md:grid-cols-2 gap-6">
        <!-- PIX -->
        <div class="p-6 rounded-2xl ring-1 ring-gray-200">
          <h3 class="text-xl font-bold mt-1">Contribua via PIX</h3>
          <p class="mt-2 text-gray-700">Escaneie o QR Code, copie a chave ou use o <em>copia e cola</em> abaixo.</p>
          <div class="mt-4 aspect-square w-full rounded-xl bg-white grid place-content-center overflow-hidden ring-1 ring-gray-200">
            <img src="baixados (1).png" alt="QR Code PIX" class="w-2/3 mx-auto" />
          </div>
          <div class="mt-4 space-y-3">
            <div>
              <label class="text-sm text-gray-600">Chave PIX (CNPJ):</label>
              <div class="mt-1 flex">
                <input id="pixKey" type="text" value="61378766009740" class="flex-1 px-3 py-2 rounded-l-lg ring-1 ring-gray-300 focus:outline-none" />
                <button id="btnCopyPix" class="px-3 py-2 rounded-r-lg bg-gray-900 text-white hover:bg-black">Copiar</button>
              </div>
            </div>
            <div>
              <label class="text-sm text-gray-600">PIX <em>copia e cola</em>:</label>
              <div class="mt-1 flex">
                <input id="pixPaste" type="text" value="00020126360014BR.GOV.BCB.PIX0114613787660097405204000053039865802BR5901N6001C62210517CAMPANHACASADAMAE63045019" class="flex-1 px-3 py-2 rounded-l-lg ring-1 ring-gray-300 focus:outline-none" />
                <button id="btnCopyPaste" class="px-3 py-2 rounded-r-lg bg-gray-900 text-white hover:bg-black">Copiar</button>
              </div>
              <p class="text-xs text-gray-500 mt-2">Favorecido: <span class="font-semibold">Paróquia Santa Inês</span></p>
            </div>
            <div class="grid sm:grid-cols-2 gap-2 pt-2">
              <a href="https://wa.me/5511957274039?text=Ol%C3%A1%2C%20gostaria%20de%20tirar%20uma%20d%C3%BAvida%20sobre%20a%20Campanha%20Casa%20da%20M%C3%A3e.%20" target="_blank" rel="noopener" class="inline-flex items-center justify-center gap-2 px-4 py-3 rounded-xl bg-green-600 text-white hover:bg-green-700">Tirar dúvidas pelo WhatsApp</a>
              <a href="https://wa.me/5511957274039?text=Ol%C3%A1%2C%20quero%20pegar%20meu%20carn%C3%AA%20da%20Campanha%20Casa%20da%20M%C3%A3e." target="_blank" rel="noopener" class="inline-flex items-center justify-center gap-2 px-4 py-3 rounded-xl bg-amber-500 text-white hover:bg-amber-600">Quero meu carnê</a>
            </div>
          </div>
        </div>
        <!-- Carnês -->
        <div class="p-6 rounded-2xl ring-1 ring-gray-200">
          <h3 class="text-xl font-bold mt-1">Carnês Mensais</h3>
          <p class="mt-2 text-gray-700">
            Os carnês têm valor fixo de <strong>R$ 50,00 por mês</strong>, durante <strong>10 meses</strong>. Ao final, sua contribuição totaliza <strong>R$ 500,00</strong> para a campanha.
          </p>
          <p class="mt-3 text-gray-700">
            • Não é boleto, não há data de vencimento.<br>
            • Pagamento via PIX, em dinheiro na secretaria ou no ofertório (entregue junto o talão do mês).<br>
            • Retire seu carnê na Secretaria da Igreja.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Prestação de contas -->
  <section id="prestacao" class="py-16">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold">Prestação de Contas</h2>
      <p class="mt-2 text-gray-700">Atualizado mensalmente. Abaixo, publicamos as <strong>entradas</strong> e <strong>saídas</strong> da Campanha Casa da Mãe.</p>
      <div class="mt-6 grid md:grid-cols-2 gap-6">
        <div class="p-6 bg-white rounded-2xl ring-1 ring-gray-200">
          <h3 class="font-semibold">Entradas</h3>
          <ul id="listaEntradas" class="mt-3 text-sm text-gray-700 space-y-1">
            <li>08/2025 – Carnês: R$ 3.520,00</li>
            <li>08/2025 – PIX: R$ 1.780,00</li>
            <li>08/2025 – Doações avulsas: R$ 650,00</li>
          </ul>
        </div>
        <div class="p-6 bg-white rounded-2xl ring-1 ring-gray-200">
          <h3 class="font-semibold">Saídas</h3>
          <ul id="listaSaidas" class="mt-3 text-sm text-gray-700 space-y-1">
            <li>Compra de telhas – R$ 2.900,00</li>
            <li>Materiais elétricos – R$ 1.200,00</li>
            <li>Pintura (mão de obra) – R$ 1.000,00</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-16">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-extrabold">Fale Conosco</h2>
      <p class="mt-2 text-gray-700">Secretaria paroquial: <a class="underline" href="tel:+5511957274039">(11) 95727-4039</a></p>
      <p class="text-sm text-gray-600 mt-2">Endereço da Paróquia: Rua Guiné, 51, Jardim São Luiz, Embu das Artes, SP</p>
      <p class="text-sm text-gray-600 mt-1">Endereço da Comunidade Nossa Senhora de Fátima: Rua Narumi Nakayama, nº 701, Jardim Nossa Senhora de Fátima, Embu das Artes, SP</p>
    </div>
  </section>

  <footer class="py-10 bg-gray-900 text-gray-300">
    <div class="max-w-6xl mx-auto px-4 text-sm flex flex-col md:flex-row items-center justify-between gap-3">
      <p>© <span id="ano"></span> Paróquia Santa Inês. Todos os direitos reservados.</p>
      <p>Página simples desenvolvida para a Campanha Casa da Mãe.</p>
    </div>
  </footer>

  <!-- Rodapé: redes sociais -->
  <div class="bg-gray-950 text-gray-200">
    <div class="max-w-6xl mx-auto px-4 py-6 flex items-center gap-6">
      <span class="text-sm">Siga a Paróquia:</span>
      <a href="https://www.facebook.com/share/17Do56LyoQ/" target="_blank" rel="noopener" class="inline-flex items-center gap-2 text-sm hover:underline">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-5 h-5 fill-current"><path d="M22 12.07C22 6.48 17.52 2 11.93 2S2 6.48 2 12.07c0 4.99 3.66 9.13 8.44 9.93v-7.03H7.9V12.07h2.54V9.86c0-2.5 1.49-3.88 3.77-3.88 1.09 0 2.24.2 2.24.2v2.46h-1.26c-1.24 0-1.62.77-1.62 1.56v1.87h2.76l-.44 2.9h-2.32V22c4.78-.8 8.44-4.94 8.44-9.93Z"/></svg>
        Facebook
      </a>
      <a href="https://www.instagram.com/santainesparoquia?igsh=cTRkY2Zwd3B5Yzh2" target="_blank" rel="noopener" class="inline-flex items-center gap-2 text-sm hover:underline">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-5 h-5 fill-current"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5Zm0 2a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3H7Zm5 3a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 2.2a2.8 2.8 0 1 0 0 5.6 2.8 2.8 0 0 0 0-5.6ZM18.5 6.8a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"/></svg>
        Instagram
      </a>
    </div>
  </div>

  <script>
    // ===== CONFIGURAÇÃO RÁPIDA =====
    const META = 150000.00;          // Meta total
    const ARRECADADO = 1000.00;        // Atualizar conforme arrecadação
    const PIX_CHAVE = '61378766009740'; // CNPJ
    const SHARE_MSG = 'Participe da Campanha Casa da Mãe – Reforma da Comunidade Nossa Senhora de Fátima! Saiba mais e contribua: ' + window.location.href;

    const barra = document.getElementById('barra');
    const valMeta = document.getElementById('valMeta');
    const valArrecadado = document.getElementById('valArrecadado');
    const pctText = document.getElementById('pctText');
    const pct = Math.min(100, Math.round((ARRECADADO / META) * 100));
    barra.style.width = pct + '%';
    valMeta.textContent = META.toLocaleString('pt-BR', { style:'currency', currency:'BRL' });
    valArrecadado.textContent = ARRECADADO.toLocaleString('pt-BR', { style:'currency', currency:'BRL' });
    pctText.textContent = pct + '% da meta alcançada';

    const inputPix = document.getElementById('pixKey');
    const btnCopy = document.getElementById('btnCopyPix');
    inputPix.value = PIX_CHAVE;
    btnCopy.addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(inputPix.value);
        btnCopy.textContent = 'Copiado!';
        setTimeout(()=> btnCopy.textContent = 'Copiar', 1500);
      } catch (e) {
        alert('Não foi possível copiar. Selecione e copie manualmente.');
      }
    });

    document.getElementById('ano').textContent = new Date().getFullYear();
  </script>

  <!-- Botão flutuante WhatsApp -->
  <a href="https://wa.me/5511957274039?text=Ol%C3%A1%2C%20gostaria%20de%20tirar%20uma%20d%C3%BAvida%20sobre%20a%20Campanha%20Casa%20da%20M%C3%A3e.%20" target="_blank" rel="noopener" class="fixed bottom-5 right-5 inline-flex items-center justify-center w-14 h-14 rounded-full bg-green-600 text-white shadow-lg hover:bg-green-700" aria-label="WhatsApp Secretaria">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-7 h-7 fill-current"><path d="M20.52 3.48A11.86 11.86 0 0 0 12.06 0C5.49 0 .17 5.32.17 11.89c0 2.09.55 4.12 1.6 5.92L0 24l6.36-1.66a11.86 11.86 0 0 0 5.7 1.45h.01c6.57 0 11.89-5.32 11.89-11.89a11.86 11.86 0 0 0-3.44-8.42ZM12.06 21.2h-.01a9.3 9.3 0 0 1-4.74-1.3l-.34-.2-3.77.99 1.01-3.68-.22-.38a9.3 9.3 0 1 1 8.07 4.57Zm5.4-6.94c-.3-.15-1.77-.87-2.05-.97-.27-.1-.47-.15-.68.15-.2.3-.78.97-.95 1.17-.17.2-.35.22-.65.07-.3-.15-1.26-.46-2.4-1.47-.89-.79-1.49-1.77-1.66-2.07-.17-.3-.02-.46.13-.61.13-.13.3-.35.44-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.02-.52-.07-.15-.68-1.64-.93-2.24-.24-.57-.5-.49-.68-.5l-.58-.01c-.2 0-.52.07-.79.37-.27.3-1.04 1.02-1.04 2.49 0 1.46 1.07 2.88 1.22 3.08.15.2 2.1 3.2 5.07 4.49.71.31 1.27.49 1.7.63.71.23 1.35.2 1.86.12.57-.08 1.77-.72 2.02-1.42.25-.7.25-1.3.17-1.42-.07-.12-.27-.2-.57-.35Z"/></svg>
  </a>

  <script>
    // ===== CONFIGURAÇÃO RÁPIDA =====
    const META = 150000.00;          // Meta total
    const ARRECADADO = 0.00;        // Atualizar conforme arrecadação
    const PIX_CHAVE = '61378766009740'; // CNPJ
    const PIX_PASTE = '00020126360014BR.GOV.BCB.PIX0114613787660097405204000053039865802BR5901N6001C62210517CAMPANHACASADAMAE63045019';
    const SHARE_MSG = 'Participe da Campanha Casa da Mãe – Reforma da Comunidade Nossa Senhora de Fátima! Saiba mais e contribua: ' + window.location.href;

    const barra = document.getElementById('barra');
    const valMeta = document.getElementById('valMeta');
    const valArrecadado = document.getElementById('valArrecadado');
    const pctText = document.getElementById('pctText');
    const pct = Math.min(100, Math.round((ARRECADADO / META) * 100));
    barra.style.width = pct + '%';
    valMeta.textContent = META.toLocaleString('pt-BR', { style:'currency', currency:'BRL' });
    valArrecadado.textContent = ARRECADADO.toLocaleString('pt-BR', { style:'currency', currency:'BRL' });
    pctText.textContent = pct + '% da meta alcançada';

    const inputPix = document.getElementById('pixKey');
    const btnCopy = document.getElementById('btnCopyPix');
    inputPix.value = PIX_CHAVE;
    btnCopy.addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(inputPix.value);
        btnCopy.textContent = 'Copiado!';
        setTimeout(()=> btnCopy.textContent = 'Copiar', 1500);
      } catch (e) {
        alert('Não foi possível copiar. Selecione e copie manualmente.');
      }
    });

    const inputPaste = document.getElementById('pixPaste');
    const btnCopyPaste = document.getElementById('btnCopyPaste');
    inputPaste.value = PIX_PASTE;
    btnCopyPaste.addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(inputPaste.value);
        btnCopyPaste.textContent = 'Copiado!';
        setTimeout(()=> btnCopyPaste.textContent = 'Copiar', 1500);
      } catch (e) {
        alert('Não foi possível copiar. Selecione e copie manualmente.');
      }
    });

    document.getElementById('ano').textContent = new Date().getFullYear();
  </script>
