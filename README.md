<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e3a5f,100:2563eb&height=6" width="100%"/>

<div align="center">

# Collective `Artificial` Intelligence Initiative

**Nicholas Coles & Shanting Chen — University of Florida**

*What is the upper bound of what machine learning can predict about human health and cognition?*

*We're running a mass collaboration to find out.*

<br/>

![](https://img.shields.io/badge/up_to_$10,000_in_incentives-2563eb?style=flat-square)
![](https://img.shields.io/badge/co--authorship_for_top_performers-16a34a?style=flat-square)
![](https://img.shields.io/badge/public_leaderboard-d97706?style=flat-square)
![](https://img.shields.io/badge/applications_open_soon-dc2626?style=flat-square)

</div>

---

## The Challenge

Apply machine learning and statistical modeling to nearly 20,000 variables from the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/) — a nationally representative longitudinal survey of Americans over 50, with biennial interviews since 1992 — to predict cancer, mortality, cognitive functioning, and depressive symptoms on a common held-out test set. The goal is not to crown a winner. It is to establish an empirical ceiling on predictability for major health and cognitive outcomes: a field-level finding that no single lab could credibly produce alone.

#### Outcomes

- **Cancer** — cumulative ever-told diagnosis (binary)
- **Death** — mortality (binary; time-to-event)
- **Cognitive functioning** — Telephone Interview for Cognitive Status (TICS) score (continuous)
- **Depressive symptoms** — Center for Epidemiological Studies Depression (CES-D) scale (continuous)

#### Predictors

~19,870 predictor columns spanning ~350 constructs across 16 waves:

- **Demographics & background** — sex, race/ethnicity, birth cohort, education, parental education, religion, veteran status
- **Health behaviors & screening** — smoking, alcohol, physical activity, cancer screening, flu shot, dental/vision/hearing care, diabetes and stroke management
- **Healthcare utilization & insurance** — hospital, nursing home, doctor visits, home care, out-of-pocket costs, Medicare/Medicaid/VA coverage, premiums
- **Psychosocial** — loneliness, Big Five personality, positive/negative affect, domain satisfaction, perceived life problems, chronic stress
- **Expectations** — subjective survival probabilities, work expectations, bequest probabilities
- **Employment, retirement, & income** — labor force status, hours/weeks worked, occupation/industry, job demands, retirement, Social Security, SSDI, pensions, earnings, government transfers
- **Wealth** — net worth, financial wealth, stocks/bonds/CDs/IRAs, real estate, housing, debt
- **Family & social structure** — marriage history, household composition, living parents/siblings, number of children, spousal health
- **Interview metadata** — interview status, dates, proxy flag, mode indicators

All predictors are drawn from the publicly released RAND HRS Longitudinal File; no restricted-access data are required to participate.

---

## Why Join

- **Up to $10,000 in performance incentives** for participating teams.
- **Public performance leaderboard** — your model's accuracy is visible to the field. Compete, learn, and build a verifiable track record.
- **Co-authorship** on the results paper for top-performing teams.
- **Open to graduate students, postdocs, and faculty** affiliated with any US institution.

---

## This Model Has Worked Before

Mass collaboration challenges have driven breakthroughs across science, medicine, industry, and engineering. CAII adapts this proven model to social and health science.

| Field | Challenge | What It Unlocked |
|---|---|---|
| **Medicine** | [CASP](https://predictioncenter.org/) — protein structure prediction (1994–present) | Drove 30 years of progress; directly enabled AlphaFold and the 2024 Nobel Prize in Chemistry |
| **Physics** | [Higgs Boson ML Challenge](https://www.kaggle.com/c/higgs-boson) — particle signal classification from CERN collision data (2014) | 1,785 teams improved detection of the Higgs boson signal; demonstrated that open ML competitions can accelerate fundamental physics |
| **Engineering** | [ImageNet / ILSVRC](https://www.image-net.org/challenges/LSVRC/) — large-scale image classification | Sparked the deep learning revolution; AlexNet (2012) cut error rates in half |
| **Business** | [Netflix Prize](https://en.wikipedia.org/wiki/Netflix_Prize) — collaborative filtering for recommendation systems | $1M prize; transformed recommender system research |
| **Social science** | [Fragile Families Challenge](https://www.pnas.org/doi/10.1073/pnas.1915006117) — predicting child outcomes from survey data | Established empirical limits of ML for social prediction; 160 teams; published in *PNAS* |

---

## Challenge Design

The challenge follows the **Common Task Method** (Donoho, 2017; Salganik et al., 2020):

- All teams predict the **same outcomes** from the **same dataset**
- Evaluation is performed on a **held-out test set consisting of not-yet-publicly-released HRS data** — analogous to the Fragile Families Challenge, which used future follow-up waves as its test set. This eliminates any possibility of overfitting to publicly available data and makes the predictability ceiling a genuine prospective estimate
- All teams must submit **open-source code and a brief narrative** — results are reproducible and publicly verifiable
- **Benchmark models** (simple regression baselines) are pre-specified so results are interpretable regardless of how well any individual model performs

---

## Who We Are

**Nicholas Coles** is an Assistant Professor at the University of Florida and Director of the [Social Science Collaboratory](https://www.nicholas-a-coles.com/social-science-collaboratory). Before joining the University of Florida, he received his PhD from the University of Tennessee, completed a postdoctoral fellowship at Harvard University, and served as a research scientist at the Stanford Institute for Human-Centered AI. His work has been published in outlets like [*Nature*](https://www.nature.com/articles/d41586-022-00150-2), [*Nature Human Behaviour*](https://www.nature.com/articles/s41562-022-01458-9) and [*Science*](https://www.science.org/doi/10.1126/science.ado7070). These contributions have been recognized via several awards, including: the Einstein Foundation Award for Promoting Quality in Research, the CORES Open Science Innovator Award, and three fellowhips from the U.S National Science Foundation.

**Shanting Chen** is an Assistant Professor of Psychology at the University of Florida and director of the [Chen Lab](https://chenlab.psych.ufl.edu/). She holds a Ph.D. in Human Development and Family Sciences from UT Austin and completed her postdoctoral training at Northwestern University. Her research examines how socio-cultural and bio-behavioral factors — including sleep, cortisol, and allostatic load — shape health and development across the lifespan, with a focus on racial/ethnic minorities and social inequality. She is the recipient of a 5-year NIH/NIA K01 Career Development Award (2025) to develop machine learning methods for identifying robust measures of allostatic load and key risk and protective factors for chronic disease across adulthood, using the Add Health and Health and Retirement Study datasets. The CAII challenge is a direct extension of that program of research.

---

## How to Apply

Full details — including eligibility, application instructions, and timeline — are **TBD**.
