# KeyShot-Studio-AI-Shots-Prompt-Assistant
Help KeyShot users author optimized AI prompts for the Restyle, Imagine, and Background modes.

# 📘 KeyShot AI Prompt Assistant

**Version:** 2.0
**Author:** Don Tuttle
**Purpose:** This assistant helps KeyShot users write optimized, structured prompts for the AI-driven **Restyle**, **Imagine**, and **Background** modes — streamlining creative workflows and boosting ideation speed.

---

## 🎯 What This Assistant Does

This GPT is designed to support 3D designers, creative leads, and product teams in authoring **clean, targeted, and imaginative prompts** for KeyShot’s integrated AI tools. It turns vague ideas into production-ready directions, with built-in knowledge of:

* CMF design strategies (color, material, finish)
* Visual storytelling for product renders
* Background/environment integration
* Creative exploration through mood and lighting
* AI rendering constraints in KeyShot

---

## 🧠 Supported KeyShot AI Modes

| Mode         | Description                                                                         |
| ------------ | ----------------------------------------------------------------------------------- |
| 🎨 Restyle   | Transform the look, materials, and lighting of a render while preserving structure. |
| 🌌 Imagine   | Quickly create new scenes, moods, or visual themes — no modeling required.          |
| 🏙️ Background | Generate contextual environments behind your product without changing the subject.  |

---

/docs/
│
├── ToC.txt                     # Table of Contents (optional, helpful for navigation)
│
├── AI_Tool_Overview.txt        # General overview of KeyShot AI functionality
├── Restyle_Mode_Guide.txt      # Creative and structural guidance for Restyle Mode
├── Imagine_Mode_Guide.txt      # Ideation and exploration usage for Imagine Mode
├── Background_Mode_Guide.txt     # Contextual background generation for Background Mode
├── Prompt_Template_Library.txt # Prompt templates, vocab, and examples
├── Example_Use_Cases.txt       # Real-world scenarios across roles and industries
├── GPT_Guidelines.txt          # Behavior, constraints, system logic for the GPT
│
└── README.txt                  # Intro, usage, purpose, and directory map


---

## 📂 Document Summaries

| File                          | Description                                                                  |
| ----------------------------- | ---------------------------------------------------------------------------- |
| `AI_Tool_Overview.txt`        | Explains all three KeyShot AI modes and their functional design.             |
| `Restyle_Mode_Guide.txt`      | Focuses on CMF styling prompt strategies.                                    |
| `Imagine_Mode_Guide.txt`      | Enables creative concept generation for moodboards and exploration.          |
| `Background_Mode_Guide.txt`     | Helps frame your product render with a matching environment.                 |
| `Prompt_Template_Library.txt` | Provides ready-to-use templates, vocab lists, and scene formatting tools.    |
| `Example_Use_Cases.txt`       | Real-world scenarios with prompts to help new users understand applications. |

---

## ✅ Usage Recommendations

1. **Select your KeyShot AI mode** based on your design need.
2. Use the appropriate **prompt template** from the library.
3. Refine your intent using material, lighting, mood, or storytelling vocabulary.
4. Paste your finished prompt into the KeyShot AI tool to generate your visual.
5. Iterate and reuse prompts to build consistent visual systems.

---

## 🔐 GPT-Specific Behavior

* Avoids technical jargon (e.g., HDRI, UV mapping, 2:1 aspect).
* Prioritizes product clarity, environment realism, and scene coherence.
* Never includes people, brands, or vehicles.
* Does not perform rendering — only prompt generation.

---

## 🤝 Contributions & Customization

This assistant is designed for creative flexibility. Future enhancements can include:

* Custom verticals (e.g., automotive, fashion, medtech)
* Prompt pack libraries
* Workflow integrations with KeyShot Studios or client brands

---

## 🧩 Versioning Notes

This version is based on KeyShot AI’s official tool capabilities for KeyShot 2026.1 and aligned with the Qwen image generation model’s structured prompt handling logic.

For updates, expand the `docs/` folder with new industry verticals or mood-specific prompt packs.

---

## 🧠 AI Model: Qwen Structured Prompting

As of KeyShot 2026.1, the AI engine uses the **Qwen** image generation model. Qwen responds best to **structured, attribute-based prompts** rather than freeform cinematic descriptions. All prompt templates in this knowledge base follow the structured prompt grammar:

```
SUBJECT → COMPOSITION → ENVIRONMENT → LIGHTING → MATERIALS → COLOR → CAMERA → STYLE → QUALITY → EXCLUSIONS
```

This approach treats prompt authoring as a **semantic render pipeline** — mapping each field to a stage in the rendering process (geometry, scene, illumination, shading, sensor, render intent, error control).

---
