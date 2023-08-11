# Concerns about Datasets:

* **Datasets' Practicality**: (R1P1) Skepticism about the practicality of the SICE_Grad and SICE_Mix datasets, especially regarding their difference from real-life low-light scenarios and the use of permuting panels. More explanation about the design philosophy of these datasets is needed.

* **Video Dataset Context**: (R1P5) Concerns about the Night Wenzhou video dataset not having corresponding normal light videos. More context on how the video is degraded, and how noise, blur, shadows, and artifacts are added is needed.

* **Dataset Realism**: (R3P1) The proposed datasets, especially "SICE_Grad” and "SICE_Mix", are seen as not being reflective of real-world scenarios, and there's skepticism about their value as benchmarks.

* **Dataset Artifacts/Copyright**: (R2P2) The boundary artifact in the new datasets, especially between different panels, needs analysis as they might distort the image semantics. Moreover, there is a concern regarding copyright issues since modifications have been made to the existing SICE dataset.

* **Wenzhou Dataset Value**: (R4P2) The Night Wenzhou dataset is challenging, but more analysis and discussion are needed to demonstrate its value. Quantitative comparison results for this dataset are also missing.


# Literature Review:

* **Literature Expansion**: (R5P1, R5P2, R3P2, R4P1, R1P3) A need for a more comprehensive literature review, especially including works based on Near-Infrared (NIR) light, noise distribution modeling in extremely dark environments, video enhancement models, and other high-level applications.

* **Redundant Figures**: (R5P3, R5P4, R5P5, R5P6) Some figures, like framework figures from other papers, might be redundant and can be removed. 

* **Network Division**: (R3P3) The divisions of some network structures are not seen as appropriate (e.g., normalizing flow and optical flow)

* **Re-categorization**: (R2P1) There's feedback to re-categorize traditional learning-based approaches for clarity. (e.g., HE should be stat, dehaze based on Retinex)


# Evaluation and Analysis:

* **Fig.16 Clarity**: (R1P2, R2P4) Clarifications are required on what the color means in Fig.16. Multiple reviewers pointed out this issue.

* **Method Emphasis**: (R2P3) There's feedback that the paper emphasizes methods introduced in recent years too much, and there's a need to include more established methods for a more comprehensive performance comparison.


# Writing and Presentation:

* **Grammar/Claims**: (R1P7, R2P5, R3P5) Multiple grammatical errors, typos, and strong claims were noted, requiring careful proofreading and potential rephrasing.
* **Differentiate from Others**: (R1P6) The paper should differentiate itself from other surveys or benchmarks on the topic of low-light image enhancement.


# Relevance to the Journal:

* **Journal Relevance**: (Final Paragraph) The paper needs to address its relevance to the journal, especially in terms of its topic and the literature cited. Questions arise about whether such topics have been published in TNNLS before and, if not, why it would be relevant now.
