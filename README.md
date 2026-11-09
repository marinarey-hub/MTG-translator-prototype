# A Computational and Translation-Based Approach to Magic: The Gathering Language

## About the Project

This project was developed as my Bachelor's Thesis (TFG) in Translation and Interlinguistic Mediation at the University of Valencia. It explores the intersection between translation, computational linguistics and the specialized language of *Magic: The Gathering*.

The main goal was to experiment with the implementation of a bilingual terminology glossary in a basic translation prototype, using Python and a rule-based approach rather than relying on language models or machine translation systems to handle terminology.

The prototype uses a glossary containing source terms, their Spanish equivalents and priority levels. It attempts to identify and translate terminology and expressions according to their importance, prioritizing specific terms and collocations over more generic matches.

In this repository you will find a xlsx document containing the glossary collected by me, a pdf document with the abstract and conclusions of my project, and the program itself.

## Scope and Limitations

**This project is an early-stage prototype, not a finished translation tool.**

I started developing it with very limited programming experience, learning Python from scratch as part of the research process. The purpose was primarily exploratory: to understand how a terminology glossary could be implemented computationally and to test whether a rule-based system could produce consistent translations without relying on language models.

The results revealed some of the limitations of this approach, particularly when dealing with grammatical structures, contextual dependencies and expressions whose meaning cannot be determined by translating their individual components.

One of the underlying ideas of this research was precisely to demonstrate that **translation requires a holistic, context-aware and fundamentally human approach**. Language cannot be treated as a puzzle in which individual words and expressions are translated separately and then simply assembled into a coherent sentence. Meaning depends on the relationships between linguistic elements, context and communicative purpose.

## Future Development

There are several possible directions for further development:

- **Integration of language models:** Improving the prototype by combining terminology prioritization with the contextual and linguistic capabilities of modern language models.
- **Context-aware translation:** Moving beyond isolated terminology matching towards a system capable of interpreting complete sentences and their context.
- **Practical application:** Exploring the development of an application that would make it easier for *Magic: The Gathering* players to use decks in different languages during games, helping them understand card text and terminology across language barriers.

## Technologies and Tools

- Python
- Jupyter Notebook
- CSV-based terminology management
- Rule-based terminology matching
- DeepL API (for comparison and experimentation)

---

*This project represents my first steps into programming and computational approaches to translation, and reflects my interest in exploring how linguistic knowledge and technology can work together.*
