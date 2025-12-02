---
layout: custom
title: ""
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
</style>


<div class="bio-container" id="home-bio">
  <div class="bio-text">
    <p>Hi! I am a PhD candidate in the Department of Government at Harvard University. I study institutions, elections, and party behavior, with a focus on climate change. Most of my current research is on the United States but I also study Europe, and in particular, how electoral system design affects how parties address 'new' issues in Europe. In a more applied body of work, I conduct research to establish policy evidence relevant to the energy transition. I also use experimental methods to study voter engagement and strategic campaign messaging.</p>

    <p>I am currently a Graduate Fellow at the <a href="https://www.iq.harvard.edu/about">Institute for Quantitative Social Science</a> (IQSS), the <a href="https://caps.gov.harvard.edu/">Center for American Political Studies</a> (CAPS), and the <a href="https://starlab.wcfia.harvard.edu/">Harvard STAR Lab</a>, and a Harvard <a href="https://salatainstitute.harvard.edu/">Salata Institute</a> Fellow. I am also part of a group of researchers committed to digitizing <a href="https://doi.org/10.1038/s41597-024-04017-1">Cast Vote Record data</a> in the United States, unlocking new research frontiers applicable to big questions in academia as well as real world campaign strategy.</p>

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

## Research

### Publications
Conevska, A., Hirano, S., Kuriwaki, S., Lewis, J. B., Mutlu, C., Snyder, J. M. (2025). **[How Partisan are U.S. Local Elections? Evidence from 2020 Cast Vote Records](https://doi.org/10.1017/S0003055425100920)**. _American Political Science Review._

Kuriwaki, S., Reece, M., Baltz, S. et al. (2024). **[Cast vote records: A database of ballots from the 2020 U.S. Election](https://doi.org/10.1038/s41597-024-04017-1)**. _Nature Scientific Data_, 11, 1304.

Conevska, A. (2021). **[International Cooperation and Natural Disasters: Evidence from Trade Agreements](https://doi.org/10.1093/isq/sqab065)**. _International Studies Quarterly_, 65(3), 606–619.

Mikkelson, G. M., Avidan, M., Conevska, A., and Etzion, D. (2021). **[Mutual reinforcement of academic reputation and fossil fuel divestment](https://doi.org/10.1017/sus.2021.19)**. _Global Sustainability_, 4.

Conevska, A., and Urpelainen, J. (2020). **[Seasonal Variation in Electricity Consumption Among Off-Grid Households: Evidence from Rural India](https://doi.org/10.1016/j.erss.2020.101444)**. _Energy Research & Social Science_, 65, 101444.

Conevska, A., Ford, J., and Lesnikowski, A. (2020). **[Assessing the adaptation fund’s responsiveness to developing country’s needs](https://doi.org/10.1080/17565529.2019.1638225)**. _Climate and Development_, 12(5), 436–447.

Conevska, A., Ford, J., Lesnikowski, A., and Harper, S. (2019). **[Adaptation financing for projects focused on food systems through the UNFCCC](https://doi.org/10.1080/14693062.2018.1466682)**. _Climate Policy_, 19(1), 43–58.

--



### Working Papers
**[When Do Voters Stop Caring? Estimating the Shape of Voters' Utility Functions](https://arxiv.org/abs/2501.03196)** (with Can Mutlu).  
_Revise &amp; Resubmit, American Political Science Review._

**Ideology, Party, and Split-Ticket Voting** (with Shigeo Hirano,  Can Mutlu,  James M. Snyder,  Jr.). 
_Revise &amp; Resubmit, American Political Science Review._

**When Are Parties ‘Good’ For The Environment?**  
(with Can Mutlu)

**Polluting Politicians: Import Shocks and Environmental Outcomes**  
(with Sean Nossek)

</div>


</section>
