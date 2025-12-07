<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Generator zleceń dla informatyka — AI/API</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#6ee7b7;--muted:#9ca3af;color-scheme:dark}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;margin:0;padding:24px;background:linear-gradient(180deg,#071024 0%,#091427 100%);color:#e6eef6}
    .container{max-width:980px;margin:0 auto}
    h1{font-size:20px;margin:0 0 12px}
    .grid{display:grid;grid-template-columns:1fr 360px;gap:18px}
    .card{background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.03);padding:14px;border-radius:12px}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
    input,select,textarea{width:100%;padding:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
    button{background:linear-gradient(90deg,var(--accent),#34d399);border:0;padding:10px 12px;border-radius:10px;color:#042018;cursor:pointer}
    .small{font-size:13px;color:var(--muted)}
    .task{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:10px;margin-bottom:10px}
    .meta{font-size:12px;color:var(--muted);margin-top:6px}
    .actions{display:flex;gap:8px;margin-top:10px}
    pre{white-space:pre-wrap;background:rgba(0,0,0,0.25);padding:10px;border-radius:8px;font-size:13px}
    footer{margin-top:18px;font-size:13px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="container">
    <h1>Generator zleceń dla informatyka — AI/API</h1>
    <div class="grid">
      <div>
        <div class="card">
          <label for="client">Klient / firma</label>
          <input id="client" placeholder="Nazwa klienta (np. 'Firma X')">

          <label for="role">Rodzaj zlecenia</label>
          <select id="role">
            <option>Rozwój aplikacji webowej</option>
            <option>Naprawa błędów / bugfix</option>
            <option>Integracja API / automatyzacja</option>
            <option>Utrzymanie serwera / DevOps</option>
            <option>Analiza bezpieczeństwa</option>
            <option>Projektowanie bazy danych</option>
            <option>Optymalizacja wydajności</option>
            <option>Inne</option>
          </select>

          <label for="stack">Technologie (komma)</label>
          <input id="stack" placeholder="np. Node.js, React, PostgreSQL">

          <label for="complexity">Poziom skomplikowania</label>
          <select id="complexity">
            <option>Proste (1-2 dni)</option>
            <option>Średnie (3-7 dni)</option>
            <option>Rozbudowane (2-4 tygodnie)</option>
            <option>Projekt długoterminowy (miesiące)</option>
          </select>

          <label for="urgency">Pilność</label>
          <select id="urgency">
            <option>Normalna</option>
            <option>Priorytetowa (24h)</option>
            <option>Natychmiastowa (do kilku godzin)</option>
          </select>

          <label for="budget">Budżet (PLN)</label>
          <input id="budget" placeholder="np. 1500">

          <label for="desc">Dodatkowy opis / wymagania</label>
          <textarea id="desc" rows="4" placeholder="Szczegóły zlecenia, dostęp do repozytorium, wymagania SLA..."></textarea>

          <div style="display:flex;gap:8px;margin-top:12px">
            <button id="generate">Generuj zlecenie</button>
            <button id="generateMany">Generuj 5 wariantów</button>
            <button id=\"export\">Eksportuj JSON<\/button>
            <button id=\"exportCSV\">Eksport CSV</button>
          </div>

          <div style="margin-top:12px">
            <label class="small">Szablony (edytowalne)</label>
            <textarea id="templates" rows="4">Proszę przygotować: {role} wykorzystując {stack}. Termin: {complexity}. Budżet: {budget} PLN. Pilność: {urgency}. Dodatkowe: {desc}</textarea>
          </div>

          <div style="margin-top:12px">
            <label class="small">Integracja z AI / API (opcjonalnie)</label>
            <input id="apiKey" placeholder="Wklej klucz API (nie wysyłaj publicznie)">
            <select id="model">
              <option value="gpt-4o">gpt-4o</option>
              <option value="gpt-4o-mini">gpt-4o-mini</option>
              <option value="gpt-3.5-turbo">gpt-3.5-turbo</option>
            </select>
            <div class="actions">
              <button id="expandAI">Rozwiń opis z AI</button>
              <button id="createBrief">Stwórz brief (AI)</button>
            </div>
            <p class="small">Uwaga: kod poniżej wysyła żądanie bezpośrednio do API — dbaj o klucz. Jeśli nie chcesz korzystać, zostaw pole puste.</p>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h2 style="margin:0 0 8px">Wygenerowane zlecenia</h2>
          <div id="list"></div>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3 style="margin-top:0">Podgląd / szablon JSON</h3>
          <pre id="preview">Brak wygenerowanych zleceń.</pre>
          <div style="margin-top:10px;display:flex;gap:8px">
            <button id="copy">Kopiuj</button>
            <button id="print">Drukuj</button>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="margin-top:0">Szybkie polecenia</h3>
          <p class="small">Przykłady promptów i zastosowań:</p>
          <ul class="small">
            <li>Przygotuj brief techniczny dla wykonawcy.</li>
            <li>Wygeneruj listę kamieni milowych oraz estymację czasu.</li>
            <li>Stwórz wiadomość ofertową dla klienta z ceną i SLA.</li>
          </ul>
        </div>
      </aside>
    </div>

    <footer>
      <div class="small">Instrukcja: Wypełnij pola po lewej i kliknij "Generuj zlecenie". Możesz wkleić klucz API i użyć przycisków AI do rozbudowania opisu (kod wysyła zapytanie typu POST — zadbaj o bezpieczeństwo klucza).</div>
    </footer>
  </div>

  <script>
    function t(s){return s.trim()}
    function makeId(){return Math.random().toString(36).slice(2,9)}

    function buildFromTemplate(data, template){
      return template.replace(/{(\w+)}/g, (_,k)=>data[k]||'')
    }

    function createTaskObject(){
      const data={
        id:makeId(),
        client:document.getElementById('client').value||'Klient nieokreślony',
        role:document.getElementById('role').value,
        stack:document.getElementById('stack').value,
        complexity:document.getElementById('complexity').value,
        urgency:document.getElementById('urgency').value,
        budget:document.getElementById('budget').value||'',
        desc:document.getElementById('desc').value||''
      }
      const template=document.getElementById('templates').value
      data.title = (data.client+' — '+data.role).trim()
      data.short = buildFromTemplate(data, template)
      data.created = new Date().toISOString()
      return data
    }

    function renderTasks(arr){
      const list=document.getElementById('list')
      list.innerHTML=''
      arr.forEach(t=>{
        const el=document.createElement('div');el.className='task'
        el.innerHTML=`<strong>${t.title}</strong><div class="meta">ID: ${t.id} • ${t.created.split('T')[0]} • ${t.complexity} • ${t.urgency}</div><div style="margin-top:8px">${t.short}</div>`
        list.appendChild(el)
      })
      document.getElementById('preview').textContent = JSON.stringify(arr, null, 2)
    }

    let tasks = []

    document.getElementById('generate').addEventListener('click',()=>{
      const t=createTaskObject(); tasks.unshift(t); renderTasks(tasks)
    })

    document.getElementById('generateMany').addEventListener('click',()=>{
      const n=5; for(let i=0;i<n;i++){tasks.unshift(createTaskObject())} renderTasks(tasks)
    })

    document.getElementById('export').addEventListener('click',()=>{
      const blob=new Blob([JSON.stringify(tasks,null,2)],{type:'application/json'});
      const url=URL.createObjectURL(blob); const a=document.createElement('a'); a.href=url; a.download='zlecenia.json'; a.click(); URL.revokeObjectURL(url);
    })

    document.getElementById('copy').addEventListener('click',()=>{
      navigator.clipboard.writeText(document.getElementById('preview').textContent).then(()=>alert('Skopiowano do schowka'))
    })

    document.getElementById('print').addEventListener('click',()=>{
      const w=window.open('about:blank','_blank'); w.document.write('<pre>'+document.getElementById('preview').textContent.replace(/</g,'&lt;')+'</pre>'); w.document.close(); w.print();
    })

    // --- Integracje Jira / GitHub ---
    document.getElementById('createBrief').insertAdjacentHTML('afterend', `
      <button id="sendJira">Wyślij do Jira (mock)</button>
      <button id="sendGitHub">Wyślij do GitHub Issues (mock)</button>
    `);

    document.addEventListener('click', e => {
      if(e.target.id === 'sendJira') alert('Integracja Jira — tu można dodać API Jira REST');
      if(e.target.id === 'sendGitHub') alert('Integracja GitHub — tu można dodać API GitHub Issues');
    });

    // --- Eksport CSV ---
    document.getElementById('exportCSV').addEventListener('click',()=>{
      if(tasks.length===0){alert('Brak danych');return}
      const header=['id','client','role','stack','complexity','urgency','budget','desc','created']
      const rows=tasks.map(t=>header.map(h=>`"${(t[h]||'').replace(/"/g,'""')}"`).join(','))
      const csv = header.join(',') + "
" + rows.join("
")
      const blob=new Blob([csv],{type:'text/csv'});
      const url=URL.createObjectURL(blob);
      const a=document.createElement('a');a.href=url;a.download='zlecenia.csv';a.click();URL.revokeObjectURL(url);
    })

    // --- AI / API helpers ---
    async function callAI(prompt, apiKey, model='gpt-4o'){
      if(!apiKey){alert('Wklej klucz API, aby użyć funkcji AI'); return null}
      // Example request — dostosuj endpoint/model do używanego dostawcy
      const payload = {model, messages:[{role:'user', content:prompt}], max_tokens:800}
      try{
        const res = await fetch('https://api.openai.com/v1/chat/completions',{
          method:'POST',
          headers:{'Content-Type':'application/json','Authorization':'Bearer '+apiKey},
          body:JSON.stringify(payload)
        })
        const js = await res.json();
        if(js.error) throw new Error(js.error.message||JSON.stringify(js))
        // support both choices and output
        const content = js.choices?.[0]?.message?.content || js.choices?.[0]?.text || JSON.stringify(js)
        return content
      }catch(e){alert('Błąd AI: '+e.message); return null}
    }

    document.getElementById('expandAI').addEventListener('click', async ()=>{
      const apiKey = document.getElementById('apiKey').value.trim()
      const model = document.getElementById('model').value
      const t=createTaskObject()
      const prompt = `Rozwiń i doprecyzuj poniższe zlecenie dla specjalisty IT tak, aby powstał jasny opis pracy (kroki do wykonania, oczekiwany rezultat, wymagania wstępne, przybliżony rozkład czasu):\n\n${t.short}`
      const ai = await callAI(prompt, apiKey, model)
      if(ai){ t.short = ai; tasks.unshift(t); renderTasks(tasks) }
    })

    document.getElementById('createBrief').addEventListener('click', async ()=>{
      const apiKey = document.getElementById('apiKey').value.trim()
      const model = document.getElementById('model').value
      const t=createTaskObject()
      const prompt = `Na podstawie poniższego opisu wygeneruj profesjonalny brief techniczny: nagłówek, cele projektu, wymagania techniczne, kamienie milowe z estymacją czasu, kryteria akceptacji i proponowaną wycenę.\n\n${t.short}`
      const ai = await callAI(prompt, apiKey, model)
      if(ai){ t.short = ai; tasks.unshift(t); renderTasks(tasks) }
    })

    // load example data
    document.getElementById('client').value='Firma X'
    document.getElementById('role').value='Integracja API / automatyzacja'
    document.getElementById('stack').value='Node.js, REST, PostgreSQL'
    document.getElementById('budget').value='3000'
  </script>
</body>
</html>
