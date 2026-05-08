# Vehicle Brand Text Dataset

## Overview

This dataset contains text descriptions of various vehicle models across multiple automotive brands. Each vehicle is stored as an individual `.txt` file containing a natural language description that can be used for prompt-based generation, NLP tasks, or multimodal AI applications.

---

## Dataset Structure

```bash
brand_texts/
├── Hyundai Creta.txt
├── Hyundai Verna.txt
├── Mahindra Scorpio.txt
├── Mahindra Thar.txt
└── ...
```

Each file corresponds to a single vehicle model.

---

## Usage

Example:

```python
with open("brand_texts/Hyundai Creta.txt", "r", encoding="utf-8") as f:
    prompt = f.read()

print(prompt)
```

---

## Applications

* Text-to-image generation
* Synthetic dataset creation
* Prompt engineering
* Automotive NLP tasks
* Vision-language research

---

## Notes

* Dataset contains only text descriptions.
* File names follow the format:

```text
<Brand> <Model>.txt
```
