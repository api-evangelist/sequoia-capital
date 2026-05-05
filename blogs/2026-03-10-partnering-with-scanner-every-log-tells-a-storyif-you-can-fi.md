---
title: "Partnering with Scanner: Every Log Tells a Story—If You Can Find It Fast Enough"
url: "https://sequoiacap.com/article/partnering-with-scanner-every-log-tells-a-story-if-you-can-find-it-fast-enough/"
date: "Tue, 10 Mar 2026 17:00:04 +0000"
author: "sbarry"
feed_url: "https://sequoiacap.com/feed/"
---
<section class="wp-block-mg-hero-stack hero-stack"><h1 class="hero-stack__title">Partnering with Scanner: Every Log Tells a Story—If You Can Find It Fast Enough</h1><div class="hero-stack__paragraph"><p>Cliff and Steven are making petabytes of security data searchable in seconds, and opening the door to a new era of AI-driven security operations.</p></div><div class="hero-stack__credits"><div class="wp-block-mg-post-byline">
	By <a href="https://sequoiacap.com/people/bogomil-balkansky/">Bogomil Balkansky</a>	</div>


<time class="wp-block-mg-post-date" datetime="2026-03-10T10:00:04-07:00">
Published March 10, 2026</time>
</div></section>



<figure class="wp-block-image size-large is-style-plain-caption"><img alt="" class="wp-image-21757" height="681" src="https://sequoiacap.com/wp-content/uploads/sites/6/2026/03/Scanner_Founders_1.jpg?w=1024" width="1024" /><figcaption class="wp-element-caption">Steven and Cliff.</figcaption></figure>



<section class="wp-block-mg-post-container post-container wysiwyg has-global-padding is-layout-constrained wp-container-mg-post-container-is-layout-d839b035 wp-block-mg-post-container-is-layout-constrained">
<p class="has-drop-cap">A while back, I was deep in research on the next generation of security infrastructure, talking to CISOs and security engineers at some of the most technically sophisticated companies in Silicon Valley. I asked them all the same question I&#8217;d asked a decade earlier when I worked in enterprise software: What&#8217;s your biggest headache? The consistency of their answers surprised me. &#8220;We drown in logs we can&#8217;t afford to keep,&#8221; as one security leader put it, &#8220;and go blind on the logs we can&#8217;t afford to search.&#8221;</p>



<p>Enterprise security today is a story of impossible choices. The tools that teams rely on generate enormous amounts of log data—every API call, every login event, every network connection. To investigate cyber threats, they need all of it, often going back a year or more. But storing everything in a SIEM like Splunk is prohibitively expensive; costs could easily consume 15% of a CISO&#8217;s entire budget. Instead, companies make a compromise: they keep only the most recent 10 to 30 days of logs in their SIEM and park the rest in Amazon S3, where storage is cheap, but the data is effectively frozen. When a breach, a compliance audit, or a forensic investigation happens, security teams discover too late that the evidence they need is out of reach, opaque and unsearchable.&nbsp;</p>



<p>I first heard about Scanner from a member of the security team at <a href="http://temporal.io">Temporal</a>, one of our portfolio companies, who called it, “crazy fast.&#8221; I looked into it, and reached out to Cliff Crosland right away.</p>



<p>What Cliff and his co-founder Steven Wu have built is elegant in its insight. They asked: what would a log search engine look like if you designed it from scratch for object storage? The answer was a purpose-built inverted index that maps field values directly to file regions in S3. Rather than combing through billions of rows, Scanner narrows each query to only the relevant slices of data. A petabyte of logs becomes interactive. Queries that took hours now run in seconds. And a streaming detection engine runs hundreds of detection rules continuously across tens of terabytes a day, without re-scanning the world for each one.</p>



<p>Cliff and Steven are exactly the kind of founders we look for. Both Stanford CS alums, they were engineering leads together at Accompany (acquired by Cisco), where they built core data infrastructure under demanding, production-scale conditions. They have an obsession with performance that borders on the philosophical; they don’t tolerate systems that feel slow. And they have the expertise to build something better.</p>



