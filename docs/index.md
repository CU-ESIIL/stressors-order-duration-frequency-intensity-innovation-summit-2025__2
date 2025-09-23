# Stressors: Order, Duration, Frequency & Intensity — Innovation Summit 2025 (Group 2)

<p style="text-align: right;"><a href="https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/edit/main/docs/index.md" title="Edit this page">✏️</a></p>

<!-- =========================================================
HERO (Swap hero.jpg, title, strapline, and the three links)
========================================================= -->

![Wide banner of the study system](assets/hero.jpg)
[Raw photo location: hero.jpg](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/hero.jpg)

**One sentence on impact:** In 3 days we will prototype decision-ready visuals that show how the order, duration, frequency, and intensity of watershed stressors stack up for Colorado headwaters.

**[Project brief (PDF)](assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdfa) · [View shared code](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/code/prism_quicklook.py) · [Data & access](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/code/prism_quicklook.py)**

> **About this site:** This public log captures our Innovation Summit sprint. Update it directly in GitHub (open a file → ✏️ → Commit changes) so the homepage always reflects the latest thinking.

---

## How to use this page (for the team)
- **Edit this file:** `docs/index.md` → ✎ → change text → **Commit changes**.
- **Add images:** upload to `docs/assets/` and reference like `assets/your_file.png`.
- Keep **text short** and **visuals first**. Think “slide captions,” not essays.

---

## Day 1 — Define & Explore
*Focus: questions, hypotheses, context; add at least one visual (photo of whiteboard/notes).*

### Our product(s) 📣
- A decision-ready briefing with layered visuals that explain how stressor sequences escalate risk in two pilot watersheds.
- Short term: 
  - Identify our response!
  - Two graphs illustrating the effects of disturbance
  - Code for processing datasets to 1) identify tipping points from the datasets, and 2) calculate disturbacne severity, order, frequency, duration (SOFD)from datasets.
  - Graph of Landfire filtered vegetaiton or region of choice
- Long term: 
  - Paper! Providing a case study of tipping point drivers in one sample system (forests?)
  - Grant proposal!

### Our question(s) 📣
- How does the SOFD of fire, drought, and development stressors influence ecosystem recovery windows?
- Where do short, intense stress clusters lead to the greatest community or ecological vulnerability?
- LT Who needs this information first (agency partners, community groups, funders) to take action?

### Hypotheses / intentions [Optional: probably not relevant if you are creating an educational tool]
- We think that the spacing between stressors is as important as their intensity for predicting recovery needs.
- We intend to test whether compact clusters of high-intensity events correlate with regime shifts? .


### Why this matters (the “upshot”) 📣
Colorado resource managers need fast, visual explanations of how multiple stressors overlap. By translating the order, duration,
frequency, and intensity of those events into a simple story, we can point to interventions that reduce risk for people and
ecosystems.

