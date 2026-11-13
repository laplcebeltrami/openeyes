# OpenEyes

## Public datasets for visual-state and cyclic-network analyses

This inventory summarizes the public research resources identified for analyses of directed interactions and circulation in resting-state fMRI and EEG. It includes eyes-open and eyes-closed comparisons, blindness, sight recovery, and visual impairment. Availability was checked against dataset documentation and published studies on 13 November 2026.

The inventory contains **14 dataset entries: 6 rs-fMRI, 6 EEG, and 2 multimodal EEG–fMRI resources**.

**EO:** eyes open; **EC:** eyes closed; **TR:** repetition time; **NR:** not reported in the cited source. Sample sizes are source-cohort counts, not final analysis counts. Recording counts describe the acquisition protocol unless an explicitly released count is given. Totals marked “under the complete protocol” are calculated from participants × sessions/runs and are not verified counts of usable files. Public research access may require registration or approval and does not mean unrestricted redistribution.

### Resting-state fMRI

| Dataset and published source | Participants | Age | Eye condition | Recordings and acquisition | Available data and access | Planned comparison |
|---|---|---|---|---|---|---|
| Human Connectome Project Young Adult, S1200 [1] | 1,206 in the release; imaging and repeat-run coverage vary | 22–35 years at recruitment | EO, fixation on a crosshair | Up to four runs over two days; 1,200 volumes per run, TR 0.72 s, 14.4 min per run | Unprocessed and preprocessed imaging, regional/grayordinate time series, and physiological recordings where available. Registration and data-use terms; restricted phenotypes require additional approval. | Large-cohort estimation and repeat-scan reproducibility under EO fixation |
| Paired eyes-open/eyes-closed study [2] | 48 healthy adults | 19–31 years | EO and EC within participants | Three runs per participant: one EO and two EC; 144 runs under the complete protocol (48 EO and 96 EC). Each run contains 240 volumes, TR 2 s, approximately 8 min. | Public functional and structural MRI through INDI/NITRC; registration and dataset terms apply. | Direct within-participant eye-state comparison |
| Cambridge Centre for Ageing and Neuroscience (CamCAN), Stage 2 [3] | 656 participants in the imaging cohort | 18–87 years | EC | One resting-state run of approximately 8 min 40 s | Structural and functional MRI, with associated cognitive data; research access application and terms apply. | Independent EC replication, with age-comparable subsets |
| Adolescent Brain Cognitive Development (ABCD) Study [4] | 11,860 in the shared cohort; available rs-fMRI varies by release, visit, and quality control | 9–10 years at baseline, followed longitudinally | EO fixation | Up to four 5-min resting-state runs per imaging visit | Raw and processed imaging under controlled research access. A cohort-wide scan total must be obtained from the selected release manifest. | Developmental replication of EO cyclic-network patterns |
| Congenital blindness and sighted adults [5] | 30 congenitally blind and 50 sighted adults | Mean 44.23 years in the blind group and 35.33 years in controls; full ranges NR | Awake rest; sighted participants blindfolded | One to four 8-min runs per participant; 240 volumes per run, TR 2 s | Public standard-space functional time-series images, rather than native raw images, in openICPSR project 198832, version 1. | Visual-experience comparison, with age adjustment or matching |
| Macular degeneration and sighted controls [6] | 11 with macular degeneration and 11 controls | 22–83 years overall | EO in total darkness, monitored with an infrared camera | Eight 5.6-min runs per participant; 176 runs under the complete protocol. Each run contains 420 volumes, TR 0.8 s. | The article reports public availability through the Human Connectome Project. The specific cohort download package remains to be located and confirmed. | Extension to acquired visual impairment |

### EEG

| Dataset and published source | Participants | Age | Eye condition or state | Recordings and acquisition | Available data and access | Planned comparison |
|---|---|---|---|---|---|---|
| Test–retest resting and cognitive-state EEG [7] | 60 healthy adults | 18–28 years | EO fixation and EC | Three sessions: initial, approximately 90 min later, and approximately one month later. Each session includes 5 min EO and 5 min EC: 360 resting recordings under the complete protocol (180 per eye condition). Acquisition used 63 or 64 electrodes, including EOG, at 500 Hz. | Public EEG time series and behavioral measures; OpenNeuro ds004148. Additional cognitive-task recordings are outside the resting-state comparison. | Within-participant eye-state differences and test–retest reliability |
| PhysioNet EEG Motor Movement/Imagery Database: resting baselines [8] | 109 participants | NR in repository documentation | EO and EC | One 1-min baseline per condition; 218 baseline recordings under the complete protocol. 64 EEG channels, 160 Hz. | Public EDF time series. Only baseline runs are included here; motor and imagery tasks are separate. | Independent short-recording EO/EC comparison |
| SRM resting-state EEG [9] | 111 healthy participants; 42 returned for retesting | 17–71 years | EC | Four minutes per recording; repeat recording approximately 2–3 months later for 42 participants. 153 recordings, 64-channel BioSemi acquisition. | Public raw and cleaned BIDS EEG, demographics, and neuropsychological scores; OpenNeuro ds003775. | EC replication and repeat-session consistency |
| Congenital blindness EEG [10] | 27 congenitally blind adults and 27 matched sighted controls | Blind: 21–55 years; controls: 22–55 years | Blindfolded awake rest | Approximately 4–5 min; 96-channel acquisition | The public Hamburg release contains spectra and analysis code, not raw or epoched EEG time series. Time-series recordings will be requested from the authors. | Blindness comparison, conditional on obtaining the recordings |
| Congenital cataract reversal EEG [10] | 38 participants after cataract reversal and 75 sighted controls in the Methods/analyzed cohort | Cataract reversal: 6.4–41.7 years; controls: 7–42 years | EO and EC | Approximately 3–4 min per condition; 32-channel acquisition | Same public spectra/code release as above; time-series recordings require an author request. The article abstract reports 77 controls, while its Methods reports 75. | Sight-recovery and eye-state comparisons within this acquisition cohort |
| Blindness/severe visual impairment in children [11] | 50 blind or severely visually impaired children and 64 sighted children | Approximately 5 months–6 years | Daytime sleep, not awake EC rest | Nap video-EEG recordings; duration varies | Public EEG recordings and clinical metadata in the study's Zenodo release (record 10200985). | Separate age- and sleep-stage-specific extension to early visual impairment |