<p>What’s most striking about Scanner isn’t the technology—though that is genuinely impressive. It’s the customers. The companies using Scanner today read like a who&#8217;s who of the cloud native world: Notion, Ramp, Benchling, Confluent, Lemonade, BeyondTrust. And they&#8217;re not just using it—they love it. Benchling replaced another product after a forced tenfold price increase, and their head of security engineering called it one of the best technical decisions their team had made. Ramp started with security logs and then expanded to application logs, reducing their SIEM bill in the process. Notion&#8217;s detection and response team built an internal AI agent that autonomously runs security investigations using Scanner.&nbsp;</p>



<p>That last example signals what’s to come. We are entering a new era of security operations, where AI agents will do much of the investigative work that today consumes hours of human time. But agents need to rapidly iterate, ask questions and follow threads; queries can’t take minutes, much less hours. Scanner&#8217;s speed is enabling these agentic security workflows across a wide range of companies: within weeks of their MCP release, nearly a third of Scanner&#8217;s customers were already using it in production, and agents now account for 80% of queries on the platform. That is not a prototype or a promising beta. That is the future arriving ahead of schedule.</p>



<p>Sequoia is proud to lead Scanner&#8217;s Series A, and we&#8217;re thrilled to partner with Cliff, Steven and their team as they work to transform a market overdue for reinvention. Scanner is winning hearts and minds among the most technically forward organizations today, and together, they will define the next decade of security infrastructure.</p>
</section>


<section class="social-sharing">
	<div class="social-sharing__container">
		<h2 class="social-sharing__title caption caption--16">Share</h2>
		<div class="social-sharing__options">
			<button class="ico--facebook">
				<span class="sr-only">
				Share this on Facebook				</span>
			</button>
			<button class="ico--twitter">
				<span class="sr-only">
				Share this on Twitter				</span>
			</button>
			<button class="ico--linkedin">
				<span class="sr-only">
				Share this on LinkedIn				</span>
			</button>
			<a class="ico--email" href="mailto:?subject=Partnering+with+Scanner:+Every+Log+Tells+a+Story—If+You+Can+Find+It+Fast+Enough&#038;body=https%3A%2F%2Fsequoiacap.com%2Farticle%2Fpartnering-with-scanner-every-log-tells-a-story-if-you-can-find-it-fast-enough%2F">
				<span class="sr-only">Share this via email</span>
			</a>
		</div>
	</div>
</section>


<div class="tags grid">
	<div class="grid__instances">
		<div class="grid__instance">
			<div class="tags__container grid__content">
				<h2 class="tags__title caption caption--16">Related Topics</h2>
				<div class="tags__links l-pillbox l-pillbox--centered">
					<a class="tag" href="https://sequoiacap.com/article/tag/ai/" style="background-color: #fab23a;">
	<span class="tag__name tag__name--dark">#AI</span>
</a>
<a class="tag" href="https://sequoiacap.com/article/tag/funding-announcement/" style="background-color: #fab23a;">
	<span class="tag__name tag__name--dark">#Funding announcement</span>
</a>
				</div>
			</div>
		</div>
	</div>
</div>


<div class="grid">
	<div class="grid__instances">
	<div class="grid__instance"><div class="grid__content"><a class="ink" href="https://sequoiacap.com/article/partnering-with-sandstone-an-ai-native-platform-for-in-house-legal-teams/?itm_medium=related-content&#038;itm_source=sequoiacap.com" style="background-color: #1f8ac4;"><div class="ink__content">
		<div class="ink__text">
		
<h2 class="ink__title">Partnering with Sandstone: An AI-Native Platform for In-House Legal Teams</h2>

	<div class="ink__detail">By Bogomil Balkansky</div>

<div class="ink__category ink__category--news">News</div>

<div class="ink__cta">Read</div>
	</div>
	</div>
</a></div></div><div class="grid__instance"><div class="grid__content"><a class="ink" href="https://sequoiacap.com/article/partnering-with-traversal-because-every-engineer-remembers-their-first-time-troubleshooting/?itm_medium=related-content&#038;itm_source=sequoiacap.com" style="background-color: #1b1916;"><div class="ink__content">
	<img alt="" class="ink__image" height="440" src="https://sequoiacap.com/wp-content/uploads/sites/6/2025/06/Ink_Traversal.jpg?w=440&amp;h=440&amp;crop=1" width="440" />	<div class="ink__text">
		
