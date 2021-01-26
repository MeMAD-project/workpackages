# MeMAD Work Packages

Work packages in MeMAD with links to deliverabels and results

## Work package 4: Multimodal and multilingual machine translation

### Objectives

* Development of multilingual machine translation with multimodal input.
* Implementation and training of neural machine translation models with non-symbolic interlingual representations covering at least six EU languages, both minor and major.
* Development of discourse-oriented machine translation optimised for the dynamics of the narrative in the audiovisual data streams.
* Providing support for cross-lingual content retrieval based on automatic content analysis.

### Participants and person months

Helsinki: 33, Aalto: 15, Linecraft: 3, Surrey: 2, Yle: 2, Lingsoft: 1

### Description of work

* Task T4.1 Modelling multimodal machine translation (Aalto 6, Helsinki 6, Lingsoft 1) M1-12: The development of machine translation models that incorporate information from textual input (possibly automatically generated content descriptions) as well as audiovisual information.
* Task T4.2 Modelling discourse-aware machine translation (Helsinki 8, Surrey 2) M13-24: Development of models that capture the dynamics of the story in the audiovisual data by incorporating contextual features that go beyond sentence boundaries in the audio or beyond shot boundaries in the visual progression. Use of speaker information and dialogue, shot, and scene structures are used to improve coherence and cohesion.
* Task T4.3 Development of multilingual and multimodal translation engines (Helsinki 12, Aalto 9) M1-36: Development of neural machine translation models that can handle multiple languages in input and output using shared representations and multilingual training procedures. Multi-task learning will be used to integrate the various translation directions and the multilingual models will be integrated with the multimodal and discourse-aware models developed in tasks T4.1 and T4.2.
* Task T4.4 Cross-lingual retrieval of audiovisual data (Helsinki 7, Yle 2, Limecraft 3) M25-36: The use of machine translation in content retrieval is investigated in real environments with end-users. Multilingual material is a challenge for audiovisual archives and data collections and cross-lingual support is needed for efficient search in large databases of that kind. Machine translation must also be fitted in the production and management workflows.

### Deliverables

* [D4.1 Report on multimodal machine translation](https://zenodo.org/record/3690762) (M12)
* [D4.2 Report on discourse-aware machine translation for audio-visual data](https://zenodo.org/record/3690764) (M24) 
* D4.3 Tools and models for multimodal, multilingual and discourse-aware MT (M36)
* D4.4 Report on cross-lingual content retrieval based on automatic translation (M36)

### Research output and results

* [Subtitle translation](https://github.com/MeMAD-project/subtitle-translation)
* [Image caption translation](https://github.com/MeMAD-project/image-caption-translation)
* [Speech translation](https://github.com/MeMAD-project/speech-translation)
* [Discourse-aware machine transltion](https://github.com/MeMAD-project/doclevel-translation)
* [Cross-lingual content retrieval](https://github.com/MeMAD-project/cross-lingual-retrieval)

Tools and Resources:

* [OpenSubtitles2018: a large collection of aligned movie subtitles](http://opus.nlpl.eu/OpenSubtitles-v2018.php)
* [TED2020: Aligned TedTalk subtitles](http://opus.nlpl.eu/TED2020.php)
* [QED: Aligned subtitles of educational videos](http://opus.nlpl.eu/QED.php)
* [Document-level machine translation benchmarks](https://zenodo.org/record/3525366)
* [OPUS-MT: MT servers and pre-trained translation models](https://github.com/MeMAD-project/Opus-MT)
* [OPUS-MT-train: MT training procedures and pipelines](https://github.com/MeMAD-project/OPUS-MT-train)
* [OPUS-eval: A collection of MT benchmarks](https://github.com/MeMAD-project/OPUS-MT-eval)
* [The Tatoeba MT Challenge: Multilingual data sets and benchmarks for machine translation](https://github.com/Helsinki-NLP/Tatoeba-Challenge)
* [Tools for converting and aligning subtitles](https://github.com/MeMAD-project/subalign)
* [OPUS-CAT: MT plugins for professional translators](https://github.com/MeMAD-project/OPUS-CAT)
* [OPUS-translator: Web interface for machine translation](https://github.com/MeMAD-project/OPUS-translator)
