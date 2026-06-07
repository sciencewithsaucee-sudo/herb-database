# 🌿 Amidha Ayurveda Herb Database v2.0

**An open-source, citable dataset of Ayurvedic medicinal plants for research, education, and digital innovation.**

The Amidha Ayurveda Herb Database aims to make authentic Ayurvedic knowledge accessible in a structured, machine-readable format, bridging traditional wisdom with modern data science, computational research, and AI applications.

---

## 📖 Overview

The **Amidha Ayurveda Herb Database v2.0** contains a curated collection of **360 unique Ayurvedic medicinal plants** with standardized botanical and Ayurvedic metadata.

Version 2.0 introduces significant improvements in data quality, structure, and consistency by consolidating duplicate records, removing formulation entries, and standardizing herb information into canonical plant records.

### Dataset Includes

* Botanical names
* English names
* Plant family classification
* Sanskrit synonyms
* Parts used
* Main Ayurvedic indications
* Rasa (Taste)
* Guna (Qualities)
* Virya (Potency)
* Vipaka (Post-digestive effect)
* Prabhava (Specific action)
* Dosha effects (Pacify / Aggravate)
* Herb descriptions
* Links to detailed herb pages

This dataset is suitable for:

* Ayurvedic students and researchers
* Health-tech startups and AI developers
* Web and app builders
* Open-data initiatives
* Computational Ayurveda research
* Educational content creation

---

## 📊 Dataset Statistics

| Metric                  | Count     |
| ----------------------- | --------- |
| Unique Medicinal Plants | 360       |
| Data Format             | JSON      |
| License                 | CC BY 4.0 |
| Version                 | 2.0.0     |

---

## 🛉 Sample Data Preview (JSON)

```json
[
  {
    "name": "Tulsi",
    "botanical_name": "Ocimum sanctum",
    "family": "Lamiaceae",
    "english_name": "Holy Basil",
    "sanskrit_synonyms": [
      "Surasa",
      "Apetarakshasi",
      "Bhuteshta",
      "Gauri"
    ],
    "part_used": [
      "Patra",
      "Pushpa",
      "Moola",
      "Bija"
    ],
    "main_indications": [
      "Kasa",
      "Shwasa",
      "Jwara",
      "Hikka"
    ],
    "image": "",
    "link": "https://www.amidhaayurveda.com/p/tulsi.html",
    "preview": "Tulsi (Ocimum sanctum) is known as the Queen of Herbs in Ayurveda. It boosts immunity, combats respiratory disorders, and possesses adaptogenic properties.",
    "pacify": [
      "Kapha",
      "Vata"
    ],
    "aggravate": [
      "Pitta"
    ],
    "tridosha": false,
    "rasa": [
      "Katu",
      "Tikta"
    ],
    "guna": [
      "Laghu",
      "Ruksha"
    ],
    "virya": "Ushna",
    "vipaka": "Katu",
    "prabhav": [
      "Rasayana",
      "Krimighna",
      "Kasahara",
      "Shoolaghna"
    ]
  }
]
```

---

## 🧬 Dataset Schema

| Field             | Type    | Description                   |
| ----------------- | ------- | ----------------------------- |
| name              | string  | Herb name                     |
| botanical_name    | string  | Scientific botanical name     |
| family            | string  | Botanical family              |
| english_name      | string  | Common English name           |
| sanskrit_synonyms | array   | Sanskrit names and synonyms   |
| part_used         | array   | Medicinal parts used          |
| main_indications  | array   | Primary Ayurvedic indications |
| image             | string  | Image URL                     |
| link              | string  | Herb page URL                 |
| preview           | string  | Short description             |
| pacify            | array   | Doshas pacified               |
| aggravate         | array   | Doshas aggravated             |
| tridosha          | boolean | Tridoshic classification      |
| rasa              | array   | Taste                         |
| guna              | array   | Qualities                     |
| virya             | string  | Potency                       |
| vipaka            | string  | Post-digestive effect         |
| prabhav           | array   | Specific actions              |

---

## ⚙️ How to Use

### Access the Raw Dataset

The complete JSON dataset can be accessed directly from this repository:

**Raw JSON URL**

https://raw.githubusercontent.com/sciencewithsaucee-sudo/herb-database/main/herb.json

### Integrate Into Projects

You may use the dataset for:

* Web applications
* Mobile applications
* Research projects
* Educational tools
* AI and machine learning projects
* Data visualizations
* Ayurveda informatics systems

Please provide proper attribution when using the dataset.

---

## 🧠 Research Purpose

This project bridges traditional Ayurvedic knowledge and digital knowledge systems, enabling:

* Computational Ayurveda research
* Educational resource development
* AI-assisted Ayurveda applications
* Open scientific collaboration
* Structured Ayurvedic data analysis

The long-term vision is to contribute toward an open Ayurvedic data ecosystem that supports education, innovation, and research worldwide.

---

## 🔄 Version History

### Version 2.0.0 (Current)

Major improvements include:

* Added botanical classification
* Added English names
* Added Sanskrit synonyms
* Added medicinal parts used
* Added main indications
* Standardized herb records
* Improved metadata quality
* Consolidated duplicate entries
* Removed formulation records
* Removed herb-part duplicate records

### Version 1.0.0 (Beta)

* Initial public release
* 700+ mixed herb records
* Core Ayurvedic pharmacological properties

---

## 🗳️ License & Citation

This dataset is released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0).**

You are free to:

* Share — copy and redistribute the material
* Adapt — remix, transform, and build upon it

Under the following terms:

* Appropriate attribution must be provided
* Indicate if changes were made
* Link to the license

### Citation

> Varshney, S. (2026). Amidha Ayurveda Herb Database v2.0. Open-source dataset of Ayurvedic medicinal plants. Zenodo. DOI: 10.5281/zenodo.17475351

Dataset Website:

https://www.amidhaayurveda.com/p/herb-database.html

---

## 🪟 Contributing

Contributions are welcome from students, researchers, developers, and Ayurveda enthusiasts.

You can help by:

* Improving data quality
* Reporting issues
* Suggesting corrections
* Enhancing documentation
* Developing tools that use the dataset

### Steps

1. Fork this repository
2. Make your improvements
3. Submit a pull request

---

## 🔗 DOI

**DOI:** https://doi.org/10.5281/zenodo.17475351

---

## 👨‍⚕️ About the Creator

This open-source project was developed by **Sparsh Varshney** to improve the accessibility, interoperability, and digital preservation of Ayurvedic knowledge.

### Connect

🌐 https://www.amidhaayurveda.com

💼 https://linkedin.com/in/sparshvarshney

📄 https://www.amidhaayurveda.com/p/about.html

---

## 💚 Vision

> "To create the world's first open Ayurvedic data ecosystem, empowering research, education, and innovation through structured open knowledge."

---

## License

This dataset is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

https://creativecommons.org/licenses/by/4.0/
