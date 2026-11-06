# Systematic Mapping Protocol

**Accessibility Features in Internet of Medical Things Interfaces: Impacts on User Experience**

The protocol was defined before screening and managed on the Parsifal platform (https://parsif.al). The study is reported following the PRISMA 2020 guidelines.

Codes: **RQ** = research question, **IC** = inclusion criterion, **EC** = exclusion criterion, **DE** = data extraction field, **QA** = quality assessment question.

## 1. Objective

To identify and analyze the accessibility features used in IoMT interfaces based on wearable devices and mobile health apps, considering their impacts on accessibility, usability and user experience. To this end, the mapping characterizes which features are implemented, which user profiles they target, which barriers they aim to reduce and which empirical effects were observed in evaluations with real users.

## 2. Research questions

**RQ1: Which accessibility technologies and features are used in IoMT system interfaces?**

*Motivation and expected outcome:* There is no survey of which accessibility features are actually implemented in wearables and health apps, whose interfaces differ from the conventional screens covered by accessibility guidelines. The aim is to identify and categorize these features (field DE-5); the expected outcome is a map of the most and least frequent features and of their adherence to formal guidelines.

**RQ2: Which user profiles and accessibility needs are considered in IoMT system interfaces?**

*Motivation and expected outcome:* An accessibility feature is only useful to people who have the limitation it compensates for. The aim is to identify the profiles and needs addressed (field DE-6); the expected outcome is the identification of well-represented and under-represented profiles in the literature.

**RQ3: How do accessibility features influence the accessibility and usability of IoMT system interfaces?**

*Motivation and expected outcome:* Adopting a feature does not by itself guarantee better use of the system. The aim is to gather the reported accessibility, effectiveness, efficiency and satisfaction metrics (field DE-7); the expected outcome is a synthesis of the observed effects and of the strength of the supporting evidence.

**RQ4: Which access and interaction barriers are reduced by applying accessibility features in IoMT systems?**

*Motivation and expected outcome:* Interaction barriers are among the causes of low adoption and abandonment of health technologies by older adults and people with disabilities. The aim is to identify which sensory, motor, cognitive and operational barriers the features seek to mitigate (field DE-8); the expected outcome is a typology of the barriers reduced and of those that persist.

**RQ5: How does applying accessibility features affect users' experience and ease of interaction in IoMT systems?**

*Motivation and expected outcome:* Beyond performance, continued use depends on how users perceive the system. The aim is to gather the reported perceptions of ease, autonomy, confidence and satisfaction (field DE-9); the expected outcome is a qualitative synthesis of the features' effects on the user experience.

## 3. Eligibility criteria

A study was included when it met all inclusion criteria (IC) and no exclusion criterion (EC).

| ID | Criterion |
|---|---|
| IC-1 | Primary empirical study that evaluates an IoMT interface with real users, using quantitative, qualitative or mixed methods. |
| IC-2 | Published between January 2020 and September 2026. |
| IC-3 | Full text in English, Portuguese or Spanish. |
| IC-4 | Describes an accessibility feature, an assistive technology or an interaction adaptation applied to wearable devices or mobile health apps. |
| IC-5 | Presents a direct comparison or reference condition (reclassified as quality item QA-5). |
| IC-6 | Reports at least one outcome of accessibility, effectiveness, efficiency, satisfaction, user experience, mental workload or operational error. |
| IC-7 | Full peer-reviewed paper (journal or conference proceedings). |
| EC-1 | Conceptual paper, without implementation or empirical validation of the interface. |
| EC-2 | Literature review, editorial, opinion piece, preprint, abstract without full text, or non-peer-reviewed book chapter. |
| EC-3 | Published before 2020 or in a language other than those defined. |
| EC-4 | Exclusive focus on networks, sensors, energy, security or privacy, without evaluating the interaction with the end user. |
| EC-5 | Interface unrelated to health, IoMT or patient monitoring. |
| EC-6 | Full text unavailable after an institutional access attempt. |
| EC-7 | Duplicate record. |

To apply IC-4 consistently, three interpretation rules were adopted:

- (i) Non-wearable devices were accepted only when the user interacts with them through a health app.
- (ii) An accessibility feature was counted as an interface element designed to compensate for a user limitation (e.g., haptic feedback, voice, sign language, multilingual or simplified interface, multimodal alerts), or a device described by the authors themselves as assistive technology.
- (iii) Accessibility in the geographic or economic sense (access to health services) was not considered.

## 4. Information sources and period

Searches were run in six electronic databases: Scopus, EI Compendex (Engineering Village), Web of Science, ScienceDirect, ACM Digital Library and IEEE Xplore. IEEE Xplore, ACM Digital Library, ScienceDirect and EI Compendex are recommended by Kitchenham and Charters as primary sources for reviews in computing; Scopus and Web of Science were added because they index engineering, computing and health journals in a multidisciplinary way.

The period covered was January 1, 2020 to September 30, 2026. The initial search was run in the first five databases; the IEEE Xplore search was re-run in October 2026 because the first run returned no records. During IEEE Xplore screening, 20 additional records were found on the database's own results pages without appearing in the exported file and were treated as records from other sources. No grey literature search or citation tracking was performed.

## 5. Search string

Main string (Scopus, EI Compendex, Web of Science, ACM Digital Library and IEEE Xplore, applied to the *All Metadata* field in the latter):

```
("Internet of things" OR "Sensors" OR "Wearables")
AND ("Health" OR "Healthcare" OR "Digital Health")
AND ("Accessibility" OR "Web Accessibility" OR "WCAG" OR "Assistive Technology" OR "Adaptive UI" OR "Universal Design" OR "Inclusive Design" OR "Multimodal Interaction")
AND ("Usability" OR "User Experience" OR "UX" OR "System Usability Scale" OR "Interaction Barriers" OR "Usability Barriers" OR "Acceptability" OR "Task Performance")
```

ScienceDirect limits the number of Boolean operators per query, so the string was split into four combinations, crossing the technology terms ("Internet of things" and "Wearables") with the accessibility terms ("Accessibility" and "WCAG"). In the other blocks, the term "Health*" and the following usability block were kept:

```
("Usability" OR "User Experience" OR "System Usability Scale" OR "Interaction Barriers" OR "Usability Barriers")
```

## 6. Study selection

Records were imported into Parsifal, where duplicates were removed and records published before 2020 were discarded. Selection took place in two phases. In the first, titles and abstracts were screened by the first author. In the second, the accepted records were checked against the eligibility criteria, based on the full text whenever available. In this phase, a language model was used as a support tool to locate, in the full text, the evidence related to each criterion; all decisions were recorded with the criterion applied and the justification, and reviewed by the authors. IEEE Xplore records went through the same process and were compared with those from the other databases to identify duplicates.

## 7. Data extraction

Extraction used a standardized form with 14 fields (DE-1 to DE-14), plus fields for the comparator and the context of use. Fields DE-5 to DE-9 correspond directly to the research questions. For each study, verbatim excerpts supporting the values extracted in fields DE-5, DE-7, DE-8 and DE-9 were recorded. As in the selection, a language model was used to help locate the information in the full text, and the extracted values were checked by the authors against these excerpts. Missing information was recorded as "Not reported".

| Field | Content | RQ |
|---|---|---|
| DE-1 to DE-3 | Identification, country and publication type | – |
| DE-4 | IoMT system type (wearable, app, telehealth, vital signs monitor, etc.) and context of use | – |
| DE-5 | Accessibility technologies and features | RQ1 |
| DE-6 | User profiles and needs considered | RQ2 |
| DE-7 | Usability and accessibility metrics and impacts | RQ3 |
| DE-8 | Access and interaction barriers reduced | RQ4 |
| DE-9 | Impacts on user experience and ease of interaction | RQ5 |
| DE-10 and DE-11 | User evaluation method and sample characterization | – |
| Comparator | Presence and type of comparison condition | – |
| DE-12 to DE-14 | Reproducibility artifacts, methodological rigor and reported limitations | – |

## 8. Quality assessment

Each study was assessed against five questions, scored 0 (not met), 0.5 (partially met) or 1 (fully met), for a maximum score of 5. The score was not used to exclude studies.

- **QA-1:** Are the interface, the IoMT device and the accessibility features described in enough detail to allow replication?
- **QA-2:** Are the accessibility, usability and user experience instruments valid and consistently applied?
- **QA-3:** Are the results presented completely, including quantitative measures, uncertainty and relevant qualitative evidence?
- **QA-4:** Is there evidence of adherence to accessibility guidelines (such as WCAG or Universal Design) and of reproducibility (code, data, protocol or hardware description)?
- **QA-5:** Does the study present a direct comparison or reference condition capable of supporting the analysis of the feature's effect?
