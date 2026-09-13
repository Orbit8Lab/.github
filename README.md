<div align="center">

<img src="assets/logo.png" alt="Orbit8 Lab" width="120">

# Orbit8 Lab

**AI-driven game localization, LQA, and localization research.**

[Website](https://www.orbit8lab.com/) · [Portfolio](https://www.orbit8lab.com/portfolio) · [Blog](https://www.orbit8lab.com/blog) · [info@orbit8lab.com](mailto:info@orbit8lab.com)

Los Angeles, CA

</div>

---

## About

Orbit8 Lab helps game developers launch globally. We provide localization, localization quality assurance, and strategic consulting built on an agentic language and QA system, and we publish research on how well language models actually perform on localization work.

Game localization has its own failure modes. Strings are short and contextless, UI text carries hard length limits, terminology has to stay consistent across tens of thousands of lines, and gendered and inflected languages break in ways that generic MT evaluation never measures. We build for that reality rather than adapting tooling made for document translation.

## Services

| | |
|---|---|
| **Game localization** | Context-aware game text translation at scale |
| **Localization QA** | Automated and human-in-the-loop LQA testing |
| **Document translation** | Supporting materials, store pages, marketing copy |
| **Compliance** | Legal and cultural review for target markets |
| **Voice over** | Coming soon |

[Request a free consultation →](mailto:info@orbit8lab.com?subject=Request%20a%20demo)

## Credits

### Shipped

**[STARDUST: Wish of Witch](https://store.steampowered.com/app/3936730/STARDUST_Wish_of_Witch/)** — Kniv Studio Co., Ltd. / Sologame
Localization QA for Simplified Chinese (zh-Hans) and Traditional Chinese (zh-Hant).
Pixel-art turn-based SRPG, released May 28, 2026.

### In progress

**[Among Shadows](https://store.steampowered.com/app/2923810/Among_Shadows/)**
Localization services.
Asymmetric PvP social-deduction game, Early Access September 24, 2026.

## Research

**[Benchmarking Large Language Models for Game Localization Quality Assurance: A Cross-Model, Cross-Lingual Analysis](https://aclanthology.org/2026.amta-research.12/)**
Mao Tian, Na Wu
*Proceedings of the 17th Conference of the Association for Machine Translation in the Americas (Research Track), pages 186–201. Québec City, Canada, August 2026.*
[PDF](https://aclanthology.org/2026.amta-research.12.pdf) · [ACL Anthology](https://aclanthology.org/2026.amta-research.12/)

We evaluated eight language models, both closed-source and open-weight, on English-to-six-language LQA across two game genres: 96 evaluation settings and 48,000 translation samples in total. Claude Sonnet 4 led overall (F1 = 0.766), ahead of Qwen-2.5-72B (0.711) and Gemini 2.0 Flash (0.691). Target language had no statistically significant effect on performance overall, though results were most consistent on French and weakest on Japanese, and genre made little difference. Open-weight models came close enough on quality, at much lower cost, to be viable in production.

<details>
<summary>BibTeX</summary>

```bibtex
@inproceedings{tian-wu-2026-benchmarking,
    title = "Benchmarking Large Language Models for Game Localization Quality Assurance: A Cross-Model, Cross-Lingual Analysis",
    author = "Tian, Mao and Wu, Na",
    booktitle = "Proceedings of the 17th Conference of the Association for Machine Translation in the {A}mericas (Volume 1: Research Track)",
    month = aug,
    year = "2026",
    address = "Qu{\'e}bec City, Canada",
    publisher = "Association for Machine Translation in the Americas",
    url = "https://aclanthology.org/2026.amta-research.12/",
    pages = "186--201"
}
```

</details>

### Annual benchmark

We publish this benchmark on an annual cycle so results track the models actually in use rather than a single frozen snapshot. Each edition re-runs the evaluation across current models and language pairs, making year-over-year progress visible.

## Collaborate with us

We are looking for collaborators across the field: localization teams, QA leads, game studios, and researchers working on MT evaluation and multilingual NLP.

We would especially like to hear from you if you:

- work on LQA in production and can speak to error types that matter in shipped titles
- can contribute evaluation data or language-pair expertise, particularly outside the highest-resource languages
- want to co-author or replicate benchmark work
- have a language or script you think current evaluation practice handles badly

## Contact

| | |
|---|---|
| Email | [info@orbit8lab.com](mailto:info@orbit8lab.com) |
| Website | [orbit8lab.com](https://www.orbit8lab.com/) |
| Location | Los Angeles, CA |

<div align="center">
<sub>© 2026 Orbit8 Lab</sub>
</div>
