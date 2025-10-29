# 🌿 Amidha Ayurveda – Open Herb Database (Beta)

**An open-source Ayurvedic herb dataset** for research, education, and innovation.  
This project aims to make authentic Ayurvedic knowledge accessible in a structured, machine-readable format — connecting traditional wisdom with modern data science.

---

## 📖 Overview

The **Amidha Ayurveda Herb Database** contains detailed data on 700+ Ayurvedic herbs, including:

- **Botanical names** and Ayurvedic names  
- **Rasa, Guna, Virya, Vipaka, Prabhava**  
- **Dosha effects** (Pacify / Aggravate)  
- **Therapeutic properties** and brief description  
- **HTML links** for individual herb pages  

This dataset is suitable for:
- Ayurvedic students & researchers  
- Health-tech startups and AI developers  
- Web & app builders using Ayurvedic knowledge  
- Educators creating open educational content  

---

## 💾 Sample Data Preview (JSON)

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
