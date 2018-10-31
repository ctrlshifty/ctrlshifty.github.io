---
layout: about
title: About
order: 1
object-id: about
---
<div class="about-section ">
<div class="about-content about-white-background">
<h1>What is CTRL+SHIFT?</h1>
<iframe src="https://www.google.com/maps/d/embed?mid=1g_5do2uHaVD7wxgKix-A6NEuy0M"  height="450" style="float:right;margin:0px 0px 10px 20px; width: 55%;" id="mymap"></iframe>
<h2>The Short Answer</h2>
<p>CTRL+Shift is an online collection of audio recordings, transcripts, process visualizations, and data analyses broken out from interviews conducted with 11 prominent contemporary American poets from across the United States. The project examines recent changes in writing practices that occurred due to the advent of the computer and the arrival of the digital age and investigates new modes of working with and publishing data from qualitative interview studies. Devin Becker conducted the interviews in 2013 and 2014 as part of a University of Idaho Seed Grant award. Becker collaborated with Corey Oglesby and Lauren Westerfield (both MFA candidates at the University of Idaho in the summer of 2017) to analyze and publish the data and findings online at CTRL+Shift.org.</p>
<img src="images/map.jpg" class="center" id="mappic">

</div>
</div>
<div class="about-section about-int">
<div class="about-content">
{% capture really %} {% include about/really.md %}{%endcapture %}
{{really | markdownify}}
</div>
</div>

<div class="about-section about-findings">
<div class="about-content">
<div class="peeps">
<h2>People</h2>

<p style="text-align:center;">
<img src="/images/portraits/devin.png"  style="height:220px;margin:auto;"/>
</p>
<p>
<a href="http://devinbecker.org">Devin Becker</a> is the director of the Center for Digital Inquiry and Learning (CDIL) and the Head of Data & Digital Services at the University of Idaho Library. In earlier research, Becker looked at the personal digital archiving practices of emerging writers in a <a href="https://doi.org/10.17723/aarc.75.2.t024180533382067">2012 American Archivist article</a>. His first collection of poetry, <a href="https://www.boaeditions.org/products/shame-shame">Shame | Shame</a>, was selected by David St. John as the winner of the thirteenth annual A. Poulin Jr. Poetry Prize and published by BOA Editions LTD in 2015.</p>

<p style="text-align:center;">
<img src="/images/portraits/corey.png" style="height:220px;margin:auto;" />
</p>
<p>
<a href="http://coreyoglesby.com">Corey Oglesby</a> is a poet, musician, and illustrator from the Washington, D.C., area. His work has recently appeared or is forthcoming in Barrow Street, DIAGRAM, Beloit Poetry Journal, Queen Mob’s Teahouse, and elsewhere. Currently the Editor-in-Chief of the literary journal Fugue, he earned his M.F.A. in Poetry at the University of Idaho, where he also helped run the Vandal Poem of the Day web project.
</p>
<p style="text-align:center;">
<img src="/images/portraits/lauren.png" style="height:220px;margin:auto;" />
</p>
<p>
<a href="http://www.laurenwesterfield.com/">Lauren Westerfield</a> is an essayist and poet from the Northern California coast. Her work has appeared or is forthcoming in DIAGRAM, Sonora Review, [PANK], Hobart, The Baltimore Review, Phoebe, Permafrost, Noble/Gas Quarterly, and The Rumpus, where she has also served as an Assistant Essays Editor. Lauren received an MFA in Creative Nonfiction from the University of Idaho, where she was a Centrum Fellow, earned Honorable Mention for the Academy of American Poets Prize, and was nominated for Best New Poets 2018.
</p>
<br>
<hr>
<br>
</div>
<div class="meth">
{% capture collab %} {% include about/collaboration.md %}{%endcapture %}
{{collab | markdownify}}
<br/><br/>
<hr />
<br/><br/>
{% capture tech %} {% include about/tech.md %}{%endcapture %}
{{tech | markdownify}}
</div>
</div>
</div>

 <div class="about-section about-process">
 <div class="about-content not-so-wide">
{% capture other %} {% include about/other.md %}{%endcapture %}
{{other | markdownify}}

</div>
</div>


