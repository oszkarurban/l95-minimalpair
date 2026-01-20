# Hungarian Minimal Pair Dataset

The `hungarian_negation_preverb_minimal_pair.csv` contains a dataset of minimal pairs designed to evaluate the negatiin induced inversion of preverbs phenomena in Hungarian.

The code for the analysis of results for the submitted report can be found in L95_code.ipynb
---

## Experiment Types
The dataset is categorized into four distinct experiment types, each testing the robustness of the inversion rule under increasing syntactic conditions:

1. **Bare**: The fundamental contrast between grammatical and ungrammatical negation.
2. **Context**: Minimal pairs within a sentence to provide natural language grounding.
3. **Intervener**: Tests whether an adverbial element placed between the negation marker and the preverb-verb construction affects the inversion.
4. **Intervener 2**: A expansion of Intervener using a second adverbial intervener.

---

## Minimal Pair Columns

Each experiment is represented by a pair of columns containing the grammatical and ungrammatical text:

| Experiment | Grammatical String | Ungrammatical String |
| :--- | :--- | :--- |
| **Bare** | `grammatical` | `ungrammatical` |
| **Context** | `grammatical_context` | `ungrammatical_context` |
| **Intervener** | `grammatical_context_adverb` | `ungrammatical_context_adverb` |
| **Intervener 2** | `grammatical_context_adverb2` | `ungrammatical_context_adverb2` |

