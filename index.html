<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Formulários ATE – CEMIG</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap');

  :root {
    --cemig-blue: #00a651;      /* cor principal (azul escuro) */
    --cemig-light: #8cc63f;     /* azul claro / destaques */
    --accent: #e8a900;          /* amarelo / avisos */
    --border: #b0bec5;          /* bordas */
    --bg: #f4f6f9;              /* fundo da página */
    --bg-section: #ffffff;      /* fundo dos cards */
    --bg-header: #00a651;       /* fundo do cabeçalho */
    --text: #1a2332;            /* texto principal */
    --text-light: #546e7a;      /* texto secundário */
    --ok: #2e7d32;              /* verde (conforme) */
    --warn: #c62828;            /* vermelho (não conforme) */
    --row-alt: #eef2f7;         /* linhas alternadas tabela */
    --pending-bg: #fff8e1;      /* fundo campo pendente */
}

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'IBM Plex Sans', sans-serif;
    background: var(--bg);
    color: var(--text);
    font-size: 13px;
    line-height: 1.4;
  }

  .page-wrapper {
    max-width: 960px;
    margin: 24px auto;
    padding: 0 16px 60px;
  }

  /* ── HOME SCREEN ── */
  .home-screen { text-align: center; padding-top: 60px; }
  .home-logo {
    width: 120px; height: 120px;
    background: var(--cemig-blue);
    border-radius: 16px;
    display: inline-flex; align-items: center; justify-content: center;
    font-family: 'IBM Plex Mono', monospace;
    font-weight: 700; font-size: 28px; color: white;
    letter-spacing: -1px; margin-bottom: 24px;
    box-shadow: 0 8px 32px rgba(0,61,122,0.3);
  }
  .home-title { font-size: 22px; font-weight: 700; color: var(--cemig-blue); margin-bottom: 6px; }
  .home-subtitle { font-size: 14px; color: var(--text-light); margin-bottom: 40px; }

  .form-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 20px; max-width: 900px; margin: 0 auto; }
  .form-card {
    background: white;
    border: 2px solid #e0e6ed;
    border-radius: 12px;
    padding: 28px 24px;
    cursor: pointer;
    transition: all 0.2s;
    text-align: left;
    position: relative;
    overflow: hidden;
  }
  .form-card:hover {
    border-color: var(--cemig-light);
    box-shadow: 0 6px 24px rgba(0,102,204,0.15);
    transform: translateY(-2px);
  }
  .form-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 4px;
    background: var(--cemig-blue);
  }
  .form-card-icon {
    font-size: 32px; margin-bottom: 12px;
  }
  .form-card h3 { font-size: 15px; font-weight: 700; color: var(--cemig-blue); margin-bottom: 6px; }
  .form-card p { font-size: 12px; color: var(--text-light); line-height: 1.5; }

  /* ── HEADER ── */
  .form-header {
    background: var(--bg-header);
    color: white;
    padding: 20px 28px;
    border-radius: 8px 8px 0 0;
    display: flex;
    align-items: center;
    gap: 24px;
  }
  .cemig-logo {
    width: 72px; height: 72px;
    background: white; border-radius: 6px;
    display: flex; align-items: center; justify-content: center;
    font-family: 'IBM Plex Mono', monospace;
    font-weight: 700; font-size: 22px;
    color: var(--cemig-blue);
    letter-spacing: -1px; flex-shrink: 0;
  }
  .form-header h1 { font-size: 18px; font-weight: 700; letter-spacing: 0.3px; }
  .form-header h2 { font-size: 13px; font-weight: 400; opacity: 0.85; margin-top: 4px; }
  .form-header .sub { font-size: 12px; opacity: 0.7; margin-top: 6px; font-style: italic; }

  /* ── CARD ── */
  .card {
    background: var(--bg-section);
    border: 1px solid var(--border);
    border-top: none;
    padding: 20px 24px;
  }
  .card:last-of-type { border-radius: 0 0 8px 8px; }

  .section-title {
    font-size: 11px; font-weight: 700;
    text-transform: uppercase; letter-spacing: 1.2px;
    color: var(--cemig-blue);
    border-bottom: 2px solid var(--cemig-light);
    padding-bottom: 6px; margin-bottom: 16px;
  }

  /* ── GRID INPUTS ── */
  .grid { display: grid; gap: 12px; }
  .g2 { grid-template-columns: 1fr 1fr; }
  .g3 { grid-template-columns: 1fr 1fr 1fr; }
  .g4 { grid-template-columns: 1fr 1fr 1fr 1fr; }

  .field { display: flex; flex-direction: column; gap: 4px; }
  .field label { font-size: 11px; font-weight: 600; color: var(--text-light); text-transform: uppercase; letter-spacing: 0.5px; }
  .field input, .field select, .field textarea {
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 7px 10px;
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 13px; color: var(--text); background: white;
    transition: border-color 0.15s;
  }
  .field input:focus, .field select:focus, .field textarea:focus {
    outline: none;
    border-color: var(--cemig-light);
    box-shadow: 0 0 0 3px rgba(0,102,204,0.1);
  }
  .field textarea { resize: vertical; min-height: 72px; }

  /* ── TABLE ── */
  table { width: 100%; border-collapse: collapse; font-size: 12px; }
  thead tr { background: var(--cemig-blue); color: white; }
  thead th { padding: 8px 10px; text-align: left; font-weight: 600; font-size: 11px; letter-spacing: 0.5px; }
  tbody tr:nth-child(even) { background: var(--row-alt); }
  tbody tr:hover { background: #e3eaf5; }
  tbody td { padding: 7px 10px; border-bottom: 1px solid #dde3ec; vertical-align: top; }
  tbody td.item-num { font-family: 'IBM Plex Mono', monospace; font-weight: 600; color: var(--cemig-blue); width: 42px; }
  tbody td.item-qty { text-align: center; font-weight: 700; color: var(--cemig-blue); width: 50px; }
  tbody td.item-uni { text-align: center; color: var(--text-light); width: 42px; }

  .qty-input {
    width: 70px;
    border: 1px solid var(--border); border-radius: 4px;
    padding: 4px 6px; text-align: center;
    font-family: 'IBM Plex Mono', monospace; font-size: 12px;
    background: var(--pending-bg);
  }
  .qty-input:focus { outline: none; border-color: var(--cemig-light); }

  /* ── RADIO NA/C/NC ── */
  .na-c-nc { display: flex; gap: 0; }
  .na-c-nc label {
    display: flex; align-items: center; justify-content: center;
    width: 42px; height: 30px; font-size: 11px; font-weight: 600;
    cursor: pointer; border: 1px solid var(--border);
    background: white; color: var(--text-light);
    transition: all 0.15s;
  }
  .na-c-nc label:first-child { border-radius: 4px 0 0 4px; }
  .na-c-nc label:last-child { border-radius: 0 4px 4px 0; }
  .na-c-nc label:not(:first-child) { border-left: none; }
  .na-c-nc input { display: none; }
  .na-c-nc input:checked + span { font-weight: 700; }
  .na-c-nc input[value="NA"]:checked ~ span,
  .na-c-nc label:has(input[value="NA"]:checked) { background: #e0e0e0; color: #555; }
  .na-c-nc label:has(input[value="C"]:checked) { background: #c8e6c9; color: #1b5e20; }
  .na-c-nc label:has(input[value="NC"]:checked) { background: #ffcdd2; color: #b71c1c; }

  /* ── LAUDO ROW ── */
  .laudo-row {
    background: #f0f4ff;
    border-left: 3px solid var(--cemig-light);
    padding: 10px 14px; margin: 4px 0 8px;
    border-radius: 0 4px 4px 0;
  }
  .laudo-row .laudo-grid { display: flex; flex-wrap: wrap; gap: 10px; align-items: center; }
  .laudo-row label { font-size: 11px; font-weight: 600; color: var(--text-light); }
  .laudo-row input[type="text"] {
    border: 1px solid var(--border); border-radius: 3px;
    padding: 4px 8px; font-size: 12px;
    font-family: 'IBM Plex Mono', monospace;
    width: 130px; background: white;
  }
  .radio-group { display: flex; gap: 10px; align-items: center; }
  .radio-group label { display: flex; align-items: center; gap: 4px; font-size: 12px; font-weight: 500; cursor: pointer; color: var(--text); }
  .radio-group input[type="radio"] { accent-color: var(--cemig-light); }
  .fab-row { margin-top: 8px; display: flex; flex-wrap: wrap; gap: 8px; align-items: center; }
  .fab-row span { font-size: 11px; font-weight: 600; color: var(--text-light); text-transform: uppercase; }
  .checkbox-inline { display: flex; align-items: center; gap: 4px; font-size: 12px; cursor: pointer; }
  .checkbox-inline input { accent-color: var(--cemig-light); }

  /* ── LOCATION ── */
  .location-group { display: flex; gap: 16px; align-items: center; flex-wrap: wrap; }
  .location-group label { display: flex; align-items: center; gap: 6px; font-size: 13px; cursor: pointer; }
  .location-group input[type="radio"] { accent-color: var(--cemig-blue); width: 16px; height: 16px; }

  /* ── CHECKLIST ── */
  .checklist-item { display: flex; align-items: flex-start; gap: 10px; padding: 7px 0; border-bottom: 1px solid #eee; }
  .checklist-item:last-child { border-bottom: none; }
  .checklist-item input[type="checkbox"] { accent-color: var(--cemig-blue); margin-top: 2px; width: 16px; height: 16px; flex-shrink: 0; }
  .checklist-item label { font-size: 12px; cursor: pointer; line-height: 1.4; }

  /* ── BTN ── */
  .btn-bar {
    display: flex; justify-content: space-between; align-items: center;
    gap: 12px; padding: 16px 24px;
    background: white; border: 1px solid var(--border);
    border-top: 2px solid var(--cemig-blue);
    border-radius: 0 0 8px 8px;
    position: sticky; bottom: 0;
    flex-wrap: wrap;
    z-index: 100;
  }
  .btn-bar-left { display: flex; gap: 10px; }
  .btn-bar-right { display: flex; gap: 10px; flex-wrap: wrap; }
  .btn {
    padding: 10px 20px; border-radius: 5px;
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 13px; font-weight: 600;
    cursor: pointer; border: none; transition: all 0.15s;
    display: inline-flex; align-items: center; gap: 6px;
  }
  .btn-primary { background: var(--cemig-blue); color: white; }
  .btn-primary:hover { background: #002a57; }
  .btn-excel { background: #1d6f42; color: white; }
  .btn-excel:hover { background: #145a34; }
  .btn-pdf { background: var(--warn); color: white; }
  .btn-pdf:hover { background: #a31f1f; }
  .btn-back { background: transparent; color: var(--text-light); border: 1px solid var(--border); }
  .btn-back:hover { background: var(--bg); }
  .btn-reset { background: transparent; color: var(--text-light); border: 1px solid var(--border); }
  .btn-reset:hover { background: var(--bg); }

  .note-box {
    background: #fff8e1; border-left: 4px solid var(--accent);
    padding: 10px 14px; border-radius: 0 4px 4px 0;
    font-size: 12px; color: #5d4037; margin-bottom: 12px;
  }

  .hidden { display: none !important; }

  /* ── PRINT ── */
  @media print {
    body { background: white; font-size: 11px; }
    .page-wrapper { max-width: 100%; margin: 0; padding: 0; }
    .btn-bar, .home-screen { display: none !important; }
    .card { page-break-inside: avoid; }
    .form-header { background: #003d7a !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    thead tr { background: #003d7a !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .na-c-nc label:has(input[value="NA"]:checked) { background: #e0e0e0 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .na-c-nc label:has(input[value="C"]:checked) { background: #c8e6c9 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .na-c-nc label:has(input[value="NC"]:checked) { background: #ffcdd2 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    table { page-break-inside: auto; }
    tr { page-break-inside: avoid; }
  }

  @media (max-width: 600px) {
    .g2, .g3, .g4 { grid-template-columns: 1fr; }
    .form-cards { grid-template-columns: 1fr; }
    .btn-bar { flex-direction: column; }
    .btn-bar-left, .btn-bar-right { width: 100%; justify-content: center; }
  }
</style>
</head>
<body>
<div class="page-wrapper">

<!-- ═══════════════ HOME SCREEN ═══════════════ -->
<div id="home-screen" class="home-screen">
  <div class="home-logo">cemig</div>
  <div class="home-title">FORMULÁRIOS ATE</div>
  <div class="home-subtitle">Avaliação Técnica em Empreiteira – Selecione o formulário</div>
  <div class="form-cards">
    <div class="form-card" onclick="showForm('infra')">
      <div class="form-card-icon">🏢</div>
      <h3>Infraestrutura Administrativa</h3>
      <p>Avaliação das condições de infraestrutura administrativa da empreiteira: instalações, segurança, higiene e conforto.</p>
    </div>
    <div class="form-card" onclick="showForm('moto')">
      <div class="form-card-icon">🏍️</div>
      <h3>Equipes de Motociclistas</h3>
      <p>Inspeção de ferramental, EPIs e veículo das equipes de motociclistas (MO1: 1 instalador motociclista).</p>
    </div>
    <div class="form-card" onclick="showForm('es2')">
      <div class="form-card-icon">⚡</div>
      <h3>Multifuncional ES2</h3>
      <p>Equipe de serviços – 2 componentes (2 instaladores). Ferramentas, EPIs, veículo e Kit Antirreprova.</p>
    </div>
  </div>
</div>

<!-- ═══════════════ FORM: INFRAESTRUTURA ═══════════════ -->
<div id="form-infra" class="hidden">
  <div class="form-header">
    <div class="cemig-logo">cemig</div>
    <div>
      <h1>FORMULÁRIO PARA AVALIAÇÃO TÉCNICA EM EMPREITEIRA – ATE</h1>
      <h2>INFRAESTRUTURA ADMINISTRATIVA</h2>
    </div>
  </div>

  <!-- ENDEREÇO -->
  <div class="card">
    <div class="section-title">Endereço</div>
    <div class="grid g2" style="margin-bottom:10px;">
      <div class="field"><label>Av./Rua</label><input type="text" data-field="infra-endereco"></div>
      <div class="field"><label>Número</label><input type="text" data-field="infra-numero"></div>
    </div>
    <div class="grid g2">
      <div class="field"><label>Bairro</label><input type="text" data-field="infra-bairro"></div>
      <div class="field"><label>Cidade</label><input type="text" data-field="infra-cidade"></div>
    </div>
  </div>

  <!-- COMPONENTES DA EMPRESA -->
  <div class="card">
    <div class="section-title">Componentes da Empresa</div>
    <table>
      <thead><tr><th>Nome do Responsável</th><th>CPF</th><th>Função</th></tr></thead>
      <tbody>
        <tr>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="infra-resp-nome"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;font-family:'IBM Plex Mono',monospace;" placeholder="000.000.000-00" data-field="infra-resp-cpf"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="infra-resp-funcao"></td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- ITENS DE AVALIAÇÃO -->
  <div class="card">
    <div class="section-title">Itens de Avaliação</div>
    <p style="font-size:11px;color:var(--text-light);margin-bottom:10px;">N-A = Não Aplicável &nbsp;|&nbsp; C = Conforme &nbsp;|&nbsp; NC = Não Conforme</p>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:140px;">Avaliação</th></tr></thead>
      <tbody id="tb-infra-items"></tbody>
    </table>
  </div>

  <!-- NOTAS -->
  <div class="card">
    <div class="section-title">Notas</div>
    <div class="note-box">
      1 – N-A = Não aplicável / C = Conforme / NC = Não Conforme<br>
      2 – Considera-se como Base Operacional o local de início e término da jornada de trabalho das equipes.
    </div>
    <div class="field"><label>Observações</label><textarea data-field="infra-obs" placeholder="Registre aqui observações relevantes..."></textarea></div>
  </div>

  <!-- BOTÕES -->
  <div class="btn-bar">
    <div class="btn-bar-left">
      <button class="btn btn-back" onclick="goHome()">← Voltar</button>
      <button class="btn btn-reset" onclick="resetForm('infra')">Limpar</button>
    </div>
    <div class="btn-bar-right">
      <button class="btn btn-excel" onclick="exportExcel('infra')">📊 Exportar Excel</button>
      <button class="btn btn-pdf" onclick="exportPDF()">📄 Exportar PDF</button>
    </div>
  </div>
</div>

<!-- ═══════════════ FORM: MOTOCICLISTAS ═══════════════ -->
<div id="form-moto" class="hidden">
  <div class="form-header">
    <div class="cemig-logo">cemig</div>
    <div>
      <h1>FORMULÁRIO PARA AVALIAÇÃO TÉCNICA EM EMPREITEIRA – ATE</h1>
      <h2>EQUIPES DE MOTOCICLISTAS</h2>
      <div class="sub">Estrutura de pessoal MO1: 1 Instalador motociclista</div>
    </div>
  </div>

  <!-- AGENTES -->
  <div class="card">
    <div class="section-title">Agente(s) Executor(es) da Inspeção</div>
    <div class="grid g2" style="margin-bottom:10px;">
      <div class="field"><label>Agente 1</label><input type="text" data-field="moto-agente1"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="moto-mat1"></div>
    </div>
    <div class="grid g2" style="margin-bottom:10px;">
      <div class="field"><label>Agente 2</label><input type="text" data-field="moto-agente2"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="moto-mat2"></div>
    </div>
    <div class="grid g2">
      <div class="field"><label>Agente 3</label><input type="text" data-field="moto-agente3"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="moto-mat3"></div>
    </div>
  </div>

  <!-- LOCAL E DATA -->
  <div class="card">
    <div class="grid g2">
      <div class="field">
        <label>Local da Inspeção</label>
        <div class="location-group" style="margin-top:6px;">
          <label><input type="radio" name="moto-local" value="Betim" onchange="toggleOutro(this,'moto-outro-local')"> Betim</label>
          <label><input type="radio" name="moto-local" value="Sete Lagoas" onchange="toggleOutro(this,'moto-outro-local')"> Sete Lagoas</label>
          <label><input type="radio" name="moto-local" value="Outro" onchange="toggleOutro(this,'moto-outro-local')"> Outro:</label>
          <input type="text" id="moto-outro-local" class="hidden" placeholder="Especifique..." style="width:150px;border:1px solid #b0bec5;border-radius:4px;padding:4px 8px;font-size:12px;" data-field="moto-outro-local">
        </div>
      </div>
      <div class="field"><label>Data</label><input type="date" data-field="moto-data"></div>
    </div>
  </div>

  <!-- COMPONENTES DA EQUIPE -->
  <div class="card">
    <div class="section-title">Componentes da Equipe Apresentada</div>
    <table>
      <thead><tr><th>Nome</th><th>CPF</th><th>Cód. Crachá</th></tr></thead>
      <tbody>
        <tr>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="moto-nome1"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;font-family:'IBM Plex Mono',monospace;" placeholder="000.000.000-00" data-field="moto-cpf1"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="moto-cracha1"></td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- FERRAMENTAL -->
  <div class="card">
    <div class="section-title">Ferramental – MO1</div>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:45px;">Uni.</th><th style="width:50px;">MO1</th><th style="width:100px;">Qtd. Pendente</th></tr></thead>
      <tbody id="tb-moto-ferramentas"></tbody>
    </table>
  </div>

  <!-- EPIs -->
  <div class="card">
    <div class="section-title">EPIs</div>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:45px;">Uni.</th><th style="width:50px;">MO1</th><th style="width:100px;">Qtd. Pendente</th></tr></thead>
      <tbody id="tb-moto-epis"></tbody>
    </table>
  </div>

  <!-- NOTAS MOTO -->
  <div class="card">
    <div class="section-title">Notas</div>
    <div class="note-box">
      1 – Itens com (*) exigidos na quantidade de 1 por Base Operacional, podendo ser compartilhado entre equipes.<br>
      2 – Itens com (**) exigidos para cada equipe que realizar serviços em que os equipamentos são necessários.<br>
      3 – Todos EPIs e EPCs devem possuir CA.<br>
      4 – Ferramentas, EPIs e EPCs devem atender especificações e desenhos atualizados da CONTRATANTE.
    </div>
    <div class="field"><label>Observações das Ferramentas, EPIs e EPCs</label><textarea data-field="moto-obs-ferr" placeholder="Registre aqui observações..."></textarea></div>
  </div>

  <!-- VEÍCULO MOTO -->
  <div class="card">
    <div class="section-title">Veículo</div>
    <div class="grid g4" style="margin-bottom:14px;">
      <div class="field"><label>Placa</label><input type="text" data-field="moto-placa"></div>
      <div class="field"><label>Modelo</label><input type="text" data-field="moto-modelo"></div>
      <div class="field"><label>Marca</label><input type="text" data-field="moto-marca"></div>
      <div class="field"><label>Ano de Fabricação</label><input type="text" data-field="moto-ano"></div>
    </div>

    <div class="section-title" style="margin-top:12px;">Check-list de Verificação</div>
    <p style="font-size:11px;color:var(--text-light);margin-bottom:10px;">Marque apenas se estiver conforme.</p>
    <div id="checklist-moto-veiculo"></div>

    <div class="field" style="margin-top:12px;"><label>Observações do Veículo</label><textarea data-field="moto-obs-veic" placeholder="Registre aqui observações do veículo..."></textarea></div>
  </div>

  <!-- BOTÕES MOTO -->
  <div class="btn-bar">
    <div class="btn-bar-left">
      <button class="btn btn-back" onclick="goHome()">← Voltar</button>
      <button class="btn btn-reset" onclick="resetForm('moto')">Limpar</button>
    </div>
    <div class="btn-bar-right">
      <button class="btn btn-excel" onclick="exportExcel('moto')">📊 Exportar Excel</button>
      <button class="btn btn-pdf" onclick="exportPDF()">📄 Exportar PDF</button>
    </div>
  </div>
</div>

<!-- ═══════════════ FORM: MULTIFUNCIONAL ES2 ═══════════════ -->
<div id="form-es2" class="hidden">
  <div class="form-header">
    <div class="cemig-logo">cemig</div>
    <div>
      <h1>FORMULÁRIO PARA AVALIAÇÃO TÉCNICA EM EMPREITEIRA – ATE</h1>
      <h2>EQUIPES DE MULTIFUNCIONAL</h2>
      <div class="sub">Estrutura de pessoal ES2: Equipe de serviços – 2 componentes (2 instaladores)</div>
    </div>
  </div>

  <!-- AGENTES ES2 -->
  <div class="card">
    <div class="section-title">Agente(s) Executor(es) da Inspeção</div>
    <div class="grid g2" style="margin-bottom:10px;">
      <div class="field"><label>Agente 1</label><input type="text" data-field="es2-agente1"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="es2-mat1"></div>
    </div>
    <div class="grid g2" style="margin-bottom:10px;">
      <div class="field"><label>Agente 2</label><input type="text" data-field="es2-agente2"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="es2-mat2"></div>
    </div>
    <div class="grid g2">
      <div class="field"><label>Agente 3</label><input type="text" data-field="es2-agente3"></div>
      <div class="field"><label>Matrícula</label><input type="text" data-field="es2-mat3"></div>
    </div>
  </div>

  <!-- LOCAL E DATA ES2 -->
  <div class="card">
    <div class="grid g2">
      <div class="field">
        <label>Local da Inspeção</label>
        <div class="location-group" style="margin-top:6px;">
          <label><input type="radio" name="es2-local" value="Betim" onchange="toggleOutro(this,'es2-outro-local')"> Betim</label>
          <label><input type="radio" name="es2-local" value="Sete Lagoas" onchange="toggleOutro(this,'es2-outro-local')"> Sete Lagoas</label>
          <label><input type="radio" name="es2-local" value="Outro" onchange="toggleOutro(this,'es2-outro-local')"> Outro:</label>
          <input type="text" id="es2-outro-local" class="hidden" placeholder="Especifique..." style="width:150px;border:1px solid #b0bec5;border-radius:4px;padding:4px 8px;font-size:12px;" data-field="es2-outro-local">
        </div>
      </div>
      <div class="field"><label>Data</label><input type="date" data-field="es2-data"></div>
    </div>
  </div>

  <!-- COMPONENTES EQUIPE ES2 -->
  <div class="card">
    <div class="section-title">Componentes da Equipe Apresentada</div>
    <table>
      <thead><tr><th>Nome</th><th>CPF</th><th>Função</th><th>Cód. Crachá</th></tr></thead>
      <tbody>
        <tr>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="es2-nome1"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;font-family:'IBM Plex Mono',monospace;" placeholder="000.000.000-00" data-field="es2-cpf1"></td>
          <td>Instalador</td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="es2-cracha1"></td>
        </tr>
        <tr>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="es2-nome2"></td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;font-family:'IBM Plex Mono',monospace;" placeholder="000.000.000-00" data-field="es2-cpf2"></td>
          <td>Instalador</td>
          <td><input type="text" style="width:100%;border:1px solid #ddd;padding:4px 6px;border-radius:3px;" data-field="es2-cracha2"></td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- FERRAMENTAS ES2 -->
  <div class="card">
    <div class="section-title">Ferramentas e Equipamentos – ES2</div>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:45px;">Uni.</th><th style="width:50px;">ES2</th><th style="width:100px;">Qtd. Pendente</th></tr></thead>
      <tbody id="tb-es2-ferramentas"></tbody>
    </table>
  </div>

  <!-- EPIs ES2 -->
  <div class="card">
    <div class="section-title">EPIs – Equipamentos de Proteção Individual</div>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:45px;">Uni.</th><th style="width:50px;">ES2</th><th style="width:100px;">Qtd. Pendente</th></tr></thead>
      <tbody id="tb-es2-epis"></tbody>
    </table>
  </div>

  <!-- NOTAS ES2 -->
  <div class="card">
    <div class="section-title">Notas</div>
    <div class="note-box">
      1 – Itens com (*) exigidos na quantidade de 1 por Base Operativa, podendo ser compartilhado entre equipes.<br>
      2 – Itens com (**) exigidos para cada equipe que realizar serviços em que os equipamentos são necessários.<br>
      3 – Conjunto cinto paraquedista: cinto + linha de vida + trava-queda + talabarte + sacola.<br>
      4 – Todos EPIs e EPCs devem possuir CA.<br>
      5 – Ferramentas, EPIs e EPCs devem atender especificações e desenhos atualizados da CONTRATANTE.
    </div>
    <div class="field"><label>Observações das Ferramentas, EPIs e EPCs</label><textarea data-field="es2-obs-ferr" placeholder="Registre aqui observações..."></textarea></div>
  </div>

  <!-- VEÍCULO ES2 -->
  <div class="card">
    <div class="section-title">Veículo</div>
    <div class="grid g4" style="margin-bottom:14px;">
      <div class="field"><label>Placa</label><input type="text" data-field="es2-placa"></div>
      <div class="field"><label>Modelo do Veículo</label><input type="text" data-field="es2-modelo"></div>
      <div class="field"><label>Marca do Veículo</label><input type="text" data-field="es2-marca-veic"></div>
      <div class="field"><label>Ano de Fabricação</label><input type="text" data-field="es2-ano"></div>
    </div>
    <div class="grid g2" style="margin-bottom:14px;">
      <div class="field"><label>Nome do Motorista</label><input type="text" data-field="es2-motorista"></div>
      <div class="field"><label>CPF do Motorista</label><input type="text" placeholder="000.000.000-00" data-field="es2-cpf-mot"></div>
    </div>
    <div class="grid g4" style="margin-bottom:14px;">
      <div class="field">
        <label>Tipo de Equipamento</label>
        <div style="display:flex;gap:16px;margin-top:6px;">
          <label class="checkbox-inline"><input type="radio" name="es2-tipo-equip" value="Escada Giratória"> Escada Giratória</label>
          <label class="checkbox-inline"><input type="radio" name="es2-tipo-equip" value="Cesta Aérea"> Cesta Aérea</label>
        </div>
      </div>
      <div class="field"><label>Marca do Equipamento</label><input type="text" data-field="es2-marca-equip"></div>
      <div class="field"><label>Modelo do Equipamento</label><input type="text" data-field="es2-modelo-equip"></div>
      <div class="field"><label>Ano Fab. Equipamento</label><input type="text" data-field="es2-ano-equip"></div>
    </div>

    <div class="section-title" style="margin-top:12px;">Check-list de Verificação do Veículo</div>
    <p style="font-size:11px;color:var(--text-light);margin-bottom:10px;">Marque apenas se estiver conforme.</p>
    <div class="grid g2">
      <div>
        <strong style="font-size:11px;color:var(--cemig-blue);text-transform:uppercase;">Geral</strong>
        <div id="checklist-es2-veiculo"></div>
      </div>
      <div>
        <strong style="font-size:11px;color:var(--cemig-blue);text-transform:uppercase;">Equipamento (Escada / Cesta)</strong>
        <div id="checklist-es2-escada"></div>
      </div>
    </div>

    <div class="field" style="margin-top:12px;"><label>Observações do Veículo</label><textarea data-field="es2-obs-veic" placeholder="Registre aqui observações do veículo..."></textarea></div>
  </div>

  <!-- KIT ANTIRREPROVA -->
  <div class="card">
    <div class="section-title">Kit Antirreprova – Relação de Ferramentas e Materiais</div>
    <table>
      <thead><tr><th style="width:42px;">Item</th><th>Descrição</th><th style="width:45px;">Uni.</th><th style="width:50px;">ES2</th><th style="width:100px;">Qtd. Pendente</th></tr></thead>
      <tbody id="tb-es2-kit"></tbody>
    </table>
    <div class="field" style="margin-top:14px;"><label>Observações do Kit Antirreprova</label><textarea data-field="es2-obs-kit" placeholder="Registre aqui observações..."></textarea></div>
  </div>

  <!-- BOTÕES ES2 -->
  <div class="btn-bar">
    <div class="btn-bar-left">
      <button class="btn btn-back" onclick="goHome()">← Voltar</button>
      <button class="btn btn-reset" onclick="resetForm('es2')">Limpar</button>
    </div>
    <div class="btn-bar-right">
      <button class="btn btn-excel" onclick="exportExcel('es2')">📊 Exportar Excel</button>
      <button class="btn btn-pdf" onclick="exportPDF()">📄 Exportar PDF</button>
    </div>
  </div>
</div>

</div><!-- /page-wrapper -->

<script>
// ════════════════════════════════════════════════════════
// DATA - INFRAESTRUTURA
// ════════════════════════════════════════════════════════
const infraItems = [
  {num:1, desc:"Equipamento de refrigeração em bom estado, para guarda e conservação de alimentos."},
  {num:2, desc:"Água potável, filtrada, para os trabalhadores por meio de bebedouros ou equipamento similar."},
  {num:3, desc:"Produtos inflamáveis e químicos armazenados adequadamente em local apropriado."},
  {num:4, desc:"Reservatório de água com capacidade aproximada de 60 litros diários por trabalhador. O reservatório ou bebedouro é limpo periodicamente."},
  {num:5, desc:"Aparelhos e sistema de ar condicionado inspecionados e limpos periodicamente."},
  {num:6, desc:"Existência e implantação do PSCIP – processo de segurança contra incêndio e pânico. A instalação possui o projeto de combate a incêndio e o AVCB atualizados."},
  {num:7, desc:"Existência de equipamentos de proteção contra incêndio onde aplicável (extintores, hidrantes, sprinklers, etc.)."},
  {num:8, desc:"Pisos do local de trabalho livres de depressões ou saliências que prejudiquem a circulação de pessoas ou a movimentação de materiais."},
  {num:9, desc:"Emprego de materiais antiderrapantes e corrimãos onde houver perigo de escorregamento nos pisos, escadas, rampas, corredores e passagens dos locais de trabalho."},
  {num:10, desc:"Materiais armazenados de forma a evitar a obstrução de portas, equipamentos contra incêndio e saídas de emergência."},
  {num:11, desc:"Vias de circulação de pessoas e máquinas sinalizadas e pré-definidas em locais com alto potencial de risco."},
  {num:12, desc:"Existência de sinalização de segurança e de emergência."},
  {num:13, desc:"Prateleiras, estantes, escaninhos e armações robustas e adequadas ao tipo de material armazenado."},
  {num:14, desc:"Local destinado a refeição fora do local de trabalho, limpo, arejado, com boa iluminação, piso lavável, com mesas e assentos em bom estado de conservação, e lavatórios e pias próximos ao local."},
  {num:15, desc:"Estufa, fogão ou similar para aquecimento de refeição, sendo proibida a utilização de álcool para este fim."},
  {num:16, desc:"Iluminação adequada ao ambiente."},
  {num:17, desc:"Conforto térmico adequado ao ambiente."},
  {num:18, desc:"Existência de guarda-corpo nos andares acima do solo. Tais como: terraços, balcões, compartimentos para garagens, etc."},
  {num:19, desc:"Os banheiros e vestiários são em número suficiente para atender os empregados."},
  {num:20, desc:"Resíduos industriais devidamente separados, em locais disponíveis para coleta."},
  {num:21, desc:"As instalações elétricas estão adequadamente protegidas. (Caixas com tampa, fiação dentro de eletrodutos, conexões isoladas, bebedouros e chuveiros aterrados)."},
  {num:22, desc:"Pia exclusiva para lavar os alimentos e utensílios."},
  {num:23, desc:"Os botijões de GLP estão instalados fora do ambiente de utilização, em área permanentemente ventilada e coberta. Válvula e mangueira aprovados pelo INMETRO e dentro da validade."},
  {num:24, desc:"As instalações sanitárias possuem paredes e piso impermeável, lavável, o piso inclinado para ralos de escoamento com sifões e não apresentam ressaltos/saliências e portas individuais por sanitário."},
  {num:25, desc:"A instalação sanitária possui lavatório, vaso sanitário com assento e caixa de descarga ou válvula automática, na proporção de 1 conjunto para cada grupo de 20 trabalhadores."},
  {num:26, desc:"Possui local para armazenamento de alimentos, separado dos produtos de limpeza."},
  {num:27, desc:"O chuveiro possui água quente e está na proporção de 01 para cada grupo de 10 trabalhadores."},
  {num:28, desc:"A cobertura ou laje protege contra chuva e a instalação não está situada em subsolo ou porões."},
  {num:29, desc:"Equipe multidisciplinar indicada, espaços confinados reconhecidos, identificados, sinalizados e com registros atualizados."},
  {num:30, desc:"Manter o ambiente livre de focos de reprodução de mosquitos."},
  {num:31, desc:"Os equipamentos de proteção contra incêndio estão selados, sinalizados e com a inspeção em dia."},
  {num:32, desc:"O estabelecimento possui alvará de licença e funcionamento para as atividades desenvolvidas."},
  {num:33, desc:"Cadeira com altura ajustável, rodízios, borda frontal arredondada, encosto com forma levemente adaptada ao corpo para proteção da região lombar, pouca ou nenhuma conformação no assento."},
  {num:34, desc:"Mapa de risco em local visível e atualizado."},
  {num:35, desc:"Mesa sem quinas vivas e sem tampa de vidros."},
  {num:36, desc:"Monitor e mesa atendem as condições antropométricas dos trabalhadores."},
  {num:39, desc:"Existência de vestiário com armários individuais, bom estado de conservação e com aberturas para ventilação ou portas teladas."},
  {num:40, desc:"Materiais e equipamentos armazenados adequadamente."},
  {num:41, desc:"Canteiro de obra/estabelecimento organizado, limpo e desimpedido, notadamente nas vias de circulação, passagens e escadarias."},
  {num:42, desc:"O local para refeições possui nº de assentos e mesas com tampos lisos e laváveis, suficientes para atender os trabalhadores."},
  {num:43, desc:"Layout adequado ao material armazenado."},
  {num:44, desc:"Local apropriado para armazenamento e destinação de resíduos."},
  {num:45, desc:"Parte não pavimentada da instalação capinada e limpa."},
  {num:46, desc:"Banheiros e instalações sanitárias higienizados, com água, sabão e papel toalha e higiênico disponíveis."},
  {num:47, desc:"Possui recipiente com tampa na cozinha e banheiro para coleta de lixo. Os resíduos são retirados e armazenados em local adequado periodicamente."},
  {num:48, desc:"A instalação sanitária possui papel higiênico e o lavatório possui material para a limpeza, enxugo ou secagem das mãos, proibindo-se o uso de toalhas coletivas."},
  {num:49, desc:"Produto químico possui FISPQ?"},
  {num:50, desc:"A instalação está livre de insetos e roedores, não necessitando de dedetização."},
];

// ════════════════════════════════════════════════════════
// DATA - MOTOCICLISTAS
// ════════════════════════════════════════════════════════
const motoFerramentas = [
  {num:1, desc:"Alicate profissional com cabo isolado", uni:"Pç", qty:1},
  {num:2, desc:"Alicate de corte diagonal com cabo isolado", uni:"Pç", qty:1},
  {num:3, desc:"Analisador de Desvio de Registro (**)", uni:"Pç", qty:1, laudo:1, fabs:[], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","Conserve","Engelmig"]},
  {num:4, desc:"Bastão de manobra ou vara telescópica com cabeçote universal com no mínimo 6 peças extensíveis e sacola para acondicionar", uni:"Pç", qty:1, laudo:1, fabs:["Montrel"]},
  {num:6, desc:"Canivete, lâmina tipo navalha", uni:"Pç", qty:1},
  {num:7, desc:"Chave canhão de 3/8\" isolada (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:8, desc:"Chave canhão de 7/16\" isolada (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:9, desc:"Chave de fenda isolada 6,5 x 150mm (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:10, desc:"Chave de fenda isolada 3 x 100mm (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:11, desc:"Chave de fenda isolada 5,5 x 150mm (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:12, desc:"Chave inglesa 200mm isolada (isolamento de cabo e extensão)", uni:"Pç", qty:1},
  {num:15, desc:"Conjunto chave allen em mm de 8; 6; 5; 4; 3; 2,5 e 2", uni:"Cj", qty:1},
  {num:16, desc:"Conjunto chave allen em polegadas de 1/4; 7/32; 3/16; 5/32; 9/64; 1/8; 7/64; 3/32 e 5/64", uni:"Cj", qty:1},
  {num:18, desc:"Crachá de identificação com nome e número de registro do empregado", uni:"Pç", qty:1},
  {num:21, desc:"Dispositivo de corte de ramal", uni:"Pç", qty:1},
  {num:23, desc:"Equipamento de comunicação de dados e voz conforme especificação da Contratante (incluindo câmera e GPS)", uni:"Pç", qty:1},
  {num:24, desc:"Inflador ou testador de luvas de borracha (*)", uni:"Pç", qty:1},
  {num:25, desc:"Impressora Térmica Portátil", uni:"Pç", qty:1, laudo:1, fabs:["ZEBRA RW420","ZEBRA ZQ520","ZEBRA ZQ521","BIXOLON XM7-40"]},
  {num:26, desc:"Lanterna para capacete ou manual", uni:"Pç", qty:1},
  {num:28, desc:"Volt-amperímetro alicate classe IV", uni:"Pç", qty:1, laudo:1, labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","Conserve","Engelmig"]},
];

const motoEpis = [
  {num:29, desc:"Bolsa de Lona para acondicionar capacete, luva de vaqueta e óculos", uni:"Un", qty:1},
  {num:30, desc:"Bolsa para acondicionar luva isolante", uni:"Un", qty:1},
  {num:31, desc:"Bota de Segurança Cano Longo (BOTA DE CAMPANHA)", uni:"Pr", qty:2},
  {num:32, desc:"Bota impermeável – cano longo – de borracha", uni:"Pr", qty:1},
  {num:33, desc:"Calça de Uniforme com Tecido Resistente à Chama – condutibilidade, inflamabilidade e influências eletromagnéticas, com logotipo empresa", uni:"Un", qty:3},
  {num:34, desc:"Camisa de Uniforme manga longa com Tecido Resistente à Chama – condutibilidade, inflamabilidade e influências eletromagnéticas com logotipo empresa", uni:"Un", qty:3},
  {num:35, desc:"Capa impermeável para chuva (calça e blusa separadas, com faixa reflexiva)", uni:"Un", qty:1},
  {num:36, desc:"Capacete de segurança, classe B, com aba frontal e jugular", uni:"Un", qty:1},
  {num:38, desc:"Colete de proteção para motociclista (com faixa reflexiva)", uni:"Un", qty:1},
  {num:39, desc:"Jaqueta de Uniforme com Tecido Resistente à Chama – condutibilidade, inflamabilidade e influências eletromagnéticas com logotipo empresa", uni:"Un", qty:1},
  {num:40, desc:"Joelheira, cotoveleira de proteção e Luvas de motociclista (equipamentos de proteção do motociclista). A luva deve ter fechamento no punho.", uni:"Cj", qty:1},
  {num:41, desc:"Luva de borracha isolante 0,5kV (classe 00)", uni:"Pr", qty:1, laudo:1, fabs:["Salisbury","North Safety","GB","Orion"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","Conserve","Engelmig"]},
  {num:43, desc:"Luva de couro para proteção da luva de borracha isolante", uni:"Pr", qty:1},
  {num:44, desc:"Luva de vaqueta para trabalho leve", uni:"Pr", qty:1},
  {num:45, desc:"Óculos de segurança incolor para proteção de partículas multidirecionais", uni:"Un", qty:1},
  {num:46, desc:"Óculos de segurança lente escura tonalidade 2 ou 3 para proteção de partículas multidirecionais", uni:"Un", qty:1},
  {num:47, desc:"Protetor solar FPS 30", uni:"Un", qty:1},
];

const motoChecklistVeiculo = [
  "Veículo próprio / Veículo locado",
  "Documentação atualizada",
  "Controle de manutenção (físico ou digital)",
  "Câmera veicular",
  "Rastreador veicular",
  "Antena dupla",
  "Baú de 90L",
  "Baú com fixação de varas internas",
  "Baú com faixas reflexivas",
  "Baú com identificação 'a serviço da CEMIG'",
  "Mata cachorro (aço tubular em peça única)",
  "Pneu em condições de uso (s/ reformar)",
  "Funilaria em boas condições",
  "Todas as setas em correto funcionamento",
  "Farol baixo e alto em correto funcionamento",
  "Buzina em correto funcionamento",
  "Capacete em bom estado de conservação",
  "Capacete com faixa reflexiva",
  "Viseira escamoteável ou de abertura total",
  "Viseira transparente em condições de uso",
  "Manete/manopla em condições de uso",
];

// ════════════════════════════════════════════════════════
// DATA - ES2 (reusing from original)
// ════════════════════════════════════════════════════════
const es2Ferramentas = [
  {num:1, desc:"Alicate bomba d'água com cabo isolado", uni:"Pç", qty:2},
  {num:2, desc:"Alicate de compressão hidráulico (com corda e gancho)", uni:"Pç", qty:1, laudo:1, fabs:["Hidramaq","Solução","Hubbel","Izumi","Grenlee"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:3, desc:"Alicate de compressão mecânica (com corda e gancho) (OPCIONAL se substituído por alicate de compressão hidráulico)", uni:"Pç", qty:1, laudo:1, fabs:["Hidramaq","Tec-Ali","Hubbel","Solução"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:4, desc:"Alicate profissional com cabo isolado", uni:"Pç", qty:2},
  {num:5, desc:"Analisador de Desvio de Registros (**)", uni:"Pç", qty:1, laudo:1, fabs:["Montrel"]},
  {num:6, desc:"Arco de serra com lâmina", uni:"Pç", qty:1},
  {num:7, desc:"Bandeirolas para sinalização e suporte para fixação", uni:"Pç", qty:10},
  {num:8, desc:"Bandeja para armazenamento de equipamento com vazamento de óleo (*)", uni:"Pç", qty:1},
  {num:9, desc:"Bastão de manobra ou vara telescópica com cabeçote universal com no mínimo 6 partes extensíveis e sacola para acondicionar", uni:"Pç", qty:1, laudo:1, fabs:["Terex","Solução","Hastings"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:10, desc:"Bastão pega-tudo cabeçote alumínio 32mm x 2580mm e sacola para acondicionar", uni:"Pç", qty:1, laudo:1, fabs:["Terex"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:11, desc:"Binóculo", uni:"Pç", qty:1},
  {num:12, desc:"Bolsa de lona porta fusível", uni:"Pç", qty:1},
  {num:13, desc:"Cabeçote para grampo de aterramento", uni:"Pç", qty:1},
  {num:14, desc:"Cabo isolado 1x53mm² (1x1/0) com garra para by-pass – 4 metros", uni:"Un", qty:1},
  {num:15, desc:"Calibrador portátil para ensaio em medidor kWh eletromecânico e eletrônico (**)", uni:"Pç", qty:1},
  {num:16, desc:"Calço emborrachado para veículo (veículos com estabilizador deverão também conter calços poliméricos para as sapatas)", uni:"Pç", qty:2},
  {num:17, desc:"Câmera com sensor de fadiga que registre os eventos, emita alerta sonoro e visual", uni:"Pç", qty:1},
  {num:19, desc:"Câmera veicular conforme especificação da IT-RD-00022", uni:"Pç", qty:1},
  {num:20, desc:"Canivete", uni:"Pç", qty:2},
  {num:25, desc:"Catraca para 750 daN", uni:"Pç", qty:1},
  {num:28, desc:"Chave canhão de 3/8\" isolada (isolamento de cabo e extensão) – isolamento >= 1kV", uni:"Pç", qty:2},
  {num:29, desc:"Chave canhão de 7/16\" isolada (isolamento de cabo e extensão) – isolamento >= 1kV", uni:"Pç", qty:2},
  {num:30, desc:"Chave com catraca com cabo isolado para aplicação de conector perfuração", uni:"Pç", qty:2},
  {num:31, desc:"Chave de fenda isolada (isolamento de cabo e extensão) 6,5 x 150mm", uni:"Pç", qty:2},
  {num:32, desc:"Chave de fenda isolada (isolamento de cabo e extensão) 3 x 100mm", uni:"Pç", qty:2},
  {num:33, desc:"Chave de fenda isolada (isolamento de cabo e extensão) 5,5 x 150mm", uni:"Pç", qty:2},
  {num:34, desc:"Chave Phillips isolada (isolamento de cabo e extensão) 6 x 150mm", uni:"Pç", qty:2},
  {num:35, desc:"Chave Phillips isolada (isolamento de cabo e extensão) 3 x 100mm (**)", uni:"Pç", qty:1},
  {num:36, desc:"Chave inglesa 200mm isolada", uni:"Pç", qty:2},
  {num:37, desc:"Chave inglesa 300mm isolada", uni:"Pç", qty:2},
  {num:39, desc:"Computador notebook (**)", uni:"Pç", qty:1},
  {num:40, desc:"Cone de sinalização, altura mínima 700mm", uni:"Pç", qty:10},
  {num:41, desc:"Conjunto chave allen em mm de 8; 6; 5; 4; 3; 2,5 e 2", uni:"Cj", qty:1},
  {num:42, desc:"Conjunto chave allen em polegadas de 1/4; 7/32; 3/16; 5/32; 9/64; 1/8; 7/64; 3/32 e 5/64", uni:"Cj", qty:1},
  {num:43, desc:"Conjunto de aterramento temporário para baixa tensão", uni:"Cj", qty:2, laudo:2, fabs:["Terex","Solução","FCP"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:44, desc:"Conjunto de aterramento temporário para média tensão monofásico", uni:"Cj", qty:2, laudo:2, fabs:["Terex","Solução","FCP"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:45, desc:"Conjunto de aterramento temporário para média tensão trifásico", uni:"Cj", qty:2, laudo:2, fabs:["Terex","Solução","FCP"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:46, desc:"Conjunto de aterramento temporário sela com grampo de aterramento e haste", uni:"Cj", qty:3, laudo:3, fabs:["Terex"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:47, desc:"Corda para isolamento de área (mínimo 8mm)", uni:"M", qty:50},
  {num:48, desc:"Crachá de identificação", uni:"Pç", qty:2},
  {num:49, desc:"Degrau de Fibra", uni:"Pç", qty:4},
  {num:50, desc:"Descascador de cabos para RDC", uni:"Pç", qty:1},
  {num:52, desc:"Detector de MT de 1 a 35 kV", uni:"Pç", qty:1, laudo:1, fabs:["Terex","Solução","Lider","Steetc"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:54, desc:"Dinamômetro 45 kgf para teste de padrão de entrada", uni:"Pç", qty:1, laudo:1, fabs:[], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:55, desc:"Dispositivo anti-queda de cartucho", uni:"Pç", qty:1},
  {num:56, desc:"Dispositivo by-pass para chave fusível (*)", uni:"Pç", qty:1},
  {num:57, desc:"Dispositivo de abertura em carga para MT", uni:"Pç", qty:1, laudo:1, fabs:["Leal","S&C","Solução"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:58, desc:"Dispositivo de corte de ramal", uni:"Pç", qty:1},
  {num:59, desc:"Dispositivo de fixação de placas de advertência", uni:"Pç", qty:5},
  {num:60, desc:"Dispositivos instaladores de linha de vida (agulhão + gancho)", uni:"Cj", qty:1},
  {num:64, desc:"Equipamento de comunicação de dados e voz conforme especificação da Contratante (incluindo câmera fotográfica e GPS)", uni:"Pç", qty:1},
  {num:65, desc:"Escada de extensão 2 x 4,25m (± 0,5m) de fibra", uni:"Pç", qty:2},
  {num:66, desc:"Escada singela 1 x 3,50m (± 0,5m) de fibra", uni:"Pç", qty:1},
  {num:67, desc:"Escova de aço tubular para condutores", uni:"Pç", qty:2},
  {num:68, desc:"Esticador com correia ou moitão de 2 gornes para condutores CA/CAA", uni:"Pç", qty:1},
  {num:69, desc:"Sovela (Estilete) para teste em poste de madeira", uni:"Pç", qty:1},
  {num:72, desc:"Estropo de Corrente para içamento de equipamentos, com laudo de capacidade de carga", uni:"Pç", qty:1},
  {num:73, desc:"Estropo Cinta Tubular de 800mm com identificação indelével da capacidade de carga 1000 daN", uni:"Pç", qty:2},
  {num:75, desc:"Ferramenta para aplicação de conector cunha (com corda e gancho)", uni:"Pç", qty:1},
  {num:77, desc:"Garra para cabo CA/CAA 2/0 a 336", uni:"Pç", qty:2},
  {num:78, desc:"Garra para cabo CA/CAA 6 a 1/0", uni:"Pç", qty:2},
  {num:79, desc:"Garra para cabo de aço 6,4mm a 9,5mm", uni:"Pç", qty:2},
  {num:80, desc:"Garra para aterramento temporário chave fusível", uni:"Pç", qty:3},
  {num:81, desc:"Grampo prendedor de lençol", uni:"Pç", qty:8},
  {num:82, desc:"Impressora Térmica Portátil", uni:"Pç", qty:1, laudo:1, fabs:["ZEBRA RW420","ZEBRA ZQ520","ZEBRA ZQ521","BIXOLON XM7-40"]},
  {num:83, desc:"Inflador ou testador de luvas de borracha (*)", uni:"Pç", qty:1},
  {num:80, desc:"Kit Calibrador portátil para ensaio em medidor kWh eletromecânico e eletrônico (**)", uni:"Pç", qty:1, laudo:1, fabs:["Montrel"]},
  {num:85, desc:"Kit Antirreprova (**)", uni:"Pç", qty:1},
  {num:86, desc:"Lanterna", uni:"Pç", qty:2},
  {num:87, desc:"Lençol de borracha isolante para BT e sacola para acondicionar", uni:"Pç", qty:10, laudo:10, labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:90, desc:"Lima murça chata", uni:"Pç", qty:1},
  {num:92, desc:"Marreta de aço de 2,5 kg", uni:"Pç", qty:1},
  {num:93, desc:"Martelo bola", uni:"Pç", qty:1},
  {num:94, desc:"Mastro equilíbrio de momento (*)", uni:"Pç", qty:1},
  {num:95, desc:"Matriz para alicate hidráulico (162, 163, 236, 237, 238, 239, 242, 243, 245, 248, 249, 251, 252, 316, 321, D3, N e O)", uni:"Cj", qty:1},
  {num:96, desc:"Matriz para alicate mecânico (162, 163, 236, 237, 238, 239, 242, 243 e 245)", uni:"Cj", qty:1},
  {num:99, desc:"Moitão de 3 gornes de 1800 daN", uni:"Pç", qty:1},
  {num:100, desc:"Motosserra com freio de corrente, devidamente licenciada e registrada pelo IBAMA (*)", uni:"Pç", qty:1, laudo:1},
  {num:103, desc:"Placa de advertência 'não opere esta chave'", uni:"Pç", qty:5},
  {num:106, desc:"Ponteiro de aço 1/2 pol de mão", uni:"Pç", qty:1},
  {num:107, desc:"Recipiente aprovado pelo INMETRO para transporte e armazenamento de combustível para motosserra (*)", uni:"Pç", qty:1},
  {num:108, desc:"Sequencímetro BT", uni:"Pç", qty:1},
  {num:109, desc:"Serra para corte de galhos 21'' (533mm) ou 23'' (610mm)", uni:"Pç", qty:1},
  {num:110, desc:"Serrote curvo para poda", uni:"Pç", qty:1},
  {num:115, desc:"Tesourão articulado 750mm (com corda e gancho)", uni:"Pç", qty:1},
  {num:116, desc:"Trado aço de 3/8\" para madeira", uni:"Pç", qty:1},
  {num:117, desc:"Trena de fibra de 50m", uni:"Pç", qty:1},
  {num:119, desc:"Volt-amperímetro alicate classe IV", uni:"Pç", qty:2, laudo:2, labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
];

const es2Epis = [
  {num:120, desc:"Bolsa de Lona para acondicionar capacete, luva de vaqueta e óculos", uni:"Un", qty:2},
  {num:121, desc:"Bolsa de Lona para acondicionar manga isolante", uni:"Un", qty:2},
  {num:122, desc:"Bolsa para acondicionar luva isolante", uni:"Un", qty:4},
  {num:123, desc:"Botina de Segurança com cadarço", uni:"Pr", qty:4},
  {num:124, desc:"Calça de Uniforme com Tecido Resistente à Chama – condutibilidade, inflamabilidade e influências eletromagnéticas, com logotipo empresa", uni:"Un", qty:6},
  {num:125, desc:"Camisa de Uniforme manga longa com Tecido Resistente à Chama – condutibilidade, inflamabilidade e influências eletromagnéticas com logotipo empresa", uni:"Un", qty:6},
  {num:126, desc:"Capa impermeável para chuva (calça e blusa separadas, com faixa reflexiva)", uni:"Un", qty:2},
  {num:127, desc:"Capacete de segurança, classe B, com aba frontal e jugular", uni:"Un", qty:2},
  {num:128, desc:"Capuz de proteção solar com tecido Resistente à Chama", uni:"Un", qty:2},
  {num:129, desc:"Carretilha de dupla ação com corda e gancho para trabalho e resgate", uni:"Un", qty:2, laudo:2},
  {num:130, desc:"Conjunto cinto paraquedista, talabarte de posicionamento com mosquetão de alumínio tripla trava e trava quedas", uni:"Cj", qty:2, laudo:2, fabs:["Leal"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:131, desc:"Corda de linha de vida 12mm – normatizadas pela NR18 (Cabos de fibra sintética) – 15 metros", uni:"Pç", qty:2},
  {num:132, desc:"EPI para operador de Motosserra – Capacete com viseira acoplado com abafador de ruído tipo concha, luvas, botina com biqueira e calça especificadas para a atividade", uni:"Pç", qty:1},
  {num:133, desc:"Espora de aço completa com correia para poste duplo T", uni:"Pr", qty:2},
  {num:136, desc:"Garrafa térmica de 5 litros (1 garrafa para cada 2 pessoas)", uni:"Un", qty:1},
  {num:137, desc:"Jaqueta de Uniforme com Tecido Resistente à Chama (OPCIONAL, de acordo com a necessidade da região)", uni:"Un", qty:2},
  {num:138, desc:"Luva de borracha isolante 0,5kV (classe 00)", uni:"Pr", qty:2, laudo:2, fabs:["Salisbury","Northsafety","GB","Orion"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:139, desc:"Luva de borracha Isolante 17kV (classe 2) ou 26,5kV (classe 3) – Conforme nível de tensão da região", uni:"Pr", qty:2, laudo:2, fabs:["Salisbury","Northsafety","GB","Orion"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:140, desc:"Luva de couro para proteção da luva de borracha isolante", uni:"Pr", qty:4},
  {num:142, desc:"Luva de vaqueta para trabalho leve", uni:"Pr", qty:2},
  {num:143, desc:"Manga isolante para 1kV – (Classe 0)", uni:"Pr", qty:2, laudo:2, fabs:["Salisbury","GB"], labs:["Oficina do Alicate","ITRA","REMO","CTMIG","Helite","BHMIG","GLOBALTEK"]},
  {num:144, desc:"Mosquetão de aço dupla trava 22kN (para pontos de ancoragem)", uni:"Pç", qty:4},
  {num:145, desc:"Óculos de segurança incolor para proteção de partículas multidirecionais", uni:"Un", qty:2},
  {num:146, desc:"Óculos de segurança lente escura tonalidade 2 ou 3 para proteção de partículas multidirecionais", uni:"Un", qty:2},
  {num:147, desc:"Perneira de couro sem partes metálicas ou Bota de Campanha", uni:"Pr", qty:2},
  {num:149, desc:"Protetor solar FPS 30", uni:"Un", qty:2},
  {num:150, desc:"Sacola para ferramentas 'tira colo'", uni:"Un", qty:1},
  {num:151, desc:"Sacola de Lona para acondicionar ferramenta e EPIs (catarina)", uni:"Un", qty:2},
  {num:152, desc:"Sacola de Lona para acondicionar linha de vida e cinto", uni:"Un", qty:2},
];

const es2Kit = [
  {num:1, desc:"Caixa de ferramentas para acondicionamento dos itens – Capacidade Média 10L", uni:"PÇ", qty:1},
  {num:2, desc:"Cadeado médio", uni:"PÇ", qty:1},
  {num:3, desc:"Talhadeira tamanho Médio (25 cm)", uni:"PÇ", qty:1},
  {num:4, desc:"Marreta de 1 Kg", uni:"PÇ", qty:1},
  {num:5, desc:"Pincel Pequeno (15 cm)", uni:"PÇ", qty:1},
  {num:6, desc:"Gabarito / Molde alfabeto e Números", uni:"CJ", qty:1},
  {num:7, desc:"Lata de tinta pequena (50 ml)", uni:"PÇ", qty:1},
  {num:8, desc:"Chave de boca 16", uni:"PÇ", qty:1},
  {num:9, desc:"Parafuso Vazado (dispositivo para selar)", uni:"PÇ", qty:5},
  {num:10, desc:"Conector Bimetálico (Parafuso fendido)", uni:"PÇ", qty:5},
  {num:11, desc:"Parafuso terminal para Aterramento", uni:"PÇ", qty:5},
  {num:12, desc:"Fita Isolante tamanho Médio – 05 metros", uni:"PÇ", qty:1},
  {num:13, desc:"Fita Alta Fusão – 05 Metros", uni:"PÇ", qty:1},
  {num:14, desc:"Visor para Caixa de Medição tamanho Padrão", uni:"PÇ", qty:5},
  {num:15, desc:"Disjuntor Monopolar de 40A", uni:"PÇ", qty:3},
  {num:16, desc:"Disjuntor Monopolar de 70A", uni:"PÇ", qty:2},
  {num:17, desc:"Disjuntor Bipolar de 60A", uni:"PÇ", qty:2},
  {num:18, desc:"Disjuntor Tripolar de 50A", uni:"PÇ", qty:1},
  {num:19, desc:"Disjuntor Tripolar de 60A", uni:"PÇ", qty:1},
  {num:20, desc:"Parafuso para fixação de Medidor à caixa Medição", uni:"PÇ", qty:5},
  {num:21, desc:"Parafuso para fixação de Medidor ao Cavalete", uni:"PÇ", qty:5},
  {num:22, desc:"Tampão para vedação de furos de caixa Monofásica", uni:"PÇ", qty:5},
  {num:23, desc:"Tampão para vedação de furos de caixa Polifásica", uni:"PÇ", qty:5},
  {num:24, desc:"Terminal Tubular de Cobre para cabo 6mm", uni:"PÇ", qty:5},
  {num:25, desc:"Terminal Tubular de Cobre para cabo 10mm", uni:"PÇ", qty:5},
  {num:26, desc:"Terminal Tubular de Cobre para cabo 16mm", uni:"PÇ", qty:5},
  {num:27, desc:"Terminal Tubular de Cobre para cabo 25mm", uni:"PÇ", qty:5},
  {num:28, desc:"Terminal Tubular de Cobre para cabo 50mm", uni:"PÇ", qty:5},
  {num:29, desc:"Flanela / estopa para limpeza", uni:"PÇ", qty:1},
  {num:30, desc:"1 metro de cabo de cobre 6mm (para rabicho)", uni:"M", qty:1},
  {num:31, desc:"1 metro de cabo de cobre 10mm (para rabicho)", uni:"M", qty:1},
  {num:32, desc:"1 metro de cabo de cobre 16mm (para rabicho)", uni:"M", qty:1},
];

const es2ChecklistVeiculo = [
  "Veículo próprio / locado",
  "Documentação atualizada",
  "Controle de manutenção do veículo (físico ou digital)",
  "Câmera veicular",
  "Rastreador veicular",
  "Sistema de Amarração de Escadas",
  "Pneu em condições de uso (s/ reformar eixo diant.)",
  "Pneu de mesmo desenho no mesmo eixo",
  "Identificação 'à serviço da CEMIG'",
  "Funilaria em boas condições",
  "Todas as setas em correto funcionamento",
  "Farol alto e baixo em correto funcionamento",
  "Giroflex",
  "Silibim (iluminação auxiliar)",
  "Buzina em correto funcionamento",
  "Kit resgate (fabricante Soluções)",
];

const es2ChecklistEscada = [
  "Escada giratória em correto funcionamento",
  "Placa de identificação da torre",
  "Laudo da escada giratória",
  "Controle de manutenção da escada (físico ou digital)",
  "Equipamento com fabricação menor a 15 anos",
  "Equipamento com gráfico de carga visível",
  "Placa de identificação da cesta aérea",
  "Laudo de inspeção de manutenção válido",
  "Manutenção anual válida",
  "Laudo de emissão acústica válido (4 em 4 anos)",
  "Controles identificados e protegidos contra uso inadvertido",
  "Ponto de aterramento no chassi e equipamento",
  "Inclinômetro",
  "Bloqueio de sapata por braço fora do berço",
  "Válvula de segurança com holding dos cilindros do braço",
  "Ponto de ancoragem",
  "Sistema de parada de emergência inferior e superior",
  "Sistema de operação de emergência",
  "Sistema de nivelamento da cesta aérea",
  "Liner e teste para 46 kV (inserir validade do laudo nas observações)",
];

// ════════════════════════════════════════════════════════
// RENDER FUNCTIONS
// ════════════════════════════════════════════════════════
let idCounter = 0;
function uid() { return 'f' + (++idCounter); }

function renderLaudo(n, fabs, labs, hasValidade = true) {
  let html = '<div class="laudo-row">';
  for (let i = 1; i <= n; i++) {
    const id = uid();
    html += `<div class="laudo-grid" style="margin-bottom:${n>1?'8px':'0'}">
      <span style="font-size:11px;font-weight:700;color:var(--cemig-blue);">${n>1?i+'º ':''}Laudo</span>
      <div class="radio-group">
        <label><input type="radio" name="${id}" value="S"> S</label>
        <label><input type="radio" name="${id}" value="N"> N</label>
      </div>
      <label>Nº controle:</label>
      <input type="text" placeholder="___________" style="width:120px;">
      ${hasValidade ? `<label>Validade:</label><input type="text" placeholder="__/__/____" style="width:100px;">` : ''}
    </div>`;
  }
  if (fabs && fabs.length > 0) {
    html += `<div class="fab-row"><span>Fabricantes:</span>`;
    fabs.forEach(f => { html += `<label class="checkbox-inline"><input type="checkbox"> ${f}</label>`; });
    html += `<label class="checkbox-inline"><input type="checkbox"> Outro</label></div>`;
  }
  if (labs && labs.length > 0) {
    html += `<div class="fab-row"><span>Laboratórios:</span>`;
    labs.forEach(l => { html += `<label class="checkbox-inline"><input type="checkbox"> ${l}</label>`; });
    html += `<label class="checkbox-inline"><input type="checkbox"> Outro</label></div>`;
  }
  html += '</div>';
  return html;
}

function renderTableQty(items, tbodyId) {
  const tbody = document.getElementById(tbodyId);
  let html = '';
  items.forEach(item => {
    html += `<tr>
      <td class="item-num">${item.num}</td>
      <td>${item.desc}</td>
      <td class="item-uni">${item.uni}</td>
      <td class="item-qty">${item.qty}</td>
      <td><input class="qty-input" type="number" min="0" placeholder="0" data-item="${item.num}"></td>
    </tr>`;
    if (item.laudo) {
      html += `<tr><td colspan="5" style="padding:4px 10px 8px;">
        ${renderLaudo(item.laudo, item.fabs, item.labs)}
      </td></tr>`;
    }
  });
  tbody.innerHTML = html;
}

function renderInfraTable() {
  const tbody = document.getElementById('tb-infra-items');
  let html = '';
  infraItems.forEach(item => {
    const name = 'infra-item-' + item.num;
    html += `<tr>
      <td class="item-num">${item.num}</td>
      <td>${item.desc}</td>
      <td>
        <div class="na-c-nc">
          <label><input type="radio" name="${name}" value="NA"><span>N-A</span></label>
          <label><input type="radio" name="${name}" value="C"><span>C</span></label>
          <label><input type="radio" name="${name}" value="NC"><span>NC</span></label>
        </div>
      </td>
    </tr>`;
  });
  tbody.innerHTML = html;
}

function renderChecklist(items, divId) {
  const div = document.getElementById(divId);
  div.innerHTML = items.map((item, i) =>
    `<div class="checklist-item">
      <input type="checkbox" id="cl-${divId}-${i}">
      <label for="cl-${divId}-${i}">${item}</label>
    </div>`
  ).join('');
}

// ════════════════════════════════════════════════════════
// NAVIGATION
// ════════════════════════════════════════════════════════
let currentForm = null;

function showForm(formId) {
  document.getElementById('home-screen').classList.add('hidden');
  ['form-infra','form-moto','form-es2'].forEach(id => document.getElementById(id).classList.add('hidden'));
  document.getElementById('form-' + formId).classList.remove('hidden');
  currentForm = formId;
  window.scrollTo(0, 0);
}

function goHome() {
  ['form-infra','form-moto','form-es2'].forEach(id => document.getElementById(id).classList.add('hidden'));
  document.getElementById('home-screen').classList.remove('hidden');
  currentForm = null;
  window.scrollTo(0, 0);
}

function toggleOutro(el, targetId) {
  const outroInput = document.getElementById(targetId);
  if (el.value === 'Outro') {
    outroInput.classList.remove('hidden');
  } else {
    outroInput.classList.add('hidden');
  }
}

function resetForm(formId) {
  if (!confirm('Limpar todos os campos deste formulário?')) return;
  const container = document.getElementById('form-' + formId);
  container.querySelectorAll('input, textarea, select').forEach(el => {
    if (el.type === 'checkbox' || el.type === 'radio') el.checked = false;
    else el.value = '';
  });
}

// ════════════════════════════════════════════════════════
// EXPORT PDF
// ════════════════════════════════════════════════════════
function exportPDF() {
  window.print();
}

// ════════════════════════════════════════════════════════
// EXPORT EXCEL
// ════════════════════════════════════════════════════════
function exportExcel(formId) {
  const wb = XLSX.utils.book_new();
  const today = new Date().toLocaleDateString('pt-BR');

  if (formId === 'infra') {
    exportInfraExcel(wb, today);
  } else if (formId === 'moto') {
    exportMotoExcel(wb, today);
  } else if (formId === 'es2') {
    exportES2Excel(wb, today);
  }

  const formNames = {infra:'Infraestrutura', moto:'Motociclistas', es2:'Multifuncional_ES2'};
  XLSX.writeFile(wb, `ATE_${formNames[formId]}_${today.replace(/\//g,'-')}.xlsx`);
}

function getVal(selector) {
  const el = document.querySelector(selector);
  return el ? el.value : '';
}

function getRadio(name) {
  const el = document.querySelector(`input[name="${name}"]:checked`);
  return el ? el.value : '';
}

function exportInfraExcel(wb, today) {
  // Info sheet
  const info = [
    ['FORMULÁRIO ATE – INFRAESTRUTURA ADMINISTRATIVA'],
    ['Data de exportação', today],
    [''],
    ['ENDEREÇO'],
    ['Av./Rua', getVal('[data-field="infra-endereco"]')],
    ['Número', getVal('[data-field="infra-numero"]')],
    ['Bairro', getVal('[data-field="infra-bairro"]')],
    ['Cidade', getVal('[data-field="infra-cidade"]')],
    [''],
    ['RESPONSÁVEL'],
    ['Nome', getVal('[data-field="infra-resp-nome"]')],
    ['CPF', getVal('[data-field="infra-resp-cpf"]')],
    ['Função', getVal('[data-field="infra-resp-funcao"]')],
    [''],
    ['Observações', getVal('[data-field="infra-obs"]')],
  ];
  const ws1 = XLSX.utils.aoa_to_sheet(info);
  XLSX.utils.book_append_sheet(wb, ws1, 'Informações');

  // Items sheet
  const itemRows = [['Item', 'Descrição', 'Avaliação']];
  infraItems.forEach(item => {
    const val = getRadio('infra-item-' + item.num);
    const label = val === 'NA' ? 'N-A' : val === 'C' ? 'Conforme' : val === 'NC' ? 'Não Conforme' : '';
    itemRows.push([item.num, item.desc, label]);
  });
  const ws2 = XLSX.utils.aoa_to_sheet(itemRows);
  ws2['!cols'] = [{wch:6},{wch:80},{wch:15}];
  XLSX.utils.book_append_sheet(wb, ws2, 'Itens de Avaliação');
}

function exportMotoExcel(wb, today) {
  const container = document.getElementById('form-moto');
  const info = [
    ['FORMULÁRIO ATE – EQUIPES DE MOTOCICLISTAS'],
    ['Data de exportação', today],
    [''],
    ['AGENTES EXECUTORES'],
    ['Agente 1', getVal('[data-field="moto-agente1"]'), 'Matrícula', getVal('[data-field="moto-mat1"]')],
    ['Agente 2', getVal('[data-field="moto-agente2"]'), 'Matrícula', getVal('[data-field="moto-mat2"]')],
    ['Agente 3', getVal('[data-field="moto-agente3"]'), 'Matrícula', getVal('[data-field="moto-mat3"]')],
    [''],
    ['Local', getRadio('moto-local') || getVal('[data-field="moto-outro-local"]')],
    ['Data', getVal('[data-field="moto-data"]')],
    [''],
    ['EQUIPE'],
    ['Nome', getVal('[data-field="moto-nome1"]')],
    ['CPF', getVal('[data-field="moto-cpf1"]')],
    ['Crachá', getVal('[data-field="moto-cracha1"]')],
    [''],
    ['VEÍCULO'],
    ['Placa', getVal('[data-field="moto-placa"]')],
    ['Modelo', getVal('[data-field="moto-modelo"]')],
    ['Marca', getVal('[data-field="moto-marca"]')],
    ['Ano', getVal('[data-field="moto-ano"]')],
    [''],
    ['Observações Ferramentas', getVal('[data-field="moto-obs-ferr"]')],
    ['Observações Veículo', getVal('[data-field="moto-obs-veic"]')],
  ];
  const ws1 = XLSX.utils.aoa_to_sheet(info);
  XLSX.utils.book_append_sheet(wb, ws1, 'Informações');

  // Ferramental + EPIs
  const rows = [['Item', 'Descrição', 'Uni.', 'Qtd. Exigida', 'Qtd. Pendente']];
  collectTableData(container, 'tb-moto-ferramentas', motoFerramentas, rows);
  collectTableData(container, 'tb-moto-epis', motoEpis, rows);
  const ws2 = XLSX.utils.aoa_to_sheet(rows);
  ws2['!cols'] = [{wch:6},{wch:70},{wch:6},{wch:12},{wch:14}];
  XLSX.utils.book_append_sheet(wb, ws2, 'Ferramentas e EPIs');

  // Checklist
  const clRows = [['Item', 'Conforme']];
  const clDiv = document.getElementById('checklist-moto-veiculo');
  clDiv.querySelectorAll('.checklist-item').forEach((el, i) => {
    const checked = el.querySelector('input[type="checkbox"]').checked;
    clRows.push([motoChecklistVeiculo[i], checked ? 'Sim' : 'Não']);
  });
  const ws3 = XLSX.utils.aoa_to_sheet(clRows);
  ws3['!cols'] = [{wch:50},{wch:10}];
  XLSX.utils.book_append_sheet(wb, ws3, 'Checklist Veículo');
}

function exportES2Excel(wb, today) {
  const container = document.getElementById('form-es2');
  const info = [
    ['FORMULÁRIO ATE – MULTIFUNCIONAL ES2'],
    ['Data de exportação', today],
    [''],
    ['AGENTES EXECUTORES'],
    ['Agente 1', getVal('[data-field="es2-agente1"]'), 'Matrícula', getVal('[data-field="es2-mat1"]')],
    ['Agente 2', getVal('[data-field="es2-agente2"]'), 'Matrícula', getVal('[data-field="es2-mat2"]')],
    ['Agente 3', getVal('[data-field="es2-agente3"]'), 'Matrícula', getVal('[data-field="es2-mat3"]')],
    [''],
    ['Local', getRadio('es2-local') || getVal('[data-field="es2-outro-local"]')],
    ['Data', getVal('[data-field="es2-data"]')],
    [''],
    ['EQUIPE'],
    ['Nome 1', getVal('[data-field="es2-nome1"]'), 'CPF', getVal('[data-field="es2-cpf1"]'), 'Crachá', getVal('[data-field="es2-cracha1"]')],
    ['Nome 2', getVal('[data-field="es2-nome2"]'), 'CPF', getVal('[data-field="es2-cpf2"]'), 'Crachá', getVal('[data-field="es2-cracha2"]')],
    [''],
    ['VEÍCULO'],
    ['Placa', getVal('[data-field="es2-placa"]'), 'Modelo', getVal('[data-field="es2-modelo"]')],
    ['Marca', getVal('[data-field="es2-marca-veic"]'), 'Ano', getVal('[data-field="es2-ano"]')],
    ['Motorista', getVal('[data-field="es2-motorista"]'), 'CPF Motorista', getVal('[data-field="es2-cpf-mot"]')],
    ['Tipo Equipamento', getRadio('es2-tipo-equip')],
    ['Marca Equip.', getVal('[data-field="es2-marca-equip"]'), 'Modelo Equip.', getVal('[data-field="es2-modelo-equip"]'), 'Ano Equip.', getVal('[data-field="es2-ano-equip"]')],
    [''],
    ['Obs. Ferramentas', getVal('[data-field="es2-obs-ferr"]')],
    ['Obs. Veículo', getVal('[data-field="es2-obs-veic"]')],
    ['Obs. Kit', getVal('[data-field="es2-obs-kit"]')],
  ];
  const ws1 = XLSX.utils.aoa_to_sheet(info);
  XLSX.utils.book_append_sheet(wb, ws1, 'Informações');

  // Ferramentas
  const ferrRows = [['Item', 'Descrição', 'Uni.', 'Qtd. Exigida', 'Qtd. Pendente']];
  collectTableData(container, 'tb-es2-ferramentas', es2Ferramentas, ferrRows);
  const ws2 = XLSX.utils.aoa_to_sheet(ferrRows);
  ws2['!cols'] = [{wch:6},{wch:70},{wch:6},{wch:12},{wch:14}];
  XLSX.utils.book_append_sheet(wb, ws2, 'Ferramentas');

  // EPIs
  const epiRows = [['Item', 'Descrição', 'Uni.', 'Qtd. Exigida', 'Qtd. Pendente']];
  collectTableData(container, 'tb-es2-epis', es2Epis, epiRows);
  const ws3 = XLSX.utils.aoa_to_sheet(epiRows);
  ws3['!cols'] = [{wch:6},{wch:70},{wch:6},{wch:12},{wch:14}];
  XLSX.utils.book_append_sheet(wb, ws3, 'EPIs');

  // Kit
  const kitRows = [['Item', 'Descrição', 'Uni.', 'Qtd. Exigida', 'Qtd. Pendente']];
  collectTableData(container, 'tb-es2-kit', es2Kit, kitRows);
  const ws4 = XLSX.utils.aoa_to_sheet(kitRows);
  ws4['!cols'] = [{wch:6},{wch:70},{wch:6},{wch:12},{wch:14}];
  XLSX.utils.book_append_sheet(wb, ws4, 'Kit Antirreprova');

  // Checklists
  const clRows = [['Item', 'Conforme']];
  const clDiv1 = document.getElementById('checklist-es2-veiculo');
  clDiv1.querySelectorAll('.checklist-item').forEach((el, i) => {
    clRows.push([es2ChecklistVeiculo[i], el.querySelector('input').checked ? 'Sim' : 'Não']);
  });
  clRows.push(['', '']);
  clRows.push(['EQUIPAMENTO (Escada/Cesta)', '']);
  const clDiv2 = document.getElementById('checklist-es2-escada');
  clDiv2.querySelectorAll('.checklist-item').forEach((el, i) => {
    clRows.push([es2ChecklistEscada[i], el.querySelector('input').checked ? 'Sim' : 'Não']);
  });
  const ws5 = XLSX.utils.aoa_to_sheet(clRows);
  ws5['!cols'] = [{wch:55},{wch:10}];
  XLSX.utils.book_append_sheet(wb, ws5, 'Checklist Veículo');
}

function collectTableData(container, tbodyId, dataArray, rows) {
  const inputs = container.querySelectorAll(`#${tbodyId} .qty-input`);
  let inputIdx = 0;
  dataArray.forEach(item => {
    const pendente = inputs[inputIdx] ? inputs[inputIdx].value || '' : '';
    rows.push([item.num, item.desc, item.uni, item.qty, pendente]);
    inputIdx++;
  });
}

// ════════════════════════════════════════════════════════
// INIT
// ════════════════════════════════════════════════════════
renderInfraTable();
renderTableQty(motoFerramentas, 'tb-moto-ferramentas');
renderTableQty(motoEpis, 'tb-moto-epis');
renderChecklist(motoChecklistVeiculo, 'checklist-moto-veiculo');
renderTableQty(es2Ferramentas, 'tb-es2-ferramentas');
renderTableQty(es2Epis, 'tb-es2-epis');
renderTableQty(es2Kit, 'tb-es2-kit');
renderChecklist(es2ChecklistVeiculo, 'checklist-es2-veiculo');
renderChecklist(es2ChecklistEscada, 'checklist-es2-escada');
</script>
</body>
</html>