### Inspirations (papers, datasets, tools)
- Publication: [IPCC AR6 — Impacts, Adaptation and Vulnerability](https://www.ipcc.ch/report/ar6/wg2/)
- Dataset portal: [USGS Water Data for the Nation](https://waterdata.usgs.gov/nwis)
- Tool/tech: [NOAA Climate Explorer](https://crt-climate-explorer.nemac.org/)

### Field notes / visuals
<!-- EDIT: Replace with a real smartphone photo or sketch; keep filename simple. -->
![Whiteboard brainstorm (replace this)](assets/day1_whiteboard.jpg)
[Raw photo location: day1_whiteboard.jpg](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/day1_whiteboard.jpg)
*Caption: What this shows and why it’s useful today.*

> **Different perspectives:** Briefly capture disagreements or alternate framings. These can unlock innovation.
[emergency management triggers]
> - We will know we’re onto something if we can visualize at least two contrasting stressor sequences with clear decision cues.
---

## Day 2 — Data & Methods
*Focus: what we’re testing and building; show a first visual (plot/map/screenshot/GIF).*

### Data sources we’re exploring 📣
- **USGS WaterWatch streamflow anomalies** — daily discharge for candidate Colorado headwaters basins.

  ![Streamflow departures from normal](assets/explore_data_plot.png)
  [Raw photo location: explore_data_plot.png](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/explore_data_plot.png)
  *Snapshot showing initial flow departures during drought periods.*

- **NOAA Hazard Mapping System fire detections** — identifying recent burn perimeters that precede hydrologic stress.

### Methods / technologies we’re testing 📣
- Sequence analysis of multi-hazard timelines (fire → drought → flood).
- Change point detection on 7-day rolling anomalies to surface stress clusters.
- Interactive story map prototypes that layer time, intensity, and affected communities.

### Challenges identified
- Aligning spatial footprints between hydrologic gauges, fire perimeters, and community boundaries.
- Limited overlap in temporal resolution between hazard products (daily vs. sub-daily events).
- Deciding which stressor combinations best illustrate contrasting management decisions.

### Visuals
<!-- EDIT: Swap examples; keep file sizes modest. -->
#### Static figure
![Sequence of stressors for the Poudre River pilot basin](assets/figure1.png)
[Raw photo location: figure1.png](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/figure1.png)
*Figure 1.* Prototype layout showing how fire and drought events cascade toward debris-flow risk.

#### Animated change (GIF)
![Seasonal shifts in stress intensity](assets/change.gif)
[Raw photo location: change.gif](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/change.gif)
*Figure 2.* Animated comparison of seasonal intensity clusters; helps illustrate recovery windows.

#### Interactive map (iframe)
<iframe
  title="Study area (OpenStreetMap)"
  src="https://www.openstreetmap.org/export/embed.html?bbox=-105.35%2C39.90%2C-105.10%2C40.10&layer=mapnik&marker=40.000%2C-105.225"
  width="100%" height="360" frameborder="0"></iframe>
<p><a href="https://www.openstreetmap.org/?mlat=40.000&mlon=-105.225#map=12/40.0000/-105.2250">Open full map</a></p>

> If an embed doesn’t load, put the normal link directly under it.

---

## Final Share Out — Insights & Sharing 
*Focus: synthesis; highlight 2–3 visuals that tell the story; keep text crisp. Practice a 2-minute walkthrough of the homepage 📣: Why → Questions → Data/Methods → Findings → Next.*

![Team photo at start of Day 3](assets/team_photo.jpg)
[Raw photo location: team_photo.jpg](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/team_photo.jpg)

### Findings at a glance 📣
- Streamflow recovery times lengthen by >30% when drought follows wildfire within a single season.
- Communities downstream of paired fire–flood sequences experience 2x the sediment pulses relative to single-stressor years.
- Prioritizing mitigation on basins with clustered stress scores could reduce emergency deployments by up to one event per year.

### Visuals that tell the story 📣
<!-- EDIT: Swap visuals; prioritize clarity. -->
![Lead conclusion visual placeholder](assets/fire_hull.png)
[Raw photo location: fire_hull.png](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/fire_hull.png)
*Visual 1.* Storyboard of stressor order and timing alongside management-ready interpretation panels.

![Supporting panels for key insights](assets/hull_panels.png)
[Raw photo location: hull_panels.png](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/hull_panels.png)
*Visual 2.* Supporting panels highlighting contrasting basins and community touchpoints.

![Complementary result figure placeholder](assets/main_result.png)
[Raw photo location: main_result.png](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/docs/assets/main_result.png)
*Visual 3.* Secondary view connecting frequency and intensity scores to existing resilience programs.

<iframe
  title="Short explainer video (optional)"
  width="100%" height="360"
  src="https://www.youtube.com/embed/ASTGFZ0d6Ps"
  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen></iframe>

### What’s next? 📣
- Validate stressor sequences for an additional basin using community-provided datasets.
- Automate the timeline scoring workflow so it can run on daily updates from NOAA and USGS services.
- Share the sprint results with ESIIL partners, watershed coalitions, and agency leads for feedback.

---

## Featured links (image buttons)
<!-- EDIT: Replace images/links; keep alt text meaningful and motion subtle. -->
<table>
<tr>
<td align="center" width="33%">
  <a href="assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdfa"><img src="assets/button_brief.gif" alt="Project brief notes" width="240"><br><strong>Read the brief</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/code/prism_quicklook.py"><img src="assets/button_code.gif" alt="View shared code" width="240"><br><strong>View code</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/blob/main/code/prism_quicklook.py"><img src="assets/button_data.gif" alt="Explore data" width="240"><br><strong>Explore data</strong></a>
</td>
</tr>
</table>

---

## Team
| Name | Role | Contact | GitHub |
|------|------|---------|--------|
| _Add your team lead_ | Lead | | |
| _Add teammate_ | Role | | |

---



## Storage

Code
Keep shared scripts, notebooks, and utilities in the [`code/`](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/tree/main/code) directory. Document how to run them in a README or within the files so teammates and visitors can reproduce your workflow.

Documentation
Use the [`docs/`](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/tree/main/docs) folder to publish project updates on this site. Longer internal notes can live in [`documentation/`](https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2/tree/main/documentation); summarize key takeaways here so the public story stays current.

---

## Cite & reuse
If you use these materials, please cite:

> Innovation Summit 2025 Group 2 Team. (2025). *Stressors: Order, Duration, Frequency & Intensity — Innovation Summit 2025 (Group 2).* https://github.com/CU-ESIIL/stressors-order-duration-frequency-intensity-innovation-summit-2025__2

License: CC-BY-4.0 unless noted. See dataset licenses on the **[Data](data.md)** page.

---

<!-- EDIT HINTS
- Upload images to docs/assets/ and reference as assets/filename.png
- Keep images ~1200 px wide; avoid >5–8 MB per file.
- Use short, active sentences; this is a scrolling “slide deck.”
- Update this page at least once per day during the sprint.
-->
