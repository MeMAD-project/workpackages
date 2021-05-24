# MeMAD Work Packages

Work packages in MeMAD with links to deliverables and results

## Work package 1: Data collection and management

### Objectives

* Defining, collecting and making available suitable datasets of media, content descriptions and metadata for the project to use.
* Collecting and managing datasets created by the project.

### Partners

Yle (WP leader), Limecraft, Aalto University, EURECOM, University of Surrey, Lingsoft, INA, University of Helsinki

### Description of work

* Task T1.1 Data identification, preparation and delivery to partners: Identifying media and other data needed for the different work packages, acquiring and if need be, licensing it. Technical transcodings and other preparations and making the media data set available to project partners.
* Task T1.2 Project result data collection and curating for the project’s needs: Planning the data collection and distribution process. Design a data collection and distribution platform inside the project. Maintaining the platform and improving it during the project.
* Task T1.3 Project legacy dataset collection, selection and storing in relevant repositories: Project results, working material and media are curated into a collection of project legacy datasets. Parts of this collection may be published also during the project.

### Deliverables

* [D1.1 Data management plan](https://zenodo.org/record/4327654)
* D1.2 Collection of annotated video data to be used in following work packages
* D1.3 Data collection and distribution platform, first version
* [D1.4 Data management plan, update 1](https://zenodo.org/record/4327675)
* D1.5 Data collection and distribution platform, final version
* D1.6 Data management plan, update 2
* D1.7 Collection of annotations and / or video data resulting from the projec

### Research output and results

[Combining and Curating Automated Metadata from Multiple Sources](https://zenodo.org/record/4058122)


## Work package 2: Automatic multimodal content analysis

### Objectives

* Development of video, audio and speech content analysis techniques for indexing and description.
* Evaluation of the developed techniques with standard benchmark and evaluation campaign data
* Connecting content analysis input and output with translation, linked data and human processing.
* Providing methods and results for human processing and evaluation and system integration.

### Partners

Aalto University (WP leader), EURECOM, INA, Lingsoft, University of Helsinki, University of Surrey, Yle

### Description of work

* Task T2.1 Development of automatic tools for multimodal content analysis: Development of basic machine learning based techniques that utilize deep convolutional and recurrent neural networks for visual, speech and other audio media content description in uni- and multimodal fashions.
* Task T2.2 Using human input to multimodal content analysis: Development of models that can utilize human-like content description (verbal-visual relations, long narratives and recurrent object referrals in multiple languages) as inputs. The models are informed by: (i) users’ understanding of media, and their needs in the media enrichment; (ii) theoretical concepts relating to multimodal analysis; and, (iii) knowledge of what aspects of multimedia content can be captured by automatically extracted features, and from existing metadata.
* Task T2.3 Generating human-like narrative media content description. Development of multi-layered models that can generate human-like descriptions for videos, taking into account both the visual and aural domains and referring to the recurrent objects and persons in intelligent ways.

### Deliverables

* [D2.1 Libraries and tools for multimodal content analysis](https://zenodo.org/record/3697989)
* D2.2 Implementations of methods adapted to enhanced human inputs
* D2.3 Software and demonstration of human-like content description generation

### Research output and results

 * [mmca collection of software](https://github.com/MeMAD-project/mmca)
 * [PicSOM](https://github.com/aalto-cbir/PicSOM)
 * [DeepCaption](https://github.com/aalto-cbir/DeepCaption)
 * [Visual storytelling](https://github.com/aalto-cbir/visual-storytelling)
 * [Speech recognition training scripts for Finnish](https://github.com/psmit/char-fin-2017)
 * [Speaker-aware ASR training](https://github.com/MeMAD-project/speaker-aware-attention-asr)
 * [SphereDiar](https://github.com/Livefull/SphereDiar)
 * [Multimodal ASR](https://github.com/aalto-speech/avsr)
 * [Spoken language identification](https://github.com/py-lidbox/lidbox)
 * [Audio event classification](https://github.com/MeMAD-project/AudioTagger)
 * [Statistical tools for caption dataset analysis](https://github.com/MeMAD-project/statistical-tools)
 * [Face recognition](https://github.com/D2KLab/FaceRec)
 * [inaSpeechSegmenter](https://github.com/ina-foss/inaSpeechSegmenter)
 * [inaFaceGender](https://github.com/ina-foss/inaFaceGender)
 * [Models for MeMAD language identification pipeline](https://zenodo.org/record/4486873)

## Work package 3: Media enrichment and hyperlinking

### Objectives

* Define the set of back-end microservices supporting the MeMAD workflow: content analysis, moments detection, annotation and enrichment services.
* Services are implemented as APIs, tested, adapted and refined, based on WP1 data, WP2 results, WP3 internal tests and WP6 evaluations.

### Partners

EURECOM (WP leader), Aalto University, Lingsoft, INA, Limecraft, Yle

### Description of work

* Task T3.1 TV programme semantic annotation: ASR results, script and automatic transcription are converted to time-aligned and isambiguated entity names, initially for some common types and some languages, later to larger vocabularies and more languages.
* Task T3.2 TV moments detection: Identification of “micro-moments” which lead to viewer interest to content enrichments according to the particular content of the programme. The automatic segmentation of the TV program performed in WP2 will is a key input for the TV moments detection.
* Task T3.3 TV moments linking: Different enrichment services that will be triggered by the moments detected in the task T3.2. Enrichments will be composed of news articles automatically retrieved and promoted by the broadcaster, related videos and video excerpts and visualization of data analytics performed on social media enhanced by data extracted from knowledge graphs such as Wikidata and DBpedia.

### Deliverables

* D3.1 TV programme annotation model
* D3.2 TV moments detection and linking, initial version
* D3.3 TV moments detection and linking, final version

### Research output and results

 * [Media memorability in MediaEval 2019-20](https://github.com/MeMAD-project/media-memorability)
 * [MeMAD metadata converter](https://github.com/MeMAD-project/rdf-converter)
 * [MeMAD Knowledge Graph API](https://github.com/MeMAD-project/api)
 * [MeMAD Explorer](https://github.com/MeMAD-project/explorer)


## Work package 4: Multimodal and multilingual machine translation

### Objectives

* Development of multilingual machine translation with multimodal input.
* Implementation and training of neural machine translation models with non-symbolic interlingual representations covering at least six EU languages, both minor and major.
* Development of discourse-oriented machine translation optimised for the dynamics of the narrative in the audiovisual data streams.
* Providing support for cross-lingual content retrieval based on automatic content analysis.

### Partners

University of Helsinki (WP leader), Aalto University, Limecraft, University of Surrey, Yle, Lingsoft

### Description of work

* Task T4.1 Modelling multimodal machine translation: The development of machine translation models that incorporate information from textual input (possibly automatically generated content descriptions) as well as audiovisual information.
* Task T4.2 Modelling discourse-aware machine translation: Development of models that capture the dynamics of the story in the audiovisual data by incorporating contextual features that go beyond sentence boundaries in the audio or beyond shot boundaries in the visual progression. Use of speaker information and dialogue, shot, and scene structures are used to improve coherence and cohesion.
* Task T4.3 Development of multilingual and multimodal translation engines: Development of neural machine translation models that can handle multiple languages in input and output using shared representations and multilingual training procedures. Multi-task learning will be used to integrate the various translation directions and the multilingual models will be integrated with the multimodal and discourse-aware models developed in tasks T4.1 and T4.2.
* Task T4.4 Cross-lingual retrieval of audiovisual data: The use of machine translation in content retrieval is investigated in real environments with end-users. Multilingual material is a challenge for audiovisual archives and data collections and cross-lingual support is needed for efficient search in large databases of that kind. Machine translation must also be fitted in the production and management workflows.

### Deliverables

* [D4.1 Report on multimodal machine translation](https://zenodo.org/record/3690762)
* [D4.2 Report on discourse-aware machine translation for audio-visual data](https://zenodo.org/record/3690764)
* [D4.3 Tools and models for multimodal, multilingual and discourse-aware MT](https://zenodo.org/record/4630083)
* [D4.4 Report on cross-lingual content retrieval based on automatic translation](https://zenodo.org/record/4639513)

### Research output and results

* [Subtitle translation](https://github.com/MeMAD-project/subtitle-translation)
* [Image caption translation](https://github.com/MeMAD-project/image-caption-translation)
* [Speech translation](https://github.com/MeMAD-project/speech-translation)
* [Discourse-aware machine transltion](https://github.com/MeMAD-project/doclevel-translation)
* [Cross-lingual content retrieval](https://github.com/MeMAD-project/cross-lingual-retrieval)
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


## Work package 5: Human processing in multimodal content description and translation

### Objectives

* Understand the main principles, techniques and strategies of human video description.
* Identify differences and commonalities of human and machine-based video description.
* Build a human-based model of video description applicable to various usage situations.
* Develop a prototype application for review/editing machine-generated video descriptions.

### Partners

University of Surrey (WP leader), Limecraft, Aalto University, University of Helsinki, Yle, INA

### Description of work

* Task T5.1 Multimodal annotation of described video: A set of audiovisual material that has audio description and subtitles in at least one project language will be transcribed as necessary and annotated with information about relevant visual, auditory and verbal elements. These elements will then be aligned with the corresponding information in the audio description and subtitles. The dataset will be used as research data in T5.2/T5.3 and as training data in T2.2/T2.3.
* Task T5.2 Key characteristics of human and machine video description: Comparative analyses of human content descriptions with corresponding machine-based video descriptions from T2.1 and T2.2 to identify characteristic features and patterns of each method.
* Task T5.3 Modelling human video description: Modelling of the human processes of content description, drawing on knowledge about multimodal translation of audiovisual content and the insights from T5.2 . Several models are expected to come out, ranging from a keyword level to complex multi-sentence descriptions. The models will be used in T2.3 and T4.3 to inform the machine in learning to describe.
* Task T5.4 Prototype application to review and edit machine generated content descriptions: In this task, we will deliver a prototype application that serves the producer, by which he can review and edit the machine generated content descriptions, taking into account the conclusions of T5.1, T5.2 and T5.3.

### Deliverables

* D5.1 Multimodally annotated dataset of described video
* D5.2 Report on comparative analysis of human and machine video description
* D5.3 Best Practice Guide for Video Description
* D5.4 Prototype application to manipulate the video description

### Research output and results

* [MeMAD_ Surrey dataset](https://zenodo.org/record/4727751)

## Work package 6: Integration and evaluations

### Objectives

* Specify the data interchange formats, including inputs and outputs of the processes.
* Implement three distinct iterations of the tools and methods developed in WP2-5, for evaluations with end users, and eventually dissemination and exploitation.
*  Formal and systematic evaluation of the tools and methods developed by WP2-WP5 as well as of the solution as a whole, for each of the use cases UC1-4.

### Partners

Limecraft (WP leader), EURECOM, University of Surrey, Lingsoft, Aalto University, University of Helsinki, Yle, INA

### Description of work

* Task T6.1 Specification of the data interchange formats: All partners collaborate in the process of setting the specifications and requirements. This task will yield one iteratively updated deliverable, i.e. the formal specification of the data interchange formats.
* Task T6.2 Prototype implementation: Limecraft will take the lead in the functional integration and deployment of the technologies delivered by WP2-5.
* Task T6.3 Evaluation: Each implementation iteration will be concluded by an evaluation phase of three months. This task yields one formal deliverable, which is the final evaluation report in which we plan to consolidate the results of the three evaluation cycles.

### Deliverables

* D6.1 Specification of the data interchange format, initial version
* D6.2 MeMAD prototype, initial version
* D6.3 Evaluation report, initial version
* D6.4 Specification of the data interchange format, intermediate version
* D6.5 MeMAD prototype, intermediate version
* D6.6 Evaluation report, intermediate version
* D6.7 Specification of the data interchange format, final version
* D6.8 MeMAD prototype, final version
* D6.9 Evaluation report, final version

### Research output and results

 * [Video content segmentation](https://github.com/MeMAD-project/content-segmentation)
 * [MeMAD metadata interchange formats](https://github.com/MeMAD-project/interchange-formats)

