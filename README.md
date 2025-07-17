
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>ICS3U Career Exploration: Programming → Software Developer (University of Waterloo Path)</title>
<meta name="description" content="ICS3U Careers Assignment interactive mini‑site: Programming career (Software Developer / Programmer, NOC 21232) with University of Waterloo Computer Science pathway." />
<style>
:root {
  --uw-gold: #ffd54f;
  --uw-black: #000;
  --uw-grey: #f5f5f5;
  --uw-blue: #00bcd4;
  --uw-dark: #1c1c1c;
  --radius-lg: 16px;
  --trans-fast: 0.15s;
  --max-width: 1100px;
  --font-body: system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  --font-head: var(--font-body);
}
html,body{margin:0;padding:0;font-family:var(--font-body);line-height:1.5;}html{min-height:100%;}body{min-height:100vh;background:var(--uw-grey);color:#111;}body.dark{background:var(--uw-dark);color:#eee;}

.hidden{display:none!important}
header{background:var(--uw-blue);color:#fff;padding:1rem;position:sticky;top:0;z-index:1000;}
header h1{margin:0;font-size:1.25rem;line-height:1.2;}
nav{margin-top:.5rem;display:flex;flex-wrap:wrap;gap:.5rem;}
nav button{background:rgba(255,255,255,.15);color:#fff;border:1px solid rgba(255,255,255,.3);padding:.4rem .8rem;font-size:.9rem;border-radius:var(--radius-lg);cursor:pointer;transition:background var(--trans-fast),transform var(--trans-fast);} 
nav button:hover,nav button:focus{background:rgba(255,255,255,.3);transform:translateY(-1px);} 
nav button.active{background:var(--uw-gold);color:#000;}
#darkToggle{margin-left:auto;background:var(--uw-black)!important;color:#fff!important;border-color:#000!important;}
main{max-width:var(--max-width);margin:0 auto;padding:1.5rem;}
section{margin-bottom:3rem;padding:1.5rem;background:#fff;border-radius:var(--radius-lg);box-shadow:0 1px 3px rgba(0,0,0,.08);} 
body.dark section{background:#2c2c2c;box-shadow:0 1px 3px rgba(0,0,0,.6);} 
section h2{margin-top:0;font-family:var(--font-head);}
.grid-two{display:grid;grid-template-columns:1fr 1fr;gap:1.25rem;}@media(max-width:700px){.grid-two{grid-template-columns:1fr}}
.callout{border-left:6px solid var(--uw-blue);padding-left:1rem;margin:1rem 0;background:rgba(0,188,212,.15);}
body.dark .callout{background:rgba(255,255,255,.1);}
.tag{display:inline-block;padding:.15rem .5rem;font-size:.75rem;border-radius:8px;background:var(--uw-gold);color:#000;margin-right:.25rem;margin-bottom:.25rem;}
.table-scroll{overflow-x:auto;}
table{width:100%;border-collapse:collapse;font-size:.95rem;}
th,td{border:1px solid #ccc;padding:.5rem;text-align:left;}
body.dark th,body.dark td{border-color:#555;}
progress{width:100%;height:1.25rem;}
.salary-range{display:flex;align-items:center;gap:1rem;flex-wrap:wrap;margin:1rem 0;}
.salary-range input[type=range]{flex:1;min-width:200px;}
.salary-cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1rem;margin-top:1rem;}
.salary-card{padding:1rem;border-radius:var(--radius-lg);background:rgba(0,0,0,.05);}
body.dark .salary-card{background:rgba(255,255,255,.1);} 
.salary-card h4{margin:.25rem 0;}
.badge{display:inline-block;padding:.1rem .4rem;font-size:.7rem;border-radius:4px;background:var(--uw-blue);color:#fff;margin-left:.25rem;}
details{margin:.75rem 0;padding:.75rem;border:1px solid #ccc;border-radius:var(--radius-lg);}body.dark details{border-color:#555;}
details[open]{background:rgba(0,0,0,.03);}body.dark details[open]{background:rgba(255,255,255,.08);}
summary{cursor:pointer;font-weight:600;}
.timeline{position:relative;padding-left:1.5rem;margin:1.5rem 0;}
.timeline::before{content:"";position:absolute;left:.5rem;top:0;bottom:0;width:4px;background:var(--uw-blue);} 
.timeline-step{position:relative;margin-bottom:1.25rem;padding-left:1.5rem;}
.timeline-step::before{content:"";position:absolute;left:-1.05rem;top:.2rem;width:1.25rem;height:1.25rem;border-radius:50%;background:var(--uw-gold);border:2px solid var(--uw-blue);} 
footer{max-width:var(--max-width);margin:0 auto 4rem auto;padding:0 1.5rem;color:#666;font-size:.85rem;}
body.dark footer{color:#bbb;}
.source-list{font-size:.85rem;line-height:1.35;}
.source-list li{margin-bottom:.5rem;}
.smallcaps{font-variant:small-caps;}
.badge-outlook{background:var(--uw-gold);color:#000;padding:.2rem .5rem;font-size:.75rem;border-radius:4px;font-weight:700;}
.flex-tags{display:flex;flex-wrap:wrap;gap:.25rem;}
.hero{display:flex;align-items:center;justify-content:center;flex-direction:column;text-align:center;padding:3rem 1rem;background:linear-gradient(135deg,var(--uw-blue),#00838f);color:#fff;border-radius:var(--radius-lg);margin-bottom:2rem;}
.hero h2{font-size:clamp(1.75rem,3vw,2.5rem);margin:.25rem 0;}
.hero p{max-width:600px}
.btn{display:inline-block;padding:.6rem 1.1rem;font-size:1rem;border-radius:var(--radius-lg);border:none;cursor:pointer;background:var(--uw-gold);color:#000;font-weight:600;}
.btn:focus,.btn:hover{filter:brightness(1.05);} 
#goStartBtn{margin-top:1.25rem;}
.code-block{font-family:monospace;font-size:.85rem;background:rgba(0,0,0,.08);padding:1rem;border-radius:var(--radius-lg);overflow-x:auto;}
.source-list{font-size:.95rem;line-height:1.35;margin:0;padding:0;list-style:none;} .source-list li{margin:0 0 1rem 0;padding-left:2em;text-indent:-2em;} /* Print styles */
@media print{header,nav,#darkToggle,#goStartBtn{display:none!important}body{background:#fff;color:#000;}section{page-break-inside:avoid;box-shadow:none;border:1px solid #ccc;}a:after{content:" (" attr(href) ")";font-size:.8em;color:#555}}
</style>
</head>
<body>
<header>
  <h1>ICS3U Career Exploration – Programming → Software Developer<br><span style="font-size:.85em;font-weight:400">Pathway Spotlight: University of Waterloo Computer Science</span></h1>
  <nav aria-label="Main Navigation">
    <button class="active" data-target="home">Home</button>
    <button data-target="career">Career Profile</button>
    <button data-target="market">Labour Market & Salary</button>
    <button data-target="path">Waterloo Path</button>
    <button data-target="fit">Is This For Me?</button>
    <button data-target="sources">Sources</button>
    <button id="darkToggle" title="Toggle dark mode">🌙</button>
  </nav>
</header>
<main>
  <section id="home" data-section>
    <div class="hero">
      <h2>Welcome!</h2>
      <p>This interactive mini‑site completes the <strong>ICS3U Careers Assignment</strong>. It explores the <em>Programming</em> job category by focusing on the real‑world career of a <strong>Software Developer / Programmer (NOC 21232)</strong> and maps the pathway through the <strong>University of Waterloo Computer Science</strong> program.</p>
      <button id="goStartBtn" class="btn" data-target="career">Start Exploring →</button>
    </div>
    <h2>About This Project</h2>
    <p>This interactive mini‑site is my researched career exploration for <strong>ICS3U</strong>. It focuses on the <strong>Programming</strong> career area through the specific role of a <strong>Software Developer / Programmer (NOC 21232)</strong> and maps an academic pathway via the <strong>University of Waterloo Computer Science</strong> program. Inside you’ll find: a career overview, required education/training, labour‑market outlook, salary data, a personal fit reflection, program entrance requirements, first‑year course plan, degree structure, co‑op information, and full APA references.</p>
  </section>

  <section id="career" data-section class="hidden">
    <h2>Career Profile: Software Developer / Programmer (NOC 21232)</h2>
    <p>Software developers and programmers design, write, test, and maintain the code that powers applications, operating systems, games, embedded devices, and cloud platforms. They translate user needs and system requirements into working software using programming languages, development tools, and collaborative workflows such as version control and agile project management (Government of Canada, 2025).</p>
    <p>Common responsibilities include analyzing problems; designing algorithms and data structures; writing and debugging code; integrating software components; performing code reviews; testing and quality assurance; documenting solutions; and maintaining or upgrading existing systems. Developers work for software publishers, consulting firms, financial institutions, government, start‑ups, and in‑house IT teams across most industries (Government of Canada, 2024–2025; Government of Canada, 2025).</p>
    <h3>Education & Training</h3>
    <p>This occupation <strong>usually requires a university degree</strong> (bachelor’s or higher) in computer science, software engineering, or a related field. Alternate pathways include college diplomas with bridging, industry certifications, and self‑directed learning, but employers hiring for development roles frequently list degree‑level education as preferred (Government of Canada, 2025; University of Waterloo, 2025).</p>
    <h3>Core Technical Skill Tags</h3>
    <div class="flex-tags" id="skillTags">
      <span class="tag">Programming</span>
      <span class="tag">Algorithms</span>
      <span class="tag">Data Structures</span>
      <span class="tag">Databases (SQL)</span>
      <span class="tag">Version Control (Git)</span>
      <span class="tag">Testing / QA</span>
      <span class="tag">Cloud & Deployment</span>
      <span class="tag">Teamwork</span>
      <span class="tag">Problem Solving</span>
    </div>
    <h3>Where the Jobs Are</h3>
    <ul>
      <li>Computer systems design & related services</li>
      <li>Finance, insurance & fintech</li>
      <li>Information & cultural industries (software publishing, media, gaming)</li>
      <li>Public sector & health IT</li>
    </ul>
    <p>Sector mix varies by region; large tech and financial hubs (e.g., Greater Toronto Area) concentrate many roles, while local manufacturing and public‑sector IT drive demand in other regions (Government of Canada, 2024–2025; Government of Canada, 2025).</p>
  </section>

  <section id="market" data-section class="hidden">
    <h2>Labour Market & Salary</h2>
    <h3>Ontario Outlook (2024–2026)</h3>
    <p>The Government of Canada Job Bank projects a <span class="badge-outlook">Moderate</span> employment outlook for <em>Software developers and programmers</em> in Ontario for the <strong>2024‑2026</strong> period. Employment growth will create some new positions, and relatively few openings are expected from retirements (Government of Canada, 2024–2025).</p>
    <h3>Canada‑Wide Snapshot</h3>
    <p>Nationally, software developers and programmers show strong participation across provinces. The Job Bank reports a <strong>median wage of about $46.15/hour (~$96K/yr full‑time)</strong> and indicates that roles typically require university education (Government of Canada, 2025).</p>
    <details>
      <summary>Regional variation inside Ontario</summary>
      <p>Within Ontario, outlooks range from <em>good</em> in some regions (e.g., Stratford‑Bruce Peninsula) to <em>limited</em> in others (e.g., Northwest), with <em>moderate</em> projections for major centres including Toronto and Ottawa. Regional industrial mix and employer demand drive these differences (Government of Canada, 2024–2025).</p>
    </details>

    <h3>Career Progression (Typical Path)</h3>
    <div class="grid-two" style="--gap:1rem;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));">
      <div class="salary-card"><h4>Junior Developer</h4><p>0‑2 yrs. Focus on learning codebases, debugging, tickets, and mentorship.</p></div>
      <div class="salary-card"><h4>Intermediate Developer</h4><p>3‑5 yrs. Own features, design components, collaborate across teams.</p></div>
      <div class="salary-card"><h4>Senior / Lead</h4><p>6+ yrs. Architecture decisions, code reviews, mentoring, reliability.</p></div>
      <div class="salary-card"><h4>Beyond Coding</h4><p>Paths into Technical Lead, Engineering Manager, Product, Start‑up Founder.</p></div>
    </div>
    <p style="font-size:.85rem;margin-top:1rem;">Progression timelines vary by company and performance; strong fundamentals plus co‑op experience can accelerate early growth (Government of Canada, 2025; University of Waterloo, 2025).</p>
    <h3>Salary Explorer (Select Career Stage)</h3>
    <div class="salary-range">
      <label for="expLevel"><strong>Experience Level:</strong></label>
      <input type="range" id="expLevel" min="0" max="2" step="1" value="1" aria-label="Experience level slider" />
      <span id="expLabel">Intermediate</span>
    </div>
    <div class="salary-cards" aria-live="polite" id="salaryCards">
      <!-- populated by JS -->
    </div>
    <p style="font-size:.85rem;margin-top:1rem;">Salary data sources combine Government of Canada Job Bank wages, employee‑reported salary surveys (Indeed), job‑posting aggregates (ZipRecruiter), and tech‑company total compensation submissions (Levels.fyi) to show a realistic range across education levels and experience. Dates current to July 16, 2025 (Government of Canada, 2025; Indeed, 2025; ZipRecruiter, 2025; Levels.fyi, 2025).</p>
  </section>

  <section id="path" data-section class="hidden">
    <h2>Pathway: University of Waterloo Computer Science</h2>
    <p>The University of Waterloo’s Computer Science (regular or co‑op) program is housed in the Cheriton School of Computer Science within the Faculty of Mathematics. Admission is competitive (individual selection typically in the <strong>low‑to‑mid 90s</strong> range) and requires strong Grade 12 math preparation (University of Waterloo, 2025; OUInfo, 2025).</p>
    <h3>Entrance Requirements (Ontario High School)</h3>
    <div class="table-scroll">
      <table aria-describedby="entranceReqNote">
        <thead><tr><th>Requirement</th><th>Details</th></tr></thead>
        <tbody>
          <tr><td>OSSD + 6 Grade 12 U/M courses</td><td>Includes all required courses listed below.</td></tr>
          <tr><td>Advanced Functions (MHF4U)</td><td>Required.</td></tr>
          <tr><td>Calculus &amp; Vectors (MCV4U)</td><td>Required.</td></tr>
          <tr><td>Any Grade 12 U English</td><td>ENG4U or equivalent (EAE4U accepted).</td></tr>
          <tr><td>One additional 4U course</td><td>Counts in top six average.</td></tr>
          <tr><td>Recommended CS Background</td><td>ICS3U recommended preparation.</td></tr>
          <tr><td>Admission Information Form (AIF)</td><td>Required for all Faculty of Mathematics programs (incl. CS).</td></tr>
        </tbody>
      </table>
    </div>
    <p id="entranceReqNote" class="callout">Meeting minimums does not guarantee admission; Waterloo uses holistic review including grades, the AIF, and sometimes contest participation (University of Waterloo, 2025; OUInfo, 2025).</p>

    <h3>First‑Year Course Plan</h3>
    <div class="grid-two">
      <div>
        <h4>1A Term (Fall)</h4>
        <ul>
          <li>CS 115 <em>Intro to CS 1</em> <strong>or</strong> CS 135 <em>Designing Functional Programs</em></li>
          <li>MATH 135 Algebra</li>
          <li>MATH 137 Calculus 1</li>
          <li>Communication course</li>
          <li>Elective</li>
        </ul>
      </div>
      <div>
        <h4>1B Term (Winter)</h4>
        <ul>
          <li>CS 116 <em>Intro to CS 2</em> <strong>or</strong> CS 136 <em>Algorithm Design & Data Abstraction</em> + CS 136L <em>Software Dev Tools</em></li>
          <li>MATH 136 Linear Algebra 1</li>
          <li>MATH 138 Calculus 2</li>
          <li>Two electives</li>
        </ul>
      </div>
    </div>
    <p>Advanced ("enriched") streams (CS 145, advanced algebra/calculus) are available for highly prepared students (Cheriton School of Computer Science, 2025).</p>

    <h3>Program Length & Degree Requirements</h3>
    <p>The Bachelor of Computer Science (regular) typically takes four years; the co‑op program extends the calendar time (often ~5 years) because students alternate academic terms with paid work placements. Degree completion requires CS &amp; Math core courses, breadth/communication electives, and successful completion of co‑op work terms if enrolled in co‑op (University of Waterloo, 2025).</p>
    <ul>
      <li><strong>CS & Math Core:</strong> Sequential CS programming + algorithms courses; calculus, algebra, linear algebra foundation through upper years.</li>
      <li><strong>Breadth / Communication:</strong> Non‑Math communication and breadth electives required for graduation.</li>
      <li><strong>Minimum Averages:</strong> Students must maintain required major and overall averages to remain in good standing and progress (see CS academic regulations).</li>
      <li><strong>Work‑Integrated Learning:</strong> If enrolled in co‑op, complete 4–6 paid work terms plus associated professional development (PD) courses & work reports.</li>
      <li><strong>Time to Complete:</strong> Regular ~4 yrs; Co‑op sequence usually ~5 yrs due to alternating work/school terms.</li>
    </ul>
    <h3>Co‑op: Earn While You Learn</h3>
    <p>Waterloo operates <strong>North America’s largest co‑op (paid internship) program</strong>. Students alternate four‑month school terms with four‑month full‑time paid work terms, building up to ~2 years of experience before graduation. Co‑op roles include software development, data engineering, product, game dev, and research across Canada and globally (University of Waterloo, 2025).</p>

    <h3>Preparation Timeline (You → Waterloo CS)</h3>
    <div class="timeline">
      <div class="timeline-step"><strong>Grade 10‑11:</strong> Take math prerequisites; enroll in ICS3U to build coding basics; join coding clubs &amp; contests (University of Waterloo, 2025).</div>
      <div class="timeline-step"><strong>Grade 12 Fall:</strong> Enroll in MHF4U &amp; MCV4U; complete ENG4U; maintain high 90‑ish average; begin Waterloo application (OUAC) (University of Waterloo, 2025; OUInfo, 2025).</div>
      <div class="timeline-step"><strong>Grade 12 Winter:</strong> Submit Admission Information Form (AIF); optionally write Canadian Computing Competition / Euclid Math Contest to strengthen file (University of Waterloo, 2025).</div>
      <div class="timeline-step"><strong>Offer Window (Jan–May):</strong> Waterloo releases conditional offers as grades update; maintain averages (OUInfo, 2025).</div>
      <div class="timeline-step"><strong>1A @ Waterloo:</strong> Start CS 135 + Math core; build foundation for software development career (Cheriton School of Computer Science, 2025).</div>
      <div class="timeline-step"><strong>1B + First Co‑op:</strong> Move into CS 136L tools; apply coding skills in paid industry job (Cheriton School of Computer Science, 2025; University of Waterloo, 2025).</div>
    </div>
  </section>

  <section id="fit" data-section class="hidden">
    <h2>Is Software Development a Good Fit For Me?</h2>
    <p>Below is my personal reflection on whether I (<span class="smallcaps">Krish Modi</span>) would pursue Software Development after studying Computer Science at Waterloo.</p>
    <details open>
      <summary>Reasons I <strong>would</strong> pursue this career</summary>
      <ul>
        <li>I (<strong>Krish Modi</strong>) am actively learning HTML in class and teaching myself more outside class because I'm passionate about coding and building software.</li>
        <li>I've already started building real projects (e.g., e‑commerce shipping plug‑in, AI/automation tools), so a CS degree would let me scale those skills into production‑grade software.</li>
        <li>High demand across industries; skills stay portable (remote work possible) (Government of Canada, 2024–2025; Government of Canada, 2025).</li>
        <li>Strong earning potential with growth from junior to senior roles (Indeed, 2025; ZipRecruiter, 2025).</li>
        <li>The Waterloo / GTA tech ecosystem is a great <em>tech community fit</em> for me, and Waterloo’s co‑op lets me test different sectors (start‑ups, finance, big tech) before committing (University of Waterloo, 2025).</li>
      </ul>
    </details>
    <details>
      <summary>Reasons I <strong>might not</strong> pursue this career</summary>
      <ul>
        <li>Admission to top CS programs is highly competitive; requires sustained high averages and extra application work (AIF, contests) (University of Waterloo, 2025; OUInfo, 2025).</li>
        <li>Rapidly changing technologies demand ongoing upskilling; developers must continually learn new tools and languages (Government of Canada, 2025).</li>
        <li>Workload spikes (deadlines, production issues) can create stress and long hours in some sectors (Government of Canada, 2024–2025).</li>
      </ul>
    </details>
  </section>

  <section id="sources" data-section class="hidden">
    <h2>References (APA)</h2>
    <ul class="source-list">
      <li>Applying and admissions | Cheriton School of Computer Science | University of Waterloo. (2024, July 4). <em>Uwaterloo.ca</em>. https://cs.uwaterloo.ca/future-undergraduate-students/applying-admissions</li>
      <li>Canada, E. and S. D. (n.d.). <em>Software Developer in Ontario | Job prospects - Job Bank</em>. <em>Www.jobbank.gc.ca</em>. https://www.jobbank.gc.ca/marketreport/outlook-occupation/22548/ON</li>
      <li>Developer. (2025). <em>ZipRecruiter</em>. https://www.ziprecruiter.com/Salaries/Developer-Salary--in-Ontario</li>
      <li>Dog, B. (2025). <em>Computer Science (Regular/Co-op) – OUInfo</em>. <em>Ouinfo.ca</em>. https://www.ouinfo.ca/programs/waterloo/wcs</li>
      <li>First-year students | Cheriton School of Computer Science | University of Waterloo. (2024, October). <em>Uwaterloo.ca</em>. https://cs.uwaterloo.ca/current-undergraduate-students/majors/first-year-students</li>
      <li>Junior software engineer salary in Ontario. (2025). <em>Indeed.com</em>. https://ca.indeed.com/career/junior-software-engineer/salaries/Ontario</li>
      <li>Salary: Software Engineers in Ontario (May, 2024). (n.d.). <em>ZipRecruiter</em>. https://www.ziprecruiter.com/Salaries/Software-Engineers-Salary--in-Ontario</li>
      <li>Senior software engineer salary in Ontario. (2025). <em>Indeed.com</em>. https://ca.indeed.com/career/senior-software-engineer/salaries/Ontario</li>
      <li>Software Developer in Canada | Labour Market Facts and Figures. (n.d.). <em>Www.jobbank.gc.ca</em>. https://www.jobbank.gc.ca/marketreport/summary-occupation/22548/ca</li>
      <li>Software Engineer salary in Ontario. (n.d.). <em>Ca.indeed.com</em>. https://ca.indeed.com/career/software-engineer/salaries/Ontario</li>
      <li>Software Engineer Salary in Toronto, Canada. (n.d.). <em>Levels.fyi</em>. https://www.levels.fyi/t/software-engineer/locations/greater-toronto-area</li>
      <li>University of Waterloo. (2013, February 26). <em>Co-op</em>. Undergraduate Programs. https://uwaterloo.ca/future-students/co-op</li>
      <li>University of Waterloo. (2019, February 13). <em>Computer Science</em>. University of Waterloo. https://uwaterloo.ca/future-students/programs/computer-science</li>
    </ul>
    <p style="font-size:.85rem;">Accessed July 16, 2025.</p>
  </section>
</main>
<footer>
  <p style="text-align:center;">&copy; 2025 Krish Modi – ICS3U Programming Career Exploration (Software Developer → University of Waterloo CS).</p>
</footer>

<script>
/** Simple SPA navigation **/
const navButtons = document.querySelectorAll('nav button[data-target]');
const sections = document.querySelectorAll('section[data-section]');
function showSection(id){
  sections.forEach(sec=>{sec.id===id?sec.classList.remove('hidden'):sec.classList.add('hidden');});
  navButtons.forEach(btn=>{btn.dataset.target===id?btn.classList.add('active'):btn.classList.remove('active');});
  // scroll to top of main when changing
  window.scrollTo({top:0,behavior:'smooth'});
}
navButtons.forEach(btn=>btn.addEventListener('click',()=>showSection(btn.dataset.target)));
// hero start button
const goStartBtn=document.getElementById('goStartBtn');
if(goStartBtn){goStartBtn.addEventListener('click',()=>showSection(goStartBtn.dataset.target));}

/** Dark mode toggle **/
const darkToggle=document.getElementById('darkToggle');
darkToggle.addEventListener('click',()=>{document.body.classList.toggle('dark');darkToggle.textContent=document.body.classList.contains('dark')?'☀️':'🌙';});

/** Salary Explorer **/
const expLevel=document.getElementById('expLevel');
const expLabel=document.getElementById('expLabel');
const salaryCardsEl=document.getElementById('salaryCards');
const salaryData={
  0:{label:'Junior',
     notes:'0‑2 yrs experience; internships / new grads',
     rows:[
       {src:'Indeed (Junior)',amt:62245,cite:'turn3view0'},
       {src:'Job Bank median (hr→yr est.)',amt:96192,cite:'turn1view1'},
       {src:'ZipRecruiter Entry‑Level Dev avg',amt:60261,cite:'turn3view2'}]},
  1:{label:'Intermediate',
     notes:'~3‑5 yrs; common Ontario posting range',
     rows:[
       {src:'Indeed (All levels avg)',amt:99858,cite:'turn1view6'},
       {src:'ZipRecruiter (All levels avg)',amt:128591,cite:'turn1view7'},
       {src:'Levels.fyi Median Total Comp (GTA)',amt:137096,cite:'turn1view8'}]},
  2:{label:'Senior',
     notes:'6+ yrs; specialized / lead roles',
     rows:[
       {src:'Indeed (Senior)',amt:131807,cite:'turn3view1'},
       {src:'ZipRecruiter 75th%',amt:140000,cite:'turn1view7'},
       {src:'Levels.fyi 75th% (GTA)',amt:182000,cite:'turn1view8'}]}
};
function renderSalaryCards(level){
  const d=salaryData[level];
  expLabel.textContent=d.label;
  salaryCardsEl.innerHTML='';
  d.rows.forEach(r=>{
    const div=document.createElement('div');
    div.className='salary-card';
    div.innerHTML=`<h4>${r.src}</h4><div style="font-size:1.5rem;font-weight:700;">$${r.amt.toLocaleString('en-CA')}</div><div class="badge">${d.label}</div>`;
    salaryCardsEl.appendChild(div);
  });
  const note=document.createElement('div');
  note.style.fontSize='.85rem';
  note.style.gridColumn='1/-1';
  note.textContent=d.notes;
  salaryCardsEl.appendChild(note);
}
renderSalaryCards(expLevel.value);
expLevel.addEventListener('input',e=>renderSalaryCards(e.target.value));
</script>
</body>
</html>

