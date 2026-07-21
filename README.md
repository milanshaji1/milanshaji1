# Milan Shaji

Final-year Data Science & Business student at QUT (Bachelor of Data Science + Bachelor of Business, Entrepreneurship & Innovation), graduating 2026. Based in Queensland, Australia — targeting graduate roles in data, analytics and AI from February 2027.

**Data systems that prove their own numbers.** I build things that check their own outputs before publishing — models backtested against real baselines, and LLM outputs that are rejected unless they pass verification before touching a running system.

### Featured projects

**[GridPulse](https://github.com/milanshaji1/gridpulse)** — AI market analyst for Australia's electricity grid.
- LightGBM spike-risk model, rolling-origin backtest on 1M+ rows of real AEMO market data: 71% recall at a 20% alert budget vs. 58% baseline, PR-AUC 0.35 vs. 0.17 climatology
- Claude-based analyst generates daily briefs; every `{{value|SQL}}` citation is re-verified against the database before publishing — 30/30 on a golden evaluation set

**[gesture-canvas](https://github.com/milanshaji1/gesture-canvas)** — hand-tracked generative graphics in TouchDesigner, directed by a schema-verified LLM.
- Real-time particle scene driven by webcam hand tracking (pinch to burst)
- Natural-language scene directives ("burst mode with golden yellow sparks") are translated by Claude, then schema-validated and rejected if malformed — before ever reaching the render
- Same verification discipline as GridPulse, generalised to a domain with no database: trust the schema, not the model

**[hand-filter](https://github.com/milanshaji1/hand-filter)** — real-time computer vision VFX in TouchDesigner.
- MediaPipe hand tracking drives three corner-pinned quads, one per finger-pair across both hands, each masking a different live video filter

**[Portfolio](https://milanshaji1.github.io)** — full write-ups, methodology, and résumé

### Toolkit

Python · SQL · R · PyTorch · Power BI / Tableau · AWS basics

### Currently

Open to graduate roles in data science, analytics, and AI.
