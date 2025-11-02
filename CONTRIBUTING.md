# 🌿 Contributing to Amidha Ayurveda – Open Herb Database (Beta)

Thank you for your interest in contributing to the **Amidha Ayurveda Open Herb Database** project! 🙏 This is an open, community-driven effort to digitize and organize Ayurvedic herbal knowledge for researchers, practitioners, and developers.

---

## 🧭 Project Overview

**Repository:** [Amidha Ayurveda – Open Herb Database (Beta)](https://github.com/sciencewithsaucee-sudo/herb-database)
**DOI:** [10.5281/zenodo.17475352](https://doi.org/10.5281/zenodo.17475352)
**Author:** Sparsh Varshney
**License:** MIT License

This project provides structured data on Ayurvedic herbs in JSON format. Each herb entry includes modern scientific details, Ayurvedic references, and usability for both academic and clinical contexts.

---

## 🧩 How You Can Contribute

Contributions are welcome from students, scholars, developers, and Ayurveda enthusiasts! Here’s how you can help:

### 1. 🪴 Add or Improve Herb Data

* Add new herbs with proper classical references and verified modern information.
* Improve existing entries (spelling, classification, new research data).
* Suggest structural improvements in the JSON schema.

### 2. 🧠 Suggest Features

Help improve the project scope by proposing new ideas such as:

* Filters (e.g., Rasa, Guna, Virya, Karma)
* Search and sort algorithms for front-end
* Integration with AI tools like **ShlokaAI** for Sanskrit–English translations or Ayurvedic inference
* Cross-linking with diseases, formulations, and research papers

### 3. 💻 Improve Documentation

You can:

* Fix typos or grammar
* Add missing explanations in README
* Write tutorials or usage examples for others

### 4. 🧪 Testing & Validation

* Verify data accuracy using authoritative Ayurvedic texts
* Report inconsistencies via GitHub Issues
* Suggest standardization (e.g., reference codes for Nighantus or texts)

---

## ⚙️ Contribution Workflow

1. **Fork** this repository
2. **Clone** your fork

   ```bash
   git clone https://github.com/your-username/herb-database.git
   ```
3. **Create a new branch**

   ```bash
   git checkout -b feature/new-herb
   ```
4. **Make your changes** (edit JSON files, documentation, etc.)
5. **Commit and push**

   ```bash
   git commit -m "Added data for [Herb Name]"
   git push origin feature/new-herb
   ```
6. **Create a Pull Request** on GitHub

> 📘 Please ensure your data sources are properly cited. Ayurvedic classical texts (Charaka, Sushruta, Bhavaprakasha, etc.) and modern references (PubMed, NCBI) are welcome.

---

## 🔍 Data Format Example

```json
{
  "herb_name_sanskrit": "Ashwagandha",
  "herb_name_latin": "Withania somnifera",
  "rasa": ["Madhura", "Tikta"],
  "guna": ["Laghu", "Snigdha"],
  "virya": "Ushna",
  "vipaka": "Madhura",
  "karma": ["Balya", "Rasayana", "Vatahara"],
  "part_used": ["Root"],
  "modern_research": "Adaptogenic, reduces stress, improves muscle strength",
  "source_reference": "Bhavaprakasha Nighantu – Haritakyadi Varga"
}
```

---

## 🪷 Guidelines

* Maintain **accuracy** and **authenticity**.
* Use **IAST transliteration** for Sanskrit terms.
* Respect **open-data ethics** — do not plagiarize or scrape copyrighted sources.
* Each herb must have at least **one classical reference**.

---

## 🧾 Citation

If you use this database in your research, please cite it as:

```bibtex
@misc{Varshney_Amidha_Ayurveda_2025,
  author = {Varshney, Sparsh},
  doi = {10.5281/zenodo.17475352},
  month = nov,
  title = {{Amidha Ayurveda – Open Herb Database (Beta)}},
  url = {https://github.com/sciencewithsaucee-sudo/herb-database},
  year = {2025}
}
```

---

## 🤝 Code of Conduct

This project follows the **Contributor Covenant Code of Conduct**. Please be respectful, inclusive, and open to discussion.

---

## 🌍 Vision

> To build the world’s most comprehensive **open-source Ayurvedic herb database**, bridging traditional wisdom and modern science for researchers, clinicians, and AI developers alike.

---

### 💫 Join the Community

* 🌐 Website: [Amidha Ayurveda](https://amidhaayurveda.com)
* 🧵 GitHub Discussions: Use the Discussions tab for Q&A
* ✉️ Contact: [amidhaayurveda@gmail.com](mailto:amidhaayurveda@gmail.com)

---

**Together, let’s digitize Ayurveda for the future.** 🙌
