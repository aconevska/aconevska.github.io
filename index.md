---
layout: custom
title: "Aleksandra Conevska"
---

<style>
/* --- Home page tweaks --- */

/* 1) Make top bar links ("Research" and "CV") larger on the home page */
a[href="/#research"],
a[href="/research/"],
a[href^="/cv"] {
  font-size: 1.2rem;    
  font-weight: 500;
  letter-spacing: 0.01em;
  text-underline-offset: 0.15em;
}

/* 2) Tighten the gap below the link bar.
   Pulls the first content block upward 
   1 cm ≈ 38px; using 3rem ≈ 48px, use negative to pull up further */
#home-bio {
  margin-top: 0rem;    
}

/* on narrow screens, reduce the pull a bit for safety */
@media (max-width: 700px) {
  #home-bio { margin-top: -0.5rem; }
}

/* Make the Research section text column narrower, like the top bio text */
.research-text {
  max-width: 46rem;   /* try 36–40rem to taste */
  margin-left: 0;
  margin-right: auto; /* pushes extra space to the right */
}

@media (max-width: 800px) {
  .research-text {
    max-width: 100%;
  }
}

/* Click-to-expand abstracts; the toggle uses the site's link blue */
a.abstract-toggle {
  font-style: italic;
  white-space: nowrap;
  cursor: pointer;
}
div.abstract {
  margin: -0.6rem 0 1.25rem 0;
  line-height: 1.5;
}
div.abstract[hidden] {
  display: none;
}
</style>


<div class="bio-container" id="home-bio">
  <div class="bio-text">
    <p>Hi! I am a PhD candidate in the Department of Government at Harvard University. I am on the 2026–27 academic job market. </p>
      
     <p> I study institutions and interest group and party behavior, particularly in the context of climate change. I am particularly interested in how the design of institutions and electoral rules shape interest group, party, and voter behavior. In my more applied work, I use computational and experimental methods to understand strategic party and voter behavior, and to establish policy evidence relevant to the energy transition. I am also part of a group of researchers committed to digitizing <a href="https://doi.org/10.1038/s41597-024-04017-1">Cast Vote Record data</a> in the United States, unlocking new research frontiers applicable to big questions in academia as well as real world campaign strategy. </p>

    <p>I am currently a Graduate Fellow at the <a href="https://www.iq.harvard.edu/about">Institute for Quantitative Social Science</a> (IQSS) and the <a href="https://caps.gov.harvard.edu/">Center for American Political Studies</a> (CAPS), and a Harvard <a href="https://salatainstitute.harvard.edu/">Salata Institute</a> Fellow.</p>

    <p>Prior to Harvard, I was a Fulbright Scholar at Johns Hopkins University after earning a Bachelor of Arts and Science from McGill University with Joint Honours in Environmental Science and Political Science. I have also worked as a consultant for the World Bank Group, London Economics International, and Siemens. My research has been published in the <em>American Political Science Review</em>, <em>Nature Scientific Data</em>, <em>International Studies Quarterly</em>, and <em>Energy Research &amp; Social Science</em>.</p>
    
  </div>

  <div class="bio-photo">
    <img src="/assets/images/headshot2025_cropped.jpg" alt="Aleksandra Conevska" />

    <div class="is-container-row is-center is-inset-top-8 social-icons">
      <div class="is-inset-8">
        <a href="https://github.com/aconevska" class="is-icon" title="GitHub">
          <i class="fab fa-github fa-2x"></i>
        </a>
      </div>
      <div class="is-inset-8">
        <a href="https://x.com/aleksandracone" class="is-icon" title="Twitter">
          <i class="fab fa-twitter fa-2x"></i>
        </a>
      </div>
      <div class="is-inset-8">
        <a href="https://scholar.google.com/citations?user=9_02_o4AAAAJ&hl=en" class="is-icon" title="Google Scholar">
          <i class="ai ai-google-scholar ai-2x"></i>
        </a>
      </div>
      <div class="is-inset-8">
        <a href="https://www.linkedin.com/in/aleksandra-conevska/" class="is-icon" title="LinkedIn">
          <i class="fab fa-linkedin fa-2x"></i>
        </a>
      </div>
    </div>
  </div>
</div>

<!-- ========================= -->
<!-- Research section on home  -->
<!-- ========================= -->
<section id="research" class="bio-container" style="margin-top: 1rem;">
  <div class="bio-text research-text" markdown="1">



# Research


### Working Papers

