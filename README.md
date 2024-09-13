# World History to 1500: Q&A Dataset

This repository contains a set of question and answer pairs derived from the book "World History Volume 1: to 1500" by Ann Kordas, Ryan J Lynch, and Brooke Nelson, published by OpenStax.

## Dataset Description

This dataset consists of high-quality question and answer pairs generated from the content of "World History Volume 1: to 1500". The Q&A pairs are designed to cover key historical events, figures, and concepts from prehistory to 1500 CE, providing a comprehensive resource for students, educators, and history enthusiasts.

## Data Accuracy and Limitations

The answers in this dataset have been sampled and manually checked against the book to ensure they accurately reflect the content of the original text. However, it's important to note that any factual errors present in the original book, such as the incorrect date of the Spartacus uprising, have not been corrected in this Q&A dataset.

This dataset is solely derived from the book and has not been checked against external sources for historical accuracy. Users should be aware that while the dataset faithfully represents the content of the book, it may contain historical inaccuracies present in the original text.

## Attribution and License

### Original Work

- **Title**: [World History Volume 1: to 1500](https://open.umn.edu/opentextbooks/textbooks/world-history-volume-1-to-1500)
- **Authors**: Ann Kordas, Ryan J Lynch, and Brooke Nelson
- **Publisher**: OpenStax
- **Language**: English
- **License**: CC BY (Creative Commons Attribution)
- **License URL**: https://creativecommons.org/licenses/by/4.0/

### Derivative Work (This Dataset)

This Q&A dataset is a derivative work based on the original textbook. It was created using the PlanAI task orchestration framework to generate question and answer pairs.

- **License**: CC BY 4.0 (Creative Commons Attribution 4.0 International)
- **License URL**: https://creativecommons.org/licenses/by/4.0/

### Attribution Statement

This work is derived from "World History Volume 1: to 1500" by Ann Kordas, Ryan J Lynch, and Brooke Nelson, published by OpenStax. The original work is licensed under CC BY. This derivative work, consisting of generated question and answer pairs, is also licensed under CC BY 4.0.

## PlanAI Framework

The question and answer pairs in this dataset were generated using PlanAI, an open-source task orchestration framework. PlanAI is licensed under the Apache License 2.0.

- **PlanAI GitHub**: https://github.com/provos/planai
- **PlanAI Documentation**: https://docs.getplanai.com/

## Usage

This dataset is provided in JSON format. Each entry contains a question and its corresponding answer, along with metadata about the source material.

### Sample Structure

```json
{
    "metadata": {
        "dataset_name": "World History to 1500 Q&A Dataset",
        "dataset_description": "A collection of question and answer pairs derived from 'World History Volume 1: to 1500'",
        "original_work": {
            "title": "World History Volume 1: to 1500",
            "authors": [
                "Ann Kordas",
                "Ryan J Lynch",
                "Brooke Nelson"
            ],
            "publisher": "OpenStax",
            "language": "English",
            "license": "CC BY",
            "license_url": "https://creativecommons.org/licenses/by/4.0/"
        },
        "derivative_work": {
            "title": "World History to 1500 Q&A Dataset",
            "creator": "Your Name or Organization",
            "creation_date": "2024-09-12",
            "description": "Question and answer pairs generated using PlanAI task orchestration framework",
            "license": "CC BY 4.0",
            "license_url": "https://creativecommons.org/licenses/by/4.0/"
        },
        "generation_tool": {
            "name": "PlanAI",
            "version": "1.0.0",
            "repository": "https://github.com/provos/planai",
            "documentation": "https://docs.getplanai.com/"
        },
        "attribution": "This work is derived from 'World History Volume 1: to 1500' by Ann Kordas, Ryan J Lynch, and Brooke Nelson, published by OpenStax. The original work is licensed under CC BY. This derivative work, consisting of generated question and answer pairs, is also licensed under CC BY 4.0.",
        "usage_notes": "This dataset is intended for educational and research purposes. Users should refer to the original textbook and other authoritative sources for definitive information.",
        "contact": "For questions or concerns, please open an issue in the GitHub repository: https://github.com/provos/world-history-to-1500-qa"
    },
    "qa_pairs": [
        {
      "question": "What was the year of Spartacus's uprising against his owners?",
      "answer": "The **year of Spartacus's uprising** against his owners was **76 BCE**. This insurrection is historically significant because it represented a major challenge to Roman authority, whereby Spartacus's forces not only rose up but also **defeated two Roman armies** before facing eventual defeat in **71 BCE**. The aftermath of Spartacus's rebellion saw thousands of captured rebels crucified, a grim act intended to serve as a warning to all enslaved individuals, illustrating the lengths to which the Roman authorities would go to suppress resistance."
       },
        // ...
    ]
}
```

## Contributing

While this dataset is primarily generated from the original textbook, we welcome contributions that improve the quality, accuracy, or coverage of the Q&A pairs. Please submit a pull request with your proposed changes.

## Disclaimer

This dataset is intended for educational and research purposes. While efforts have been made to ensure accuracy, users should refer to the original textbook and other authoritative sources for definitive information.

## Contact

For questions or concerns regarding this dataset, please open an issue in this GitHub repository.