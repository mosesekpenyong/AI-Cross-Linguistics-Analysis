# AI-Cross-Linguistics-Analysis
Code suit to perform AI-assisted syllabification and tone labelling analysis and visualization
This repository provides the full implementation of an adaptive, rule-based framework for preprocessing, and analyzing lexical, syllable, and tone patterns across low-resource Nigerian languages. The framework was designed to support cross-linguistic research in phonology, lexical typology, and computational language documentation.

Contents
1. syllabify_Nigerian_languages_Engine.ipynb
Purpose: Automates syllabification of transcribed words based on linguist-validated syllable structure rules.

Functionality:
Parses language-specific vowel (V), consonant (C), and syllabic nasal (N) inventories.
Applies rule-based syllabification using atomic graphemes and phonotactic constraints.
Generates syllabified outputs and syllable structure patterns (e.g., CV-CVC).

2. Tone_Labelling_Engine.ipynb
Purpose: Labels tones on syllables using annotated tone rules.

Functionality:
Assigns tone patterns to existing syllable forms.
Handles lexical tone, and tone bearing units (vowels and syllabic nasals).

3. Syllables_Tones_Evaluation.ipynb
Purpose: Provides a structured validation and evaluation of the syllabification and tone-labelling outputs.

Functionality:
Computes summary statistics on annotation accuracy.

4. Lexical_Identity_Syllabbification_Tone_Analysis.ipynb
Purpose: Integrates lexical analysis with syllabification and tonal structure to enable phonological typology and cross-linguistic comparison.

Functionality:
Analyzes a 108-Swadesh wordllistfor syllabic and tonal behavior.
Enables clustering and contrastive studies across languages.

Features
Language-specific rule parsing
Supports tone-bearing unit analysis
Compatible with Mendeley Data outputs
Designed for typological studies and NLP dataset preparation
