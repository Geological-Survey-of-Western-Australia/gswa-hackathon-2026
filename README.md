# GSWA HyLogger Hackathon 2026

Home base for the 2026 Geological Survey of Western Australia (GSWA) Hackathon, running **12–16 October 2026**. This is where you'll find teammates, ask questions, and submit your project.

The hackathon brings geologists, data scientists, developers and GIS specialists together to unlock new value from GSWA's **HyLogger** drill core spectral data. Whether you're new to geoscience or new to coding, you're welcome here.

---

## 🚀 Getting started

1. **Read the event details.** The schedule and terms and conditions are on the [GSWA Hackathon website](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/geological-survey-of-western-australia/gswa-hackathons).
2. **Introduce yourself.** Post in the [welcome thread](https://github.com/Geological-Survey-of-Western-Australia/gswa-hackathon-2026/discussions/2) using the intro template, and let others know if you're looking for a team.
3. **Form a team.** Teams are formalised in person on **Monday 12 October**. Use the welcome thread beforehand to meet people and line up teammates. Mix domain and technical skills where you can.
4. **Get the data.** See [Data](#-data) below.
5. **Build something.** Work in your own team repository.
6. **Submit your project** by Thursday night, then **pitch it in person on Friday**. See [Submitting your project](#-submitting-your-project).

---

## 🎯 Challenge themes

| Theme | Focus |
|---|---|
| **Data Crunch** | Analytics and characterisation of the HyLogger dataset: statistics, clustering, anomaly detection, and integration with geochemistry and petrophysics |
| **Data Adoption** | Real-world industry applications: near-mine settings, resource evaluation, and geometallurgy |
| **Data Visualisation & Interactivity** | Making HyLogger data easier to use: QGIS integration, 3D visualisation, and interactive web viewers |

---

## 📁 Data

HyLogger data is available from two places:

- **[National Virtual Core Library (NVCL) on NCI THREDDS](https://thredds.nci.org.au/thredds/catalog/rs07/WA/catalog.html):** open-file HyLogger data for WA, including The Spectral Geologist (.tsg) files and drill core images.
- **[Data and Software Centre (DASC)](https://dasc.dmirs.wa.gov.au/):** search for **"HyLogger Drillhole Package"**.

To read .tsg files in Python, use [pytsg](https://github.com/Geological-Survey-of-Western-Australia/pytsg), GSWA's open-source reader.

**Please don't commit HyLogger data to any repository.** The packages are large, and redistribution may be restricted by the data licence. Instead:

- Add your data folders to `.gitignore`.
- State in your README which drillholes or packages you used and where to download them.
- Small derived outputs (e.g. summary tables or figures) are fine to include.

---

## 💬 Getting help

- **Questions for organisers or GSWA experts:** [Questions thread](https://github.com/Geological-Survey-of-Western-Australia/gswa-hackathon-2026/discussions/1)
- **Introductions, team-finding and ideas:** [Welcome thread](https://github.com/Geological-Survey-of-Western-Australia/gswa-hackathon-2026/discussions/2)

Check the FAQ at the top of the questions thread first, then post your question as a new comment.

---

## 📦 Submitting your project

Build your project in your **own public repository**, then submit it here.

1. Make sure your repo has a README (see the checklist below).
2. Nominate a team captain. They'll be the main contact for organisers and should be the one to submit.
3. Prepare your pitch slides (PDF preferred, max 25 MB). You'll attach them to the submission form and present them on Friday.
4. [Open a submission](https://github.com/Geological-Survey-of-Western-Australia/gswa-hackathon-2026/issues/new?template=submission.yml) and fill in the form.

**Using AI tools is allowed and won't be penalised.** The form asks whether your team used them, purely for transparency.

**Submission deadline:** Thursday 15 October, 11:59 pm AWST

**Pitches:** each team presents its project in person on **Friday 16 October**, using the slides attached to your submission.

Judging will use the latest commit on your default branch at the deadline. Anything pushed afterwards won't be considered.

### README checklist for your project

Your project README should include:

- [ ] Team name, members and team captain
- [ ] Challenge theme
- [ ] The problem you tackled and what you built
- [ ] Which HyLogger data you used and where to get it
- [ ] How to install and run your project
- [ ] Screenshots or a demo video (strongly encouraged)
- [ ] A licence (see the terms and conditions for any requirements)

---

## 🤝 Ground rules

- Be welcoming, especially to people new to geoscience or new to coding.
- Keep discussion respectful and in line with the event code of conduct.
- This repository is **public**. Don't post anything you wouldn't want made public, including personal contact details, credentials, or confidential company data.

---

## 📬 Contact

Organisers: events@dmpe.wa.gov.au

Organised by the [Geological Survey of Western Australia](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/geological-survey-of-western-australia).