# Data Science/ML Projects

## Text Segmentation from Engineering Drawings

**Problem:** Segmenting semantically meaningful text from engineering drawings (such as blueprints and schematics) is a rather more difficult job than, for example, OCR on text from standardized printed pages like books, newspapers, or magazines.

**Approach:** Fine-tuning the [Kraken](https://github.com/mittagessen/kraken) convolutional neural network, which was trained on pages or images with more distortion and other abberations. I developed and ran ML experiments for optical character recognition, iterating between data preprocessing and experimental testing. As part of the process, I streamlined and improved the data processing pipeline, improved training data accounting and quality, and improved results assessment and validation. Finally, I contributed to the final report for the Department of Energy grant supporting this research.

<!-- To segment and extract useful building data from engineering drawings, I developed and ran ML experiments for optical character recognition with the Kraken convolutional neural network. Mainly, segmenting semantically meaningful text from engineering drawings like blueprints and schematics is a rather more difficult job than, say, text from standardized printed pages like books, newspapers, or magazines. Consequently, I fine-tuned Kraken, which was trained on pages or images with quite a bit more distortion and other abberations.

As part of the process, I streamlined and improved the data processing pipeline (mainly to normalize and filter incoming data to the model), improved training data accounting and quality, and improved results assessment and validation. Finally, I contributed to the final report for the Department of Energy grant supporting this research. -->

---

## Onboard Data Science Tutorials \[[git](https://github.com/onboard-data/notebooks), [medium](https://medium.com/@christopher_DT)\]

<img src="images/outlier_detection.webp"/>

A series of data science tutorials and open source evangelism for Onboard Data, Inc, including: 
* tutorials on the company's API and API client \[[one](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/01_api_and_wrapper.ipynb), [two](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/02_data-points-exploration-in-pandas.ipynb), [three](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/03_time-series-analysis.ipynb)\]
* timeseries cleaning and basic imputation techniques \[[colab](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/04_timeseries_cleaning_and_imputation.ipynb), [medium](https://medium.com/onboard-blog/timeseries-cleaning-and-imputation-a96ab7e45eb7)\]
* feature engineering and selection \[[colab](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/05_Forecasting_part_1.ipynb), [medium](https://medium.com/onboard-blog/feature-selection-and-timeseries-forecasting-24067e0038e3)\]
* timeseries forecasting with Facebook's Prophet \[[colab](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/06_Forecasting_Part_2.ipynb), [medium](https://medium.com/onboard-blog/timeseries-forecasting-for-building-experts-part-2-trend-forecasting-ef82f594bc28)\]
* outlier and anomaly detection \[[colab](https://colab.research.google.com/github/onboard-data/notebooks/blob/dev/07_outliers_and_anomalies.ipynb), [medium](https://medium.com/onboard-blog/outlier-and-anomaly-detection-for-building-experts-8329492783ec)\]
* fault detection in HVAC systems \[[medium](https://medium.com/onboard-blog/open-fdd-for-automated-hvac-fault-detection-209945efde57)\]

# Cognitive Science Research

Click images for full poster pdf

### When The Wind Is Southerly: A Bayesian Model of Cue-based Cardinal Direction Estimation. 
[<img src="images/model_results.png?raw=true"/>](/pdf/CDudasThomas_Psychonomic_2021.pdf)

---

### Absolute Direction Feedback Impacts Environmental Knowledge
[<img src="images/campus_traversal.png?raw=true">](/pdf/christopher_dudas-thomas_psychonomics_2019.pdf)

---

### How Do You Know If You’re Lost or Not? Epistemic and Pragmatic Action During Navigation
[<img src="images/epistemic_v_pragmatic.png?raw=true">](/pdf/christopher_dudas_thomas_psychonomics_2018.pdf)

---

### Navigational Feedback Technology Alters Environment Awareness
[<img src="images/vb_v_hc.png?raw=true">](/pdf/christopher_aps_2017_final.pdf)

---

### Lost and Confused: Measuring Uncertainty in Navigation
[<img src="images/lost_and_confused.png?raw=true">](/pdf/christopher_psychonomics_2016_final.pdf)

# Software Projects

[QuantAQ R Client](https://github.com/christopherDT/r-quantaq)
* Developing company's R API client from scratch following CRAN standards.

[Onboard R Client](https://github.com/onboard-data/client-R)

* Refined the company's internal R client, bringing it up to CRAN standards, making it ready to be public-facing. Improved parity with company's public-facing Python API client.

[Onboard ReadTheDocs](https://onboard-api-wrappers-documentation.readthedocs.io/en/latest/index.html)

* Updated the company's API client docs to reflect the newly-public R client.

[open-fdd](https://github.com/bbartling/open-fdd/)

* Overhauled one portion of this open source AHU fault detection. Reduced redundant code, shifted to OOP, improved modularization.

<!-- ---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

--- -->