<h2 class="ink__title">Partnering with Traversal</h2>

	<div class="ink__detail">By Bogomil Balkansky and Charlie Curnin</div>

<div class="ink__category ink__category--news">News</div>

<div class="ink__cta">Read</div>
	</div>
	</div>
</a></div></div><div class="grid__instance"><div class="grid__content"><a class="ink" href="https://sequoiacap.com/article/partnering-with-fastapi-labs-simplified-app-deployment/?itm_medium=related-content&#038;itm_source=sequoiacap.com" style="background-color: #1b1916;"><div class="ink__content">
	<img alt="" class="ink__image" height="440" src="https://sequoiacap.com/wp-content/uploads/sites/6/2025/05/Fast-API-Labs_Ink.jpg?w=440&amp;h=440&amp;crop=1" width="440" />	<div class="ink__text">
		
<h2 class="ink__title">Partnering with FastAPI Labs: Simplified App Deployment </h2>

	<div class="ink__detail">By Bogomil Balkansky and Lauren Reeder</div>

<div class="ink__category ink__category--news">News</div>

<div class="ink__cta">Read</div>
	</div>
	</div>
</a></div></div><div class="grid__instance"><div class="grid__content"><a class="ink" href="https://sequoiacap.com/article/partnering-with-apex-security-the-ai-empowered-future-secured/?itm_medium=related-content&#038;itm_source=sequoiacap.com" style="background-color: #1b1916;"><div class="ink__content">
	<img alt="" class="ink__image" height="440" src="https://sequoiacap.com/wp-content/uploads/sites/6/2024/04/Ink_Apex-Portrait.jpg?w=440&amp;h=440&amp;crop=1" width="440" />	<div class="ink__text">
		
<h2 class="ink__title">Partnering with Apex Security: The AI-Empowered Future, Secured</h2>

	<div class="ink__detail">By Bogomil Balkansky</div>

<div class="ink__category ink__category--news">News</div>

<div class="ink__cta">Read</div>
	</div>
	</div>
</a></div></div>	</div>
</div>


<section class="wide-signup grid">
	<div class="grid__instances">
		<div class="grid__instance">
			<div class="grid__content grid__content--dark" style="background-color: transparent;">
				<div class="wide-signup__container">

					<div class="wide-signup__intro">
						JOIN OUR MAILING LIST					</div>

					<h1 class="wide-signup__title">
						Get the best stories from the Sequoia community.					</h1>

					
					
					<div class="wide-signup__form">
						
<!-- Mailchimp for WordPress v4.12.1 - https://wordpress.org/plugins/mailchimp-for-wp/ --><form class="mc4wp-form mc4wp-form-9292" id="mc4wp-form-3" method="post"><div class="mc4wp-form-fields"><div class="mailchimp__wrapper">
	<label class="mailchimp__label-input">
		<span class="sr-only">Email address</span>
		<input name="EMAIL" required="required" type="email" />
	</label>

	<input class="button--filled button--medium button--outline-dark" type="submit" value="Submit" />
</div></div><label style="display: none !important;">Leave this field empty if you&#8217;re human: <input autocomplete="off" name="_mc4wp_honeypot" tabindex="-1" type="text" value="" /></label><input name="_mc4wp_timestamp" type="hidden" value="1777850999" /><input name="_mc4wp_form_id" type="hidden" value="9292" /><input name="_mc4wp_form_element_id" type="hidden" value="mc4wp-form-3" /><div class="mc4wp-response"></div></form><!-- / Mailchimp for WordPress Plugin -->

					</div>

				</div>
			</div>
		</div>
	</div>
</section>
<p>The post <a href="https://sequoiacap.com/article/partnering-with-scanner-every-log-tells-a-story-if-you-can-find-it-fast-enough/">Partnering with Scanner: Every Log Tells a Story—If You Can Find It Fast Enough</a> appeared first on <a href="https://sequoiacap.com">Sequoia Capital</a>.</p>
