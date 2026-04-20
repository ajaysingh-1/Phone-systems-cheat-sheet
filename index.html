
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:var(--font-sans)}
.wrap{padding:1rem 0}
.controls{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:1rem;align-items:center}
input[type=text]{flex:1;min-width:180px;font-size:13px}
select{font-size:13px;padding:6px 10px;border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);background:var(--color-background-primary);color:var(--color-text-primary);cursor:pointer}
.count{font-size:12px;color:var(--color-text-secondary);white-space:nowrap;align-self:center}
.tbl-wrap{overflow-x:auto;border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg)}
table{width:100%;border-collapse:collapse;font-size:12px;table-layout:fixed}
th{background:var(--color-background-secondary);color:var(--color-text-secondary);font-weight:500;font-size:11px;text-transform:uppercase;letter-spacing:0.04em;padding:10px 12px;border-bottom:0.5px solid var(--color-border-secondary);text-align:left;white-space:nowrap;cursor:pointer;user-select:none}
th:hover{color:var(--color-text-primary)}
th.sort-asc::after{content:" ↑"}
th.sort-desc::after{content:" ↓"}
td{padding:10px 12px;border-bottom:0.5px solid var(--color-border-tertiary);vertical-align:top;color:var(--color-text-primary);line-height:1.5}
tr:last-child td{border-bottom:none}
tr:hover td{background:var(--color-background-secondary)}
.name{font-weight:500;font-size:13px;white-space:nowrap}
.badge{display:inline-block;font-size:10px;padding:2px 7px;border-radius:20px;font-weight:500;white-space:nowrap}
.tier-ent{background:#E6F1FB;color:#0C447C}
.tier-mid{background:#EAF3DE;color:#27500A}
.tier-smb{background:#FAEEDA;color:#633806}
.tier-dev{background:#EEEDFE;color:#3C3489}
.tier-leg{background:#F1EFE8;color:#444441}
.tier-uc{background:#FAECE7;color:#712B13}
.int-native{background:#EAF3DE;color:#27500A}
.int-strong{background:#E6F1FB;color:#0C447C}
.int-api{background:#FAEEDA;color:#633806}
.int-mid{background:#F1EFE8;color:#444441}
.features-list{padding-left:14px;margin:0}
.features-list li{margin-bottom:2px;color:var(--color-text-primary)}
.price-main{font-weight:500;font-size:12px}
.price-sub{font-size:11px;color:var(--color-text-secondary);margin-top:2px}
.note{font-size:11px;color:var(--color-text-secondary);line-height:1.5}
col.c1{width:110px}col.c2{width:70px}col.c3{width:170px}col.c4{width:110px}col.c5{width:90px}col.c6{width:90px}col.c7{width:130px}col.c8{width:160px}
.hidden{display:none}
</style>
<div class="wrap">
<h2 class="sr-only">Top 20 telephone systems — features, pricing, and Salesforce integration reference table</h2>
<div class="controls">
  <input type="text" id="search" placeholder="Search platform, feature, method..." oninput="filter()">
  <select id="tierFilter" onchange="filter()">
    <option value="">All tiers</option>
    <option value="Enterprise">Enterprise</option>
    <option value="Mid-Market">Mid-Market</option>
    <option value="SMB">SMB</option>
    <option value="Developer">Developer</option>
    <option value="Legacy">Legacy</option>
    <option value="UCaaS">UCaaS</option>
  </select>
  <select id="intFilter" onchange="filter()">
    <option value="">All integration types</option>
    <option value="Native">Native / Deep</option>
    <option value="AppExchange">AppExchange</option>
    <option value="Open CTI">Open CTI / Custom</option>
    <option value="API">API / Custom Dev</option>
  </select>
  <span class="count" id="count">20 platforms</span>
</div>
<div class="tbl-wrap">
<table id="tbl">
<colgroup><col class="c1"><col class="c2"><col class="c3"><col class="c4"><col class="c5"><col class="c6"><col class="c7"><col class="c8"></colgroup>
<thead>
<tr>
  <th onclick="sortTable(0)">Platform</th>
  <th onclick="sortTable(1)">Tier</th>
  <th>Key Features</th>
  <th>Pricing</th>
  <th>Best For</th>
  <th>SF Integration</th>
  <th>Method</th>
  <th>Notes</th>
</tr>
</thead>
<tbody id="tbody"></tbody>
</table>
</div>
</div>

<script>
const data=[
  {
    name:"Genesys Cloud CX",tier:"Enterprise",
    features:["Omnichannel routing (voice, chat, email, SMS, social)","AI-powered IVR & predictive engagement","Workforce management & quality tools","Real-time & historical analytics","Journey orchestration"],
    pricing:"From $75/user/mo",pricingSub:"Scales to $240+/agent/mo",
    bestFor:"Large enterprise contact centers needing full omnichannel + WFM",
    sfInt:"Strong AppExchange","method":"AppExchange package + Open CTI",
    notes:"Salesforce CRM integration is a paid add-on, not included in base plan. One of the 'Big 3' enterprise CCaaS."
  },
  {
    name:"NICE CXone",tier:"Enterprise",
    features:["Enlighten AI (real-time sentiment, QA, coaching)","Omnichannel routing","Workforce engagement management","Advanced compliance tools","CXone Mpower AI suite"],
    pricing:"$110–$249/user/mo",pricingSub:"Voice-only to Ultimate Suite",
    bestFor:"Large enterprises with compliance-heavy environments (finance, healthcare)",
    sfInt:"Strong AppExchange",method:"AppExchange CTI adapter",
    notes:"Market leader in workforce engagement management. Deep Salesforce integration available. Often seen in large Service Cloud deals."
  },
  {
    name:"Cisco (Webex CC)",tier:"Enterprise",
    features:["Omnichannel routing","AI-powered agent assist","Webex Calling & Meetings integration","Workforce optimization","Global PSTN coverage"],
    pricing:"$12/user/month starting, Free version available",pricingSub:"Custom quotes for Enterprise",
    bestFor:"Orgs already on Cisco infrastructure or Microsoft-heavy environments",
    sfInt:"Strong AppExchange",method:"AppExchange CTI adapter",
    notes:"Pricing is fully opaque. High implementation complexity. Best when Cisco ecosystem is already in place."
  },
  {
    name:"Avaya",tier:"Enterprise",
    features:["Two products: Cloud Office (UCaaS) & Infinity Platform (enterprise)","Omnichannel voice, video, chat, SMS","AI analytics & workforce optimization","Hybrid/on-premise deployment support","Global scale"],
    pricing:"Custom quote only",pricingSub:"Both Cloud Office & Infinity Platform",
    bestFor:"Large orgs needing hybrid cloud + on-premise deployment flexibility",
    sfInt:"AppExchange",method:"AppExchange CTI adapter",
    notes:"Legacy giant transitioning to cloud. Infinity Platform suits complex enterprise; Cloud Office suits mid-market modernization."
  },
  {
    name:"Five9",tier:"Enterprise",
    features:["Predictive, progressive & power dialers","Intelligent Virtual Agent (IVA)","Agent Assist (real-time guidance)","Omnichannel (voice, email, chat, SMS, social)","Workforce management & quality tools"],
    pricing:"From $119/user/mo",pricingSub:"Digital plan. Core/Premium/Optimum/Ultimate: custom quote. 50-user minimum.",
    bestFor:"Mid-large contact centers with high outbound call volume or compliance needs",
    sfInt:"Strong AppExchange",method:"AppExchange CTI adapter + Open CTI",
    notes:"Strong dialer capability. Add-ons (IVA, Agent Assist, SMS) are extra cost. 50-user minimum limits SMB suitability."
  },
  {
    name:"Amazon Connect",tier:"Enterprise",
    features:["Serverless CCaaS, AWS-native pay-as-you-go model","Real-time transcription (Amazon Transcribe)","AI/ML via Amazon Lex (chatbots) & Comprehend","Salesforce Service Cloud Voice partner","Highly customizable via AWS Lambda"],
    pricing:"Pay-as-you-go",pricingSub:"Per minute + per chat + per feature. No seat license.",
    bestFor:"Salesforce Service Cloud Voice deployments; AWS-first orgs with dev resources",
    sfInt:"Native (Service Cloud Voice)",method:"Service Cloud Voice — Salesforce's preferred native partner",
    notes:"Salesforce's #1 preferred telephony partner for Service Cloud Voice. Cost unpredictable at scale without careful architecture. Requires developer involvement."
  },
  {
    name:"Talkdesk",tier:"Mid-Market",
    features:["Talkdesk Studio (no-code visual workflow builder)","Copilot (real-time agent guidance)","Autopilot (virtual agents — voice & digital)","Omnichannel CX platform","Salesforce AppExchange package"],
    pricing:"From $85/user/mo",pricingSub:"Scales to $225+/user/mo",
    bestFor:"Mid-market orgs wanting AI-native CC with faster deployment than legacy enterprise platforms",
    sfInt:"Strong AppExchange",method:"Dedicated Salesforce AppExchange package",
    notes:"One of the best Salesforce-native integrations in the mid-market tier. AI features are core, not add-ons. Faster to deploy than Genesys or NICE."
  },
  {
    name:"RingCentral",tier:"Mid-Market",
    features:["UCaaS + CCaaS in one platform","Unlimited US/Canada calling","Video conferencing & team messaging","AI assistant (real-time transcription, summaries)","RingCX contact center product"],
    pricing:"RingEX: $20–$35/user/mo (annual)",pricingSub:"RingCX (CCaaS): from $65/agent/mo",
    bestFor:"Orgs wanting UCaaS + CCaaS from a single vendor",
    sfInt:"Strong AppExchange",method:"AppExchange package — Salesforce integration on Advanced plan+",
    notes:"Salesforce integration requires Advanced plan ($25/user/mo) or above. Contact center (RingCX) is a separate product/cost."
  },
  {
    name:"8x8",tier:"Mid-Market",
    features:["Combined UCaaS + CCaaS platform","Omnichannel routing","Workforce engagement management","Global PSTN (55+ countries)","Microsoft Teams certified","AI self-service"],
    pricing:"Custom quote",pricingSub:"~$18K–$55K/year per 100 users (negotiated)",
    bestFor:"International orgs needing global PSTN coverage with unified comms + CC",
    sfInt:"Strong AppExchange",method:"AppExchange package",
    notes:"Best global footprint in the mid-market. Pricing is not published — always requires a quote. Strong leverage in negotiations at quarter-end."
  },
  {
    name:"Dialpad",tier:"Mid-Market",
    features:["AI transcription & sentiment analysis on every call","Real-time call coaching","UCaaS + contact center in one platform","Unlimited US/Canada calling","Salesforce AppExchange integration"],
    pricing:"From $15/user/mo (annual)",pricingSub:"Higher tiers: custom quote",
    bestFor:"AI-forward mid-market sales/support teams wanting native transcription & coaching",
    sfInt:"Strong AppExchange",method:"AppExchange package",
    notes:"Best AI-to-price ratio in the mid-market tier. AI features are included by default, not add-ons. Popular with inside sales teams on Salesforce."
  },
  {
    name:"Vonage",tier:"Mid-Market",
    features:["Salesforce-native Contact Center (formerly NewVoiceMedia)","UCaaS: voice, SMS, file sharing","API customization (CPaaS layer)","Click-to-dial & screen pop in Salesforce","Call recording & activity logging"],
    pricing:"UCaaS: $13.99–$27.99/line/mo (annual)",pricingSub:"Contact Center: custom quote",
    bestFor:"Orgs wanting a Salesforce-native contact center with minimal custom development",
    sfInt:"Native / Deep",method:"Built natively on Salesforce; lives inside Salesforce UI",
    notes:"Formerly NewVoiceMedia — acquired by Vonage specifically for Salesforce integration. Strong choice when Salesforce is the core system of record."
  },
  {
    name:"Aircall",tier:"SMB",
    features:["Click-to-dial & screen pop","Call recording & voicemail drop","Power dialer","100+ native integrations","Call whisper/monitor/barge","Salesforce integration (Professional plan+)"],
    pricing:"Essentials: $30/license/mo",pricingSub:"Professional: $50/license/mo (annual). 3-license minimum. Enterprise: custom (25+ licenses).",
    bestFor:"SMB/mid-market inside sales teams using Salesforce for pipeline management",
    sfInt:"Strong AppExchange",method:"AppExchange package — available on Professional plan",
    notes:"Salesforce integration only on Professional ($50/mo) or above. 3-license minimum. AI features are paid add-ons ($9–$15/user/mo extra)."
  },
  {
    name:"CloudTalk",tier:"SMB",
    features:["Advanced call routing & IVR","Power dialer & parallel dialer","Real-time analytics & dashboards","Call recording","Salesforce integration (Expert plan)","140+ country coverage"],
    pricing:"From $25/user/mo (annual)",pricingSub:"Expert plan (with Salesforce): $49/user/mo",
    bestFor:"SMB/mid-market contact centers with high international call volume",
    sfInt:"AppExchange",method:"AppExchange package — Expert plan only",
    notes:"Salesforce integration is locked to the Expert plan ($49/mo). Strong international calling capability. Good analytics for the price point."
  },
  {
    name:"Ringover",tier:"SMB",
    features:["Unlimited calling to 110+ destinations","IVR & smart call routing","Auto-dialer & predictive dialer (higher tiers)","AI transcription (included on Smart plan)","90+ CRM integrations","Salesforce integration (Business plan+)"],
    pricing:"Smart: $24/user/mo",pricingSub:"Contact: $44/user/mo | Advanced: $54/user/mo (annual)",
    bestFor:"SMBs wanting affordable unlimited international calling with Salesforce integration",
    sfInt:"AppExchange",method:"AppExchange package — Business plan and above",
    notes:"Best price-to-AI ratio for SMBs. No seat minimum. Salesforce integration not available on the cheapest Smart plan."
  },
  {
    name:"Freshdesk Contact Center",tier:"SMB",
    features:["Smart IVR & call routing","Call recording","Pay-as-you-go call charges","Freshworks ecosystem integration","Salesforce integration","Agent availability management","Free plan available"],
    pricing:"From $15/user/mo",pricingSub:"Free plan available with limited features. Pay-as-you-go call charges apply.",
    bestFor:"Small teams already in the Freshworks ecosystem needing simple voice support",
    sfInt:"AppExchange",method:"AppExchange integration",
    notes:"Part of the Freshworks suite (Freshdesk, Freshsales). Best when client uses Freshdesk for ticketing. Limited for complex contact center needs."
  },
  {
    name:"Zendesk Talk",tier:"SMB",
    features:["Built into Zendesk Suite (not standalone)","Inbound call management & IVR","Automatic ticket creation from calls","Voicemail-to-ticket","Call recording","Zendesk Answer Bot AI"],
    pricing:"Bundled with Zendesk Suite",pricingSub:"Suite plans from ~$15–$50+/user/mo",
    bestFor:"Teams already using Zendesk for ticketing who need voice embedded in the same workspace",
    sfInt:"Limited",method:"Minimal — Zendesk and Salesforce overlap in function; rarely co-deployed",
    notes:"Not a standalone phone system. Rarely seen alongside Salesforce as they compete as CRM/service platforms. Best for Zendesk-native support teams."
  },
  {
    name:"Twilio (Flex)",tier:"Developer",
    features:["Fully programmable contact center platform","Omnichannel APIs (voice, SMS, chat, WhatsApp, video)","Custom Salesforce integration via Open CTI","Unlimited customization","Usage-based pricing model","5,000 free trial hours"],
    pricing:"Start for free. Then pay as you go.",pricingSub:"Free trial: 5,000 active user hours.",
    bestFor:"Orgs with strong dev teams needing a fully custom-built contact center experience",
    sfInt:"Open CTI / Custom",method:"Open CTI + custom Salesforce integration via Twilio APIs",
    notes:"Maximum flexibility but requires developer resources for everything. Per-hour pricing suits variable/seasonal demand. $150 flat suits predictable usage."
  },
  {
    name:"3CX",tier:"Legacy",
    features:["PBX system (on-prem, cloud, or hybrid)","VoIP calling & video conferencing","Live chat & web meeting","Salesforce integration via Open CTI/connector","Mobile & desktop apps","Low per-seat cost"],
    pricing:"Free (small deployments)",pricingSub:"Annual license per installation — significantly cheaper than SaaS CCaaS",
    bestFor:"Cost-conscious clients wanting basic calling without SaaS subscription costs",
    sfInt:"Open CTI / Custom",method:"Open CTI via third-party connectors or custom CTI adapter",
    notes:"PBX, not a true CCaaS. Integration requires more effort than AppExchange solutions. Common in SMB clients resistant to SaaS pricing."
  },
  {
    name:"Mitel",tier:"Legacy",
    features:["UCaaS/PBX hybrid (on-prem or cloud)","Voice & video calling","Contact center capabilities","Salesforce integration via Open CTI/middleware","Strong in regulated industries","Large installed base"],
    pricing:"Custom quote",pricingSub:"Negotiated per deployment size and model",
    bestFor:"Orgs with existing Mitel infrastructure looking to modernize gradually",
    sfInt:"Open CTI / Custom",method:"Open CTI via third-party middleware connector",
    notes:"Common in orgs migrating from legacy PBX. Integration requires middleware. Not ideal for greenfield Salesforce implementations."
  },
  {
    name:"Zoom Phone / CC",tier:"UCaaS",
    features:["Extends Zoom Meetings into calling","Video-first contact center (Zoom CC)","Click-to-dial & call recording","Salesforce AppExchange integration","Familiar Zoom UI","Metered or unlimited calling plans"],
    pricing:"Zoom Phone: from $10/user/mo (metered)",pricingSub:"Unlimited plans priced higher. Zoom CC: public pricing available.",
    bestFor:"Orgs already on Zoom for meetings wanting to extend to calling without switching vendors",
    sfInt:"Strong AppExchange",method:"AppExchange package",
    notes:"Fastest growing in mid-market. Leverage is familiarity — minimal user adoption friction. Contact center product is newer and less mature than pure-play CCaaS."
  }
];

const tierClass={Enterprise:"tier-ent","Mid-Market":"tier-mid",SMB:"tier-smb",Developer:"tier-dev",Legacy:"tier-leg",UCaaS:"tier-uc"};
const intClass={"Native / Deep":"int-native","Strong AppExchange":"int-strong","AppExchange":"int-strong","Open CTI / Custom":"int-api","Limited":"int-mid"};

let sortCol=-1,sortDir=1;

function renderRows(rows){
  const tb=document.getElementById('tbody');
  tb.innerHTML='';
  rows.forEach(r=>{
    const tr=document.createElement('tr');
    const ic=intClass[r.sfInt]||'int-mid';
    tr.innerHTML=`
      <td><span class="name">${r.name}</span></td>
      <td><span class="badge ${tierClass[r.tier]||''}">${r.tier}</span></td>
      <td><ul class="features-list">${r.features.map(f=>`<li>${f}</li>`).join('')}</ul></td>
      <td><div class="price-main">${r.pricing}</div><div class="price-sub">${r.pricingSub}</div></td>
      <td style="font-size:11px;color:var(--color-text-primary)">${r.bestFor}</td>
      <td><span class="badge ${ic}">${r.sfInt}</span></td>
      <td style="font-size:11px;color:var(--color-text-primary)">${r.method}</td>
      <td class="note">${r.notes}</td>
    `;
    tb.appendChild(tr);
  });
  document.getElementById('count').textContent=`${rows.length} platform${rows.length!==1?'s':''}`;
}

function filter(){
  const q=document.getElementById('search').value.toLowerCase();
  const t=document.getElementById('tierFilter').value;
  const i=document.getElementById('intFilter').value;
  const rows=data.filter(r=>{
    const txt=(r.name+r.tier+r.features.join(' ')+r.pricing+r.pricingSub+r.bestFor+r.sfInt+r.method+r.notes).toLowerCase();
    const matchQ=!q||txt.includes(q);
    const matchT=!t||r.tier===t;
    const matchI=!i||r.sfInt.includes(i)||r.method.includes(i);
    return matchQ&&matchT&&matchI;
  });
  renderRows(rows);
}

function sortTable(col){
  const th=document.querySelectorAll('th');
  th.forEach((h,i)=>{h.classList.remove('sort-asc','sort-desc')});
  if(sortCol===col)sortDir*=-1; else{sortCol=col;sortDir=1;}
  th[col].classList.add(sortDir===1?'sort-asc':'sort-desc');
  const keys=['name','tier'];
  const q=document.getElementById('search').value.toLowerCase();
  const t=document.getElementById('tierFilter').value;
  const i=document.getElementById('intFilter').value;
  const rows=data.filter(r=>{
    const txt=(r.name+r.tier+r.features.join(' ')+r.pricing+r.bestFor+r.sfInt+r.method+r.notes).toLowerCase();
    return(!q||txt.includes(q))&&(!t||r.tier===t)&&(!i||r.sfInt.includes(i)||r.method.includes(i));
  }).sort((a,b)=>{
    const av=(keys[col]&&a[keys[col]])||a.name;
    const bv=(keys[col]&&b[keys[col]])||b.name;
    return av.localeCompare(bv)*sortDir;
  });
  renderRows(rows);
}

renderRows(data);
</script>
