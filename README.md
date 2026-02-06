# Welcome to the UCL EEG Community

We are a hub for researchers at **University College London** focused on electroencephalography (EEG), signal processing, and neuroimaging. Our goal is to share resources, pipelines, and expertise across departments.

## 📅 Upcoming Events
* **Journal Club:** 3rd Wednesday of every month at 14:00 (Room 305).
* **Workshops:** "Intro to MNE-Python" - Coming Spring 2026.
* **Annual Symposium:** Call for abstracts is now open!

## 🧠 Resources & Pipelines
We maintain shared protocols for:
* **Preprocessing:** Maxwell filtering, ICA, and artifact rejection.
* **Analysis:** Source localization and connectivity.
* **Tools:** Support for MNE-Python, EEGLAB, and FieldTrip.

### Getting Started with our Data
Here is a standard snippet for loading our lab's raw data format:

```python
import mne

# Load raw data with standard UCL montage
raw = mne.io.read_raw_fif('subject_01_raw.fif', preload=True)
raw.filter(1, 40)  # Bandpass filter
print(raw.info)

---
layout: page
title: Team
permalink: /team/
---

# Meet the Community

Here are the key contributors to the UCL EEG Community.

## Steering Committee
* **[Name 1]**: Professor of Neuroscience. Focus: Source Localization.
* **[Name 2]**: Postdoc Fellow. Focus: Real-time BCI.

## PhD Students
* **[Student A]**: Working on auditory evoked potentials.
* **[Student B]**: Working on pediatric EEG pipelines.

## Join Us
We are always looking for new members. [Contact us](mailto:your-email@ucl.ac.uk) to get involved!