### Multimodal EEG–fMRI

| Dataset and published source | Participants | Age | Eye conditions | Recordings and acquisition | Available data and access | Planned comparison |
|---|---|---|---|---|---|---|
| Leipzig Mind-Brain-Body (LEMON) [12] | 227 in the cohort; 216 raw EEG datasets and 203 preprocessed EEG datasets reported | 20–35 and 59–77 years | rs-fMRI: EO fixation. EEG: alternating EO and EC. | Approximately 15.5 min rs-fMRI. EEG contains sixteen 1-min blocks, eight per eye condition; 62-channel acquisition. EEG and MRI were acquired separately. | Public MRI and EEG time series, preprocessed EEG, and associated behavioral/physiological measures. Coverage differs across modalities. | Within-participant EEG eye-state comparison and cross-modal replication |
| Simultaneous and independent EEG–MRI [13] | 20 healthy men | Mean 26 years, SD 3.8; full range NR | rs-fMRI: EC. EEG: EO and EC, outside the scanner, inside without scanning, and during fMRI. | Two 10-min EC rs-fMRI acquisitions, with and without EEG; 39 of 40 planned EC runs are present. EEG resting blocks are 2 min outside/inside the scanner and 10 min EC plus 2 min EO during simultaneous recording; 32 channels. | Public BIDS MRI and EEG in Mendeley Data. The 2-min EO resting fMRI acquisition is not included in the release; an EO/EC alternation task is available separately. | Cross-modal correspondence and sensitivity to the EEG recording environment |

### How these resources will be used

- EO and EC effects will be compared within participants where both conditions are available. Cohort and age differences will be handled separately from eye-state effects.
- Directed interactions require time-resolved recordings. The public blindness and cataract-reversal EEG spectra can support spectral comparisons but cannot reconstruct temporal directed networks; circulation analysis depends on obtaining the underlying EEG recordings.
- Sleep EEG will be analyzed separately from awake rest. Blindfolding, eye closure, and EO fixation are recorded as distinct conditions.
- Final participant and scan counts will follow release-specific file inventories and quality control. Cohort totals will not be treated as counts of complete, usable scans.
- Existing locally collected UW–Madison twin and JME cohorts are additional project resources, but they are not listed as public datasets here. This repository inventory contains no participant-level data.

### Published references

1. Van Essen DC, Smith SM, Barch DM, et al. The WU-Minn Human Connectome Project: An overview. *NeuroImage*. 2013;80:62–79.
2. Liu D, Dong Z, Zuo X, et al. Eyes-Open/Eyes-Closed Dataset Sharing for Reproducibility Evaluation of Resting State fMRI Data Analysis Methods. *Neuroinformatics*. 2013;11:469–476.
3. Taylor JR, Williams N, Cusack R, et al. The Cambridge Centre for Ageing and Neuroscience (Cam-CAN) data repository: Structural and functional MRI, MEG, and cognitive data from a cross-sectional adult lifespan sample. *NeuroImage*. 2017;144:262–269.
4. Casey BJ, Cannonier T, Conley MI, et al. The Adolescent Brain Cognitive Development (ABCD) study: Imaging acquisition across 21 sites. *Developmental Cognitive Neuroscience*. 2018;32:43–54.
5. Tian M, Xiao X, Hu H, et al. Visual experience shapes functional connectivity between occipital and non-visual networks. *eLife*. 2026;13:RP93067.
6. Fleming LL, Defenderfer MK, Demirayak P, et al. Impact of Deprivation and Preferential Usage on Functional Connectivity Between Early Visual Cortex and Category-Selective Visual Regions. *Human Brain Mapping*. 2024;45:e70064.
7. Wang Y, Duan W, Dong D, Ding L, Lei X. A test-retest resting, and cognitive state EEG dataset during multiple subject-driven states. *Scientific Data*. 2022;9:566.
8. Schalk G, McFarland DJ, Hinterberger T, Birbaumer N, Wolpaw JR. BCI2000: a general-purpose brain-computer interface (BCI) system. *IEEE Transactions on Biomedical Engineering*. 2004;51:1034–1043.
9. Hatlestad-Hall C, Rygvold TW, Andersson S. BIDS-structured resting-state electroencephalography (EEG) data extracted from an experimental paradigm. *Data in Brief*. 2022;45:108647.
10. Ossandón JP, Stange L, Gudi-Mindermann H, et al. The development of oscillatory and aperiodic resting state activity is linked to a sensitive period in humans. *NeuroImage*. 2023;275:120171.
11. Vitali H, Campus C, Signorini S, et al. Blindness affects the developmental trajectory of the sleeping brain. *NeuroImage*. 2024;286:120508.
12. Babayan A, Erbey M, Kumral D, et al. A mind-brain-body dataset of MRI, EEG, cognition, emotion, and peripheral physiology in young and old adults. *Scientific Data*. 2019;6:180308.
13. Gallego-Rudolf J, Corsi-Cabrera M, Concha L, Ricardo-Garcell J, Pasaye-Alcaraz E. Simultaneous and independent electroencephalography and magnetic resonance imaging: A multimodal neuroimaging dataset. *Data in Brief*. 2023;51:109661.
