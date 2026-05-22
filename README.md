# medical_clinical_discharge_summaries_nlp
**Dataset Description:**

This dataset is a large-scale collection of **Medical clinical discharge summaries**, designed to support the development of advanced healthcare AI and NLP systems.

It consists of real-world patient records collected from hospital environments, including detailed clinical information such as diagnosis, patient history, examination findings, treatment procedures, and discharge instructions.
The dataset captures authentic medical language, clinical terminology, and narrative-style documentation used by healthcare professionals. This makes it highly valuable for building accurate, scalable, and production-ready AI systems for healthcare analytics and decision support.
Additionally, this dataset can be used in pipelines for Supervised Fine-Tuning (SFT) and Reinforcement Learning with Human Feedback (RLHF) workflows.

**Key Use Cases**

    -Clinical NLP and medical text understanding
    -Disease prediction and classification systems
    -Automated discharge summary generation
    -Medical coding (ICD classification)
    -Clinical decision support systems
    -Information extraction from unstructured medical text
    -Healthcare analytics and reporting

**Dataset Specification**

    -Domain: Clinical Records
    -Content: Patient demographics, diagnosis, treatment, investigations
    -Data Nature: Real-world clinical narratives
    -Record Type: Patient discharge summaries
    -Patients: 2,364

**Value of This Dataset**

    -Enables real-world clinical NLP modeling
    -Useful for training healthcare-specific LLMs
    -Helps improve diagnosis prediction systems
    -Ideal for medical documentation automation
    -Facilitates accurate medical text annotation and labeling

**Basic JSON Schema**
```json
{
  "patient_id": "string",
  "age": "integer",
  "sex": "string",
  "department": "string",
  "admission_date": "string",
  "discharge_date": "string",
  "diagnosis": "string",
  "complaints": "string",
  "history": "string",
  "examination": "string",
  "hospital_course": "string",
  "investigations": "string",
  "discharge_advice": "string",
  "medications": "string",
  "full_text": "string",
  "metadata": {
    "source": "string",
    "hospital_type": "string",
    "record_type": "string"
  }
}
```

**Data Creation**

  Procured through formal agreements and generated in the ordinary course of business.

**Considerations**

  This dataset is provided for research and educational purposes only. It contains only sample data. For access to the full dataset and enterprise licensing options, please visit our website [InfoBay AI](https://infobay.ai/) or contact us directly.
   
    -Ph: (91) 8303174762
    -Email: datareq@infobay.ai
