---
layout: page
title: Rewilding seed microbiomes
description: Bringing beneficial microbes from wild wheat relatives back to domesticated crops. TÜBİTAK 2232-A funded, starting 2027.
img: assets/img/rewilding_seed_microbiomes.jpg
importance: 1
category: research
related_publications: false # references are listed at the bottom of this page, newest first
---

<style>
  .rw-meta { display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 0 0 1.5rem; }
  .rw-pill { display: inline-flex; align-items: center; gap: 0.4rem; padding: 0.3rem 0.85rem; border-radius: 999px; font-size: 0.9rem; border: 1px solid var(--global-divider-color); }
  .rw-pill.rw-accent { background: var(--global-theme-color); border-color: var(--global-theme-color); color: var(--global-bg-color); font-weight: 600; }
  .rw-aims { counter-reset: aim; list-style: none; padding-left: 0; }
  .rw-aims li { counter-increment: aim; position: relative; padding-left: 2.4rem; margin-bottom: 0.9rem; }
  .rw-aims li::before { content: counter(aim); position: absolute; left: 0; top: 0; width: 1.7rem; height: 1.7rem; border-radius: 50%; background: var(--global-theme-color); color: var(--global-bg-color); font-weight: 700; font-size: 0.9rem; display: flex; align-items: center; justify-content: center; }
  .rw-phases { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1rem; margin: 1rem 0 1.5rem; }
  .rw-phase { border: 1px solid var(--global-divider-color); border-top: 4px solid var(--global-theme-color); border-radius: 6px; padding: 1rem 1.2rem; }
  .rw-phase h4 { margin-top: 0; margin-bottom: 0.2rem; }
  .rw-phase .rw-when { font-size: 0.85rem; color: var(--global-text-color-light); margin-bottom: 0.6rem; }
  .rw-phase ul { padding-left: 1.1rem; margin-bottom: 0; }
  .rw-species { display: grid; grid-template-columns: 1fr 1fr; gap: 0.5rem 1rem; margin: 0.5rem 0 1.5rem; }
  .rw-species div { padding: 0.6rem 0.8rem; border-radius: 6px; border: 1px solid var(--global-divider-color); font-size: 0.95rem; }
  .rw-species .rw-label { font-size: 0.75rem; text-transform: uppercase; letter-spacing: 0.04em; color: var(--global-text-color-light); display: block; }
  .rw-join { margin-top: 2rem; padding: 1rem 1.2rem; border-left: 4px solid var(--global-theme-color); border-radius: 4px; background: var(--global-card-bg-color, var(--global-bg-color)); }
  @media (max-width: 480px) { .rw-species { grid-template-columns: 1fr; } }
</style>

<div class="rw-meta">
  <span class="rw-pill rw-accent"><i class="fa-solid fa-award"></i> TÜBİTAK 2232-A</span>
  <span class="rw-pill"><i class="fa-solid fa-calendar"></i> Starting 2027</span>
  <span class="rw-pill"><i class="fa-solid fa-location-dot"></i> Boğaziçi University, Istanbul</span>
</div>

Plant seeds are not sterile. They carry diverse microbial communities that colonise the seedling as soon as it germinates, and these **seed-borne microbiomes** strongly influence plant health. Because they arrive first, seed-borne microbes have a head start over microbes picked up from the soil, and they can pass beneficial functions from one plant generation to the next. This makes seeds an attractive route for **microbiome engineering**: introducing synthetic microbial communities (SynComs) via seeds to steer crops towards healthier, more sustainable growth with fewer chemical inputs.

## What did domestication cost us?

Crop domestication, through strong selection, hybridisation and polyploidisation, caused major losses of genetic diversity and often brought unfavourable traits along with the desirable ones. These changes likely reshaped the immune-related proteins that plants use to interact with microbes, with knock-on effects on how microbial communities assemble and on beneficial symbioses.

Modern cultivars often gain less from arbuscular mycorrhizal fungi, rhizobia and other growth-promoting microbes, and their root microbiomes differ consistently from those of wild relatives, including a reduced biocontrol potential in wheat. Domestication also seems to limit the transmission of microbes from seed to seedling. Wild crop relatives may therefore still hold beneficial microbial partnerships that modern crops have lost {% cite hassani2019metaorganisms %}. Seeds offer a practical way to bring them back. Yet we still know very little about which genomic and functional traits allow an introduced microbe to colonise a seedling {% cite soluch2021pantoea %}, persist across generations, and interact with the plant's native microbiome.

## Aims

This project aims to **rewild and engineer seed microbiomes** using microbes from wild relatives of Fertile Crescent crops, rebuilding ancestral, potentially beneficial partnerships between domesticated plants and their seed-borne microbes to improve symbiosis, plant health and yield.


<div class="rw-join">
  <strong>Interested in joining this project?</strong> See the <a href="{{ '/positions/' | relative_url }}">open positions</a> page or get in touch.
</div>

<h2>References</h2>
<div class="publications">
{% bibliography --cited --group_by none %}
</div>
