---
layout: default
title: Robert Thiesmeier
---

<button onclick="toggleLang()" style="margin-bottom: 20px; padding: 6px 14px; cursor: pointer;">🇩🇪 Deutsch</button>

<div id="en">

<h2>About me</h2>

I am a PhD student at the [Biostatistics Team](https://ki.se/en/gph/research/biostatistics-team)...


<h2>Research</h2>

My research interests lie at the intersection...


</div>

<div id="de" style="display:none;">

<h2>Über mich</h2>

Ich bin Doktorand im Biostatistik-Team...


<h2>Forschung</h2>

Meine Forschungsinteressen liegen...


</div>

<script>
function toggleLang() {
  var en = document.getElementById('en');
  var de = document.getElementById('de');
  var btn = document.querySelector('button');
  if (de.style.display === 'none') {
    de.style.display = 'block';
    en.style.display = 'none';
    btn.textContent = '🇬🇧 English';
  } else {
    de.style.display = 'none';
    en.style.display = 'block';
    btn.textContent = '🇩🇪 Deutsch';
  }
}
</script>

## Selected publications

For a full list of bibliography, see [here](https://scholar.google.com/citations?hl=de&user=ZYiVa1IAAAAJ).

### Methodological research 

**Thiesmeier** R, Haller PM, Patel SM, Bohula EM, Morrow DA, Murphy SA, O'Donoghue ML, Sabatine MS, Scirica BS, Bhatt DL, Orsini N, Bellavia A. [Statistical approaches for systematically missing covariates in individual participant data meta-analysis: insights and applications using 5 large cardiovascular trials](https://academic.oup.com/aje/advance-article/doi/10.1093/aje/kwaf226/8280162). American Journal of Epidemiology  

**Thiesmeier** R, Madley-Dowd P, Orsini N, Ahlqvist VA. [Cross-site imputation can recover missing variables in federated multicenter studies](https://www.sciencedirect.com/science/article/pii/S0895435625001532). Journal of Clinical Epidemiology

**Thiesmeier** R, Hofer SM, Orsini N. [Multiple imputation for systematically missing effect modifiers in individual participant data meta-analysis](https://journals.sagepub.com/doi/10.1177/09622802251348800). Statistical Methods in Medical Research

**Thiesmeier** R, Bottai M, Orsini N. [Imputing missing values with external data: Applications for multisite settings and federated analyses](https://journals.sagepub.com/doi/10.1177/1536867X251398605). The Stata Journal

### Educational research

**Thiesmeier** R, Orsini N. [Rolling the DICE (Design, Interpret, Compute, Estimate): Interactive Learning of Biostatistics With Simulations](https://mededu.jmir.org/2024/1/e52679/). JMIR Medical Education

**Thiesmeier** R, Orsini N, Gracely E, Oster B. [Teaching Statistics in Health Sciences: The Potential of Simulations in Public Health](https://www.tandfonline.com/doi/full/10.1080/09332480.2024.2348972). Chance

Orsini N, **Thiesmeier** R, Båge K. [A Simulation-Based Approach to Teach Interaction
Eﬀects in Postgraduate Biostatistics Courses](https://www.tandfonline.com/doi/pdf/10.1080/26939169.2024.2394536). Journal of Statistics and Data Science Education

### Medical and Population Health research

**Thiesmeier** R, Abbadi A, Rizzuto D, Calderón-Larrañaga A, Hofer SM, Orsini N. [Multiple imputation of systematically missing data on gait speed in the Swedish National Study on Aging and Care](https://www.aging-us.com/article/205552/text). Aging (Albany NY)

Shaaban A, Andersson F, **Thiesmeier** R, Orsini N, Peña S, Caspersen I, Magnusson C, Hergens M, Qazi B, Galanti R. [The association between tobacco use and COVID-19 diagnoses in three Nordic countries: a pooled analysis](https://academic.oup.com/eurpub/article/35/1/101/7825813). European Journal of Public Health

## Software
I am a proficient Stata user and use Stata for research, programming, and teaching. We recently published a Stata software package: 

[mi impute from](https://ideas.repec.org/c/boc/bocode/s459378.html), a package to impute binary, categorical, and continious variables from external data sources using logistic, multinomial logistic, and quantile regression, respectively.

## Teaching
- Karolinska Institutet - (Teaching Assistant & Lecturer): Biostatistics I (4FH083), Biostatistics II (4FH087), Biostatistics II: Logistic Regression for Epidemiologists (5314), Fundamentals of Stata (5315) (2022-)
- Summer School on Modern Methods in Biostatistics and Epidemiology - Introduction to Stata (2025-)

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<div style="margin-top: 40px; padding: 15px 0; border-top: 2px solid #e0e0e0;">
  <a href="mailto:robert.thiesmeier@ki.se" style="margin-right: 20px; text-decoration: none; color: #2c3e50; font-size: 15px;">
    <i class="fa fa-envelope" style="margin-right: 6px; color: #3498db;"></i>robert.thiesmeier@ki.se
  </a>
<a href="https://www.linkedin.com/in/robert-thiesmeier-207b60371/" target="_blank" style="text-decoration: none; color: #2c3e50; font-size: 15px;">
    <i class="fab fa-linkedin" style="margin-right: 6px; color: #0077b5;"></i>LinkedIn
  </a>
</div>



