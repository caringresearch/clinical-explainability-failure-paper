### Clinical Explainability Failure (CEF) &amp; Explainability Failure Rate (EFR) – changing the way we validate classification algorithms?

This repository includes the explanation and access to the data used for experiments in our [paper][paper_link].

We used two Chext X-ray abnormality detection algorithms in our experiments:

  - Pneumonia Detection & Classification
  - CheXNeXt

#### Dataset Details
Total Studies: 611 frontal Chest X-rays
| | Pneumonia Detection & Classification | CheXNeXt |
| --- | ------ | ------ |
| # Cases in the consolidation class | 157 | 157 |
| # Consolidation classified by the model | 136 | 221 |
| True Positives | 90 | 120 |
| Clinical Explainability Failures | 2 | 16 |
| Explainability Failure Ratio | 2/90(2.22%) | 16/120(13.33%) |

##### Data Structure
You can access the data using this [link][drive_link].
Data is stored in the following structure:
 - pneumonia_detection
    - overlap
    - no_overlap
 - chexnext
    - overlap
    - no_overlap

*overlap*: Cases where the bounding box by algorithm and the radiologist overlapped.
*no_overlap*: No overlap between the bounding boxes by the algorithm and the radiologist


#### Cite


#### Concerns?

For any issues related to the paper, please write to [Vasanth Venugopal](mailto:vasanth.venugopal@caring-research.com).
For data access related issues, please write to [Rohit Takhar](mailto:rohit.takhar@caring-research.com).




   [paper_link]: <https://carin-research.com>
   [drive_link]: <https://drive.google.com/drive/folders/1LW6vrwTVwFGbT2jJW7lwDlz0bOQbcKdQ?usp=sharing>