[Ideology, Party, and Split-Ticket Voting](https://www.dropbox.com/scl/fi/e3g0hd3l2imdxrfii6dia/partisanship_ideology_and_voting.pdf?rlkey=r3jy4h8a8m48js2kgkare54jf&st=meogwrn2&dl=0) (with Shigeo Hirano, Can Mutlu, James M. Snyder, Jr.). <a href="#" class="abstract-toggle" data-target="abs-split" aria-expanded="false">[Abstract]</a>  
_Revise &amp; Resubmit, American Political Science Review._

<div class="abstract" id="abs-split" markdown="0" hidden>
This paper examines voting as a function of ideology and partisanship at the individual level, using cast vote record (CVR) data in 2020. The dataset covers over 50 million voters across 1400 national, state, and local races. We use statewide ballot measures to estimate each voter's ideological position, and partisan offices to measure partisanship. We find (i) ideological centrist voters are more likely to split their ticket than non-centrists; (ii) voters who split their tickets at one level of government are more likely to split their ticket at other levels; (iii) when ideological non-centrists swing towards one party's candidate in a given race, ideological centrists also swing towards that candidate; (iv) when strong party supporters swing towards one party's candidate in a given race, then weak party supporters also swing towards that candidate. We then investigate the relationship between split-ticket voting and measures of candidate valence, including incumbency, endorsements by newspapers and interest groups, scandals, and expert evaluations. We find that voting on the basis of candidate valence is more related to the strength of party support than to ideology. Voting on the basis of candidate ideology is related to both strength of party support and voter ideology. Voters who are weak party supporters and who do not share the ideology of the incumbent vote significantly more for more moderate incumbents. Overall, the results suggest that even today, centrists and weak party supporters can play a key role in U.S. elections.
</div>

Electoral Accountability and Industrial Change: Regulator Selection and Renewable Energy Growth <a href="#" class="abstract-toggle" data-target="abs-jmp" aria-expanded="false">[Abstract]</a>

<div class="abstract" id="abs-jmp" markdown="0" hidden>
Regulators play an important role in public policy and existing research indicates that their influence over outcomes depends on how they are selected, where elected regulators yield more consumer oriented policies. I study regulator selection in a more complex world that better characterizes economies today. Industrial change creates new interest group alliances so regulators no longer face clear pro-business incentives when appointed and pro-consumer when elected. Focusing on the electricity sector, I argue electoral accountability yields regulators who are less likely to promote renewable energy and provide evidence that in the US, elected regulators generate significantly less electricity from renewable sources. I argue this is because green interest groups are far more productive at lobbying than electoral campaigning, allowing them greater influence when regulators are insulated from voters. I analyze regulatory lobbying from 2000-2024 and show that green NGOs devote substantially more resources to lobbying than campaigning. Despite their grassroots nature, green NGOs behave more like what we might expect of classic corporate interests. My findings indicate that electoral accountability may not produce the best long-term outcomes for consumers when outcomes involve complex temporal trade offs. Consumer advocacy groups in turn shift away from citizens toward more insulated channels of influence.
</div>


When Do Voters Get to Decide on Climate? The Universe of Climate and Energy Ballot Measures in the United States (with Can Mutlu) <a href="#" class="abstract-toggle" data-target="abs-climate" aria-expanded="false">[Abstract]</a>

<div class="abstract" id="abs-climate" markdown="0" hidden>
A large literature documents what Americans say about climate change and energy policy, but we know far less about what they do when these questions are put to them directly. This paper assembles the first systematic record of climate- and energy-related direct democracy in the United States since 2000, covering statewide and local ballot questions at every level of government and every route to the ballot, from citizen initiatives and referenda to legislative referrals, required bond and tax votes, and advisory questions. We classify each measure by its policy goal, who bears its costs, its jurisdiction, how it reached the ballot, and whether it is binding, and we document how the set of questions put to voters has changed over time. Because no national register of local ballot measures exists, we build the universe state by state from official records where they exist and estimate what remains unobserved elsewhere. Moving beyond survey evidence, we then use precinct returns to measure actual support for these measures across two decades, asking how often the pro-climate side prevails, how closely support tracks partisanship, and where Democratic-leaning electorates defect. For measures decided since 2020, we use individual-level cast vote records to examine which of partisanship, its strength, geography, ideology, and voters' choices on the other questions on the same ballot best account for their votes on climate. The resulting dataset, which we will make public, provides a foundation for studying the politics of the energy transition through revealed rather than stated preferences.
</div>


A Tale of Top-Two Primaries: Electoral Design and Legislator Responsiveness to Climate Change <a href="#" class="abstract-toggle" data-target="abs-primary" aria-expanded="false">[Abstract]</a>

<div class="abstract" id="abs-primary" markdown="0" hidden>
How do electoral rules shape how responsive American legislators are to their constituents' climate change preferences? I study this question in California, which switched from a classic primary election to a top-two primary system in 2012. I argue that top two primary systems can dilute climate agendas through re-shaping party competition. The top two design makes it more difficult for third parties such as the Green party to compete, potentially reducing the pressure Democrats face competing candidates who are more progressive on the issue. I compare how closely legislators' climate-related roll-call votes track district-level climate related voter behavior before and after the reform. I rely on evidence from the universe of state and local climate related ballot measures to compare voter support for measures related to climate before and after with legislator behavior, which I measure with the League of Conservation Voters scores. I also compare California with Colorado which still holds traditional primaries. Overall, I offer new evidence on how the design of electoral systems can strengthen or weaken how well voters are represented on climate.
</div>


[Polluting Politicians? Import Shocks, Legislator Behavior, and Environmental Outcomes](https://www.dropbox.com/scl/fi/l3z5fbgtkh664gs6j9c6s/envr_chinshock_prelim.pdf?rlkey=zng8zmgq7vntjokhsfgaf5x45&dl=0) (with Sean Nossek) <a href="#" class="abstract-toggle" data-target="abs-polluting" aria-expanded="false">[Abstract]</a>

<div class="abstract" id="abs-polluting" markdown="0" hidden>
Do trade shocks affect the environment? We explore two implications of the &ldquo;China Shock&rdquo; that bring pressure to bear influence on environmental legislation; the effect of import penetration on exposed individuals whose preferences aggregate to influence legislators and the relative power of certain firms who lobby to have their interests reflected in relevant legislation. By exploiting China's accession to the WTO in 2001, and the marked increase in imports to the United States associated with it, we attempt to shed light on pathways from trade to attitudes, emissions, and environmental policy. We find that Commuting Zones (CZs) most exposed to import competition exhibit a substantial increase in their propensity to pollute, conditional on Republican political control. We further show that imports lead to an increase in voting for environmental legislation at the national level for jurisdictions with Democratic representation, an outcome we ascribe to the distributional consequences of import exposure, and the resultant changing balance of political influence. We also find tentative evidence that trade exposure decreases support for environmental protection at the individual level among Democrats.
</div>


--

### Publications

[When Do Voters Stop Caring? Estimating the Shape of Voters' Utility Functions](https://www.dropbox.com/scl/fi/rjh63qsvt3ny1yy1jl4kj/manuscript_accept.pdf?rlkey=ecyhap5xv6meq6mmjucsg8bkl&st=vwh46v31&dl=0) (with Can Mutlu). <a href="#" class="abstract-toggle" data-target="abs-utility" aria-expanded="false">[Abstract]</a>  
_Forthcoming, American Political Science Review._

<div class="abstract" id="abs-utility" markdown="0" hidden>
In this paper, we address a longstanding puzzle over the functional form that better approximates voter utility from political choices. Though it has become the norm in the literature to represent voter utility with concave loss functions, for decades scholars have underscored this assumption’s potential shortcomings. Yet there exists little to no evidence to support one functional form assumption over another. We fill this gap by first identifying electoral settings where the different functional forms generate divergent predictions over voters’ ballot choices. We then assess which functional form better matches observed voter behavior using Cast Vote Record (CVR) data that captures the anonymized ballots of millions of voters in the 2020 U.S. general elections. Contrary to the generally assumed concave loss functions, our findings indicate that voters’ utility functions exhibit convexity at the tails, suggesting that the convex and especially the reverse S-shaped functions better predict observed voter behavior.
</div>

Conevska, A., Hirano, S., Kuriwaki, S., Lewis, J. B., Mutlu, C., Snyder, J. M. (2026). [How Partisan are U.S. Local Elections? Evidence from 2020 Cast Vote Records](https://doi.org/10.1017/S0003055425100920). _American Political Science Review_, 120(2), 564-581.

Kuriwaki, S., Reece, M., Baltz, S. et al. (2024). [Cast vote records: A database of ballots from the 2020 U.S. Election](https://doi.org/10.1038/s41597-024-04017-1). _Nature Scientific Data_, 11, 1304.

Conevska, A. (2021). [International Cooperation and Natural Disasters: Evidence from Trade Agreements](https://doi.org/10.1093/isq/sqab065). _International Studies Quarterly_, 65(3), 606–619.

Mikkelson, G. M., Avidan, M., Conevska, A., and Etzion, D. (2021). [Mutual reinforcement of academic reputation and fossil fuel divestment](https://doi.org/10.1017/sus.2021.19). _Global Sustainability_, 4.

Conevska, A., and Urpelainen, J. (2020). [Seasonal Variation in Electricity Consumption Among Off-Grid Households: Evidence from Rural India](https://doi.org/10.1016/j.erss.2020.101444). _Energy Research & Social Science_, 65, 101444.

Conevska, A., Ford, J., and Lesnikowski, A. (2020). [Assessing the adaptation fund’s responsiveness to developing country’s needs](https://doi.org/10.1080/17565529.2019.1638225). _Climate and Development_, 12(5), 436–447.

Conevska, A., Ford, J., Lesnikowski, A., and Harper, S. (2019). [Adaptation financing for projects focused on food systems through the UNFCCC](https://doi.org/10.1080/14693062.2018.1466682). _Climate Policy_, 19(1), 43–58.

--

### Works in Progress

Where are the Liberal Republicans and Conservative Democrats? Measuring Local Political Space from Cast Vote Records (with Can Mutlu, Shigeo Hirano, and James Snyder)

Voting under Different Rules: How Electoral Institutions Shape Partisan and Ideological Voting (with Can Mutlu, Shigeo Hirano, and James Snyder)

When Are Parties ‘Good’ For The Environment? (with Can Mutlu)

</div>


</section>

<script>
  document.addEventListener('click', function (e) {
    var link = e.target.closest('a.abstract-toggle');
    if (!link) return;
    e.preventDefault();
    var box = document.getElementById(link.getAttribute('data-target'));
    var opening = box.hidden;
    box.hidden = !opening;
    link.setAttribute('aria-expanded', opening ? 'true' : 'false');
  });
</script>

