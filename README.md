# 🌿 Amidha Ayurveda – Open Herb Database (Beta)

**An open-source Ayurvedic herb dataset** for research, education, and innovation.
This project aims to make authentic Ayurvedic knowledge accessible in a structured, machine-readable format — connecting traditional wisdom with modern data science.

---

## 📖 Overview

The **Amidha Ayurveda Herb Database** contains detailed data on 700+ Ayurvedic herbs, including:

* **Botanical names** and Ayurvedic names
* **Rasa, Guna, Virya, Vipaka, Prabhava**
* **Dosha effects** (Pacify / Aggravate)
* **Therapeutic properties** and brief description
* **HTML links** for individual herb pages

This dataset is suitable for:

* Ayurvedic students & researchers
* Health-tech startups and AI developers
* Web & app builders using Ayurvedic knowledge
* Educators creating open educational content

---

## 💮 Sample Data Preview (JSON)

```json
[
  {
    "name": "Ashwagandha",
    "link": "/p/ashwagandha.html",
    "preview": "Ashwagandha (Withania somnifera) is a powerful adaptogen. It reduces stress, increases strength, and supports reproductive and nervous systems.",
    "pacify": ["Vata", "Kapha"],
    "aggravate": ["Pitta"],
    "tridosha": false,
    "rasa": ["Tikta", "Kashaya"],
    "guna": ["Guru", "Snigdha"],
    "virya": "Ushna",
    "vipaka": "Madhura",
    "prabhav": ["Balya", "Medhya", "Vrishya", "Rasayan"]
  }
]
```

---

## ⚙️ How to Use

1. **Access the dataset**
   You can use the raw JSON files directly from GitHub or integrate them via API endpoints hosted at [Amidha Ayurveda](https://amidhayurveda.com/p/herb-database.html).

2. **API Example**

   ```
   https://amidhayurveda.com/api/herbs.json
   ```

3. **Integrate with Projects**
   Use the data for web apps, AI models, educational tools, or research visualizations.
   Make sure to provide attribution as mentioned below.

---

## 🧠 Research Purpose

This project bridges **Ayurvedic textual data** with **digital knowledge systems**, helping:

* Students cite authentic herb data
* Researchers perform computational Ayurveda studies
* Developers build Ayurvedic APIs and tools

---

## 🧾 License & Citation

This dataset is released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0).**

You are free to:

* **Share** — copy and redistribute the material
* **Adapt** — remix, transform, and build upon it

Under the following terms:

* Attribution must be given to **Amidha Ayurveda**
* Non-commercial, educational, and research use is preferred

**How to Cite:**

> Amidha Ayurveda Herb Database (Beta), 2025. Open-source dataset for Ayurvedic research.
> Retrieved from [https://amidhayurveda.com/p/herb-database.html](https://amidhayurveda.com/p/herb-database.html)

---

## 🧹 Contributing

We welcome contributions from students, developers, and researchers!
You can:

* Add new verified herbs
* Improve descriptions or references
* Enhance data accuracy

### Steps:

1. Fork this repository
2. Edit or add your herb entry in JSON format
3. Submit a pull request

---

## 🔗 DOI (Digital Object Identifier)

A Zenodo DOI will be generated soon for official academic referencing.
*(Example placeholder)*
**DOI:** [10.5281/zenodo.1234567](https://zenodo.org/)

---

## 👨‍⚕️ About the Creator

This open-source project was developed by **Dr. Sparsh Varshney** to contribute to the accessibility and understanding of Ayurvedic knowledge in the digital era.

**Connect:**

* 🌐 [Amidha Ayurveda Website](https://amidhayurveda.com)
* 💼 [LinkedIn](https://linkedin.com/in/sparshvarshney)
* 📄 [About Page](https://amidhayurveda.com/p/about.html)

---

### 💚 Vision

> “To create the world’s first open Ayurvedic data ecosystem —
> empowering research, startups, and education through open knowledge.”
