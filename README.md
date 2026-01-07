# KBLI 2020 Dataset

This repository contains a comprehensive dump of the KBLI (Klasifikasi Baku Lapangan Usaha Indonesia) 2020 dataset. KBLI is Indonesia's standard industrial classification system.

## Data Format

This dataset is currently available only in `JSON` format.
## KBLI Classification Structure

The KBLI 2020 classification system is structured hierarchically, typically comprising the following levels:

*   **Section:** The highest level of classification, represented by a single alphabetical character.
*   **Division:** A two-digit code, providing a broad categorization of economic activities.
*   **Group:** A three-digit code, offering a more specific classification within a division.
*   **Class:** A four-digit code, detailing a particular type of economic activity within a group.
*   **Subclass:** A five-digit code, representing the most detailed level of classification.

The KBLI codes are structured using a digit logic where each additional digit refines the classification. For example, `A` is a Section, `01` is a Division within Section `A`, `011` is a Group within Division `01`, and so on.

| Class Level | Code Format | Description                                       | Included |
| :---------- | :---------- | :------------------------------------------------ | :--------- |
| Section     | A           | Highest level, broad economic sectors             | No         |
| Division    | XX          | Two-digit code, general categories                | Yes        |
| Group       | XXX         | Three-digit code, specific categories             | Yes        |
| Class       | XXXX        | Four-digit code, detailed activities              | Yes        |
| Subclass    | XXXXX       | Five-digit code, most granular classification     | Yes        |
## Files

The dataset is organized into the following files:

| Class       | Filename           | Total Data |
| :---------- | :----------------- | :--------- |
| Full        | [kbli_lengkap.json](kbli_lengkap.json)     |  2686      |
| Division    | [kbli_golpok.json](kbli_golpok.json)   |  88        |
| Group       | [kbli_gol.json](kbli_gol.json)      |  244       | 
| Class       | [kbli_subgol.json](kbli_subgol.json)   |  523       | 
| Subclass    | [kbli_kelompok.json](kbli_kelompok.json) |  1831      |



## Usage

This dataset is provided for informational and analytical purposes. You can use it to:

*   Understand the structure of Indonesian industries.
*   Categorize businesses based on their activities.
*   Perform statistical analysis related to economic sectors.
*   Develop applications that require KBLI classifications.

## Legal Information & Disclaimer

>**IMPORTANT**: This dataset is provided "as is" without any warranty, express or implied. While we strive for accuracy, we cannot guarantee the completeness or correctness of all information contained herein.

**This data is publicly available on [oss.go.id](https://oss.go.id).**

**By using this dataset, you acknowledge and agree that you are solely responsible for its interpretation and application. We are not liable for any direct, indirect, incidental, special, or consequential damages arising from the use or inability to use this dataset, or for any actions taken based on the information provided.**

>This dataset is for general informational purposes only and does not constitute legal advice. Please consult with a qualified legal professional for any legal concerns or interpretations related to KBLI or business classifications.

>Using this public data for legitimate and ethical purposes, consistent with its public availability, should not lead to legal repercussions.
