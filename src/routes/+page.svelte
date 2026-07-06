<svelte:head>
	<title>QualityCall | Every call scored. Every score proven</title>
</svelte:head>
<header>
	<div class="wrap">
		<nav>
			<a class="brand" href="#top" aria-label="QualityCall home">
				<svg width="26" height="26" viewBox="0 0 26 26" fill="none" aria-hidden="true">
					<rect x="1" y="10" width="3" height="6" rx="1.5" fill="#0E5A63"/>
					<rect x="6" y="6" width="3" height="14" rx="1.5" fill="#0E5A63"/>
					<rect x="11" y="2" width="3" height="22" rx="1.5" fill="#E8A13D"/>
					<rect x="16" y="7" width="3" height="12" rx="1.5" fill="#0E5A63"/>
					<rect x="21" y="11" width="3" height="4" rx="1.5" fill="#0E5A63"/>
				</svg>
				QualityCall
			</a>
			<div class="nav-links">
				<a href="#offer">What we do</a>
				<a href="#how">How it works</a>
				<a href="#investors">Investors &amp; lenders</a>
				<a class="btn btn-solid nav-cta" href="#demo">Book a demo</a>
			</div>
		</nav>
	</div>
</header>

<main id="top">

	<!-- ============ HERO ============ -->
	<div class="hero">
		<div class="wrap hero-grid">
			<div>
				<span class="eyebrow">AI call quality analysis</span>
				<h1>Every call scored.<br><span class="proof">Every score proven.</span></h1>
				<p class="lede">QualityCall evaluates 100% of your customer service calls against your own quality checklist and cites the exact transcript evidence behind every score. No sampling. No guesswork. No unexplainable grades.</p>
				<div class="hero-ctas">
					<a class="btn btn-solid" href="#demo">Book a demo</a>
					<a class="btn btn-ghost" href="#investors">Investor overview</a>
				</div>
				<div class="hero-stats" role="list">
					<div class="stat" role="listitem"><div class="n">26</div><div class="l">metrics per call</div></div>
					<div class="stat" role="listitem"><div class="n">100%</div><div class="l">of calls reviewed, not 2%</div></div>
					<div class="stat" role="listitem"><div class="n">Minutes</div><div class="l">from call to coaching notes</div></div>
				</div>
			</div>

			<!-- Signature element: an evidence-cited scorecard -->
			<div class="call-card" aria-label="Example of an evidence-cited call score">
				<div class="call-head">
					<span><span class="dot" aria-hidden="true"></span>call_20260702_0417.wav</span>
					<span>SCORED · 26/26 METRICS</span>
				</div>
				<div class="transcript">
					<div class="tline"><span class="ts">00:04</span><span class="who">AGT</span><span>Thanks for calling, this is Maya. Who do I have the pleasure of speaking with?</span></div>
					<div class="tline cited"><span class="ts">00:12</span><span class="who">AGT</span><span>Before we start, can I confirm the last four digits on the account?</span></div>
					<div class="tline"><span class="ts">00:19</span><span class="who">CUS</span><span>Sure; 4471. I'm calling about a double charge on my invoice.</span></div>
					<div class="tline"><span class="ts">00:26</span><span class="who">AGT</span><span>I'm sorry about that! Let's get it sorted right now.</span></div>
				</div>
				<div class="metrics">
					<div class="chip"><span class="code">M03</span><span class="name">Identity verification</span><span class="ev">→ 00:12</span><span class="verdict pass">PASS</span></div>
					<div class="chip"><span class="code">M07</span><span class="name">Empathy statement</span><span class="ev">→ 00:26</span><span class="verdict pass">PASS</span></div>
					<div class="chip"><span class="code">M11</span><span class="name">Hold procedure</span><span class="ev">no hold</span><span class="verdict na">N/A</span></div>
					<div class="chip"><span class="code">M19</span><span class="name">Issue acknowledgment</span><span class="ev">→ 00:26</span><span class="verdict pass">PASS</span></div>
				</div>
			</div>
		</div>
	</div>

	<svg class="wave" viewBox="0 0 1200 44" preserveAspectRatio="none" aria-hidden="true">
		<path d="M0 22 Q 30 6, 60 22 T 120 22 T 180 22 T 240 22 T 300 22 T 360 22 T 420 22 T 480 22 T 540 22 T 600 22 T 660 22 T 720 22 T 780 22 T 840 22 T 900 22 T 960 22 T 1020 22 T 1080 22 T 1140 22 T 1200 22" stroke="currentColor" stroke-width="1.5" fill="none"/>
	</svg>

	<!-- ============ WHAT WE OFFER ============ -->
	<section id="offer">
		<div class="wrap">
			<div class="sec-head">
				<h2>QA that holds up to scrutiny</h2>
				<p>Most teams review a 2% sample of calls, days after they happen. QualityCall reviews everything, immediately; and shows its work on every line.</p>
			</div>
			<div class="offer-grid">
				<article class="offer">
					<span class="tag">Score</span>
					<h3>Your checklist, applied to every call</h3>
					<p>We evaluate each call against your 26-metric quality framework: greetings, verification, compliance language, resolution, closing, etc. With conditional metrics correctly marked N/A when they don't apply, never silently skipped.</p>
				</article>
				<article class="offer">
					<span class="tag">Prove</span>
					<h3>Evidence behind every grade</h3>
					<p>Every score links to the exact timestamp and transcript line that earned it. When an agent disputes a mark, you don't argue, you point. Built with anti-hallucination scaffolding so the system can never invent a justification.</p>
				</article>
				<article class="offer">
					<span class="tag">Coach</span>
					<h3>Training notes, written for you</h3>
					<p>Each evaluation generates plain-language coaching notes: what the agent did well, what to fix, and the specific moment in the call to review together. Team leads walk into 1:1s prepared, not scrambling.</p>
				</article>
			</div>
		</div>
	</section>

	<!-- ============ HOW IT WORKS ============ -->
	<section id="how" style="padding-top:0">
		<div class="how">
			<div class="how-inner">
				<div class="sec-head">
					<h2>From recording to coaching in three steps</h2>
					<p>No new phone system. No workflow overhaul. QualityCall fits around the tools you already use.</p>
				</div>
				<div class="steps">
					<div class="step">
						<span class="num">STEP 1</span>
						<h3>Connect your calls</h3>
						<p>Send recordings or transcripts from your existing phone platform. Batch uploads or automatic feeds, whichever suits your volume.</p>
					</div>
					<div class="step">
						<span class="num">STEP 2</span>
						<h3>We evaluate against your standard</h3>
						<p>Your quality checklist and reference material become the grading rubric. Every metric is scored with a cited justification from the transcript.</p>
					</div>
					<div class="step">
						<span class="num">STEP 3</span>
						<h3>Scorecards and coaching land on your desk</h3>
						<p>Dashboards for managers, evidence-linked scorecards for QA, and ready-to-use training notes for every agent conversation.</p>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- ============ INVESTORS & LENDERS ============ -->
	<section id="investors">
		<div class="wrap invest-grid">
			<div>
				<div class="sec-head" style="margin-bottom:28px">
					<h2>For investors &amp; lenders</h2>
					<p>QualityCall is a recurring-revenue software business in a market where the manual alternative, human QA teams sampling a sliver of calls, is slow, expensive, and doesn't scale.</p>
				</div>
				<div class="invest-points">
					<div class="ipoint">
						<span class="mark">01</span>
						<div>
							<h4>Recurring revenue, usage-aligned</h4>
							<p>Subscription pricing tied to call volume, so revenue grows with each customer's operation.</p>
						</div>
					</div>
					<div class="ipoint">
						<span class="mark">02</span>
						<div>
							<h4>A clear cost displacement story</h4>
							<p>Manual QA review costs multiples per call of automated evaluation and covers a fraction of the volume.</p>
						</div>
					</div>
					<div class="ipoint">
						<span class="mark">03</span>
						<div>
							<h4>Defensibility in the evidence layer</h4>
							<p>Auditable, transcript-cited scoring is what makes automated QA trustworthy enough to act on, and it's the hardest part to replicate.</p>
						</div>
					</div>
				</div>
			</div>
			<aside class="invest-card">
				<h3>Request the investor overview</h3>
				<p>We share a concise package with prospective investors and credit partners: business model, traction, unit economics, and roadmap. Tell us who you are and we'll send it directly.</p>
				<a class="btn btn-solid" href="mailto:invest@qualitycall.example?subject=Investor%20overview%20request">Request the overview</a>
				<a class="btn btn-ghost" href="mailto:invest@qualitycall.example?subject=Intro%20call">Book an intro call</a>
				<p class="fineprint" style="margin-top:14px">Shared under NDA on request · Not an offer of securities</p>
			</aside>
		</div>
	</section>

	<!-- ============ CTA ============ -->
	<section class="cta-band" id="demo" style="padding-top:20px">
		<div class="wrap">
			<h2>See your own calls scored</h2>
			<p>Send us five recordings. We'll return evidence-cited scorecards and coaching notes, then you decide.</p>
			<a class="btn btn-solid" href="mailto:hello@qualitycall.example?subject=Demo%20request">Book a demo</a>
		</div>
	</section>

</main>

<footer>
	<div class="wrap foot">
		<span>© 2026 QualityCall</span>
		<span style="display:flex;gap:22px">
			<a href="#offer">What we do</a>
			<a href="#investors">Investors &amp; lenders</a>
			<a href="mailto:hello@qualitycall.example">Contact</a>
		</span>
	</div>
</footer>
