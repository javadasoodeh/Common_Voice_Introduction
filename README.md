
### Introduction to Common Voice Platform

**Introduction:**
The Common Voice platform, created by Mozilla, aims to build a free, open-source dataset of diverse voices to improve speech recognition technologies. The goal is to make voice technology more inclusive and accessible, regardless of language, accent, or dialect. This advanced tutorial will cover the technical details of the platform, the purpose of each step in the data collection process, and provide a dataset view in table form for better understanding.

### Goals of Common Voice:

1. **Inclusivity:** To gather voices from different languages, dialects, and accents to ensure voice technology works for everyone.
2. **Accessibility:** To provide a free dataset that developers and researchers can use to improve and innovate voice technology.
3. **Community-Driven:** To engage language communities in the creation and validation of the dataset, ensuring it reflects real-world usage.

### How the Common Voice Platform Works:

**1. Contributing to the Dataset:**

**A. Reading Sentences:**
   - **Purpose:** To collect consistent, high-quality voice samples.
   - **Process:** Volunteers read pre-written sentences displayed on the platform.
   - **Technical Details:** Sentences are displayed on the platform, and recordings are captured using the device’s microphone.

**Example:**
   - You visit the Common Voice website.
   - You see the sentence, "The quick brown fox jumps over the lazy dog."
   - You click "Record" and read the sentence aloud.
   - Your recording is saved and added to the dataset.

**B. Spontaneous Speech:**
   - **Purpose:** To capture natural, conversational speech patterns.
   - **Process:** Volunteers respond to open-ended prompts or questions.
   - **Technical Details:** Prompts are displayed, and responses are recorded and stored. Speech-to-text algorithms may be used to assist with initial transcription.

**Example:**
   - You visit the Spontaneous Speech section on the Common Voice website.
   - You see a prompt like, "Describe your favorite book and why you like it."
   - You click "Record" and talk about your favorite book.
   - Your speech is recorded, transcribed, and added to the dataset.

**2. Reviewing Contributions:**

**A. Sentence Validation:**
   - **Purpose:** To ensure the quality and accuracy of recorded sentences.
   - **Process:** Volunteers listen to recordings and mark them as "Good" or "Bad."
   - **Technical Details:** A quality assurance algorithm may flag recordings for review based on factors like background noise or unclear speech.

**Example:**
   - You listen to a recording of someone saying, "The quick brown fox jumps over the lazy dog."
   - You verify that the sentence was read correctly and clearly.
   - You mark it as "Good."

**B. Transcription Review:**
   - **Purpose:** To verify the accuracy of transcriptions of spontaneous speech.
   - **Process:** Volunteers compare audio recordings to text transcriptions and make corrections if needed.
   - **Technical Details:** Transcriptions are reviewed in a dedicated interface that highlights discrepancies between the audio and text.

**Example:**
   - You listen to a recording of someone describing their favorite book.
   - You check the transcription to make sure it matches the spoken words accurately.
   - You approve the transcription if it is correct.

### Key Features of Common Voice:

**A. Domain Metadata:**
   - **Purpose:** To provide additional context and improve the usability of the dataset.
   - **Technical Details:** Metadata includes information such as speaker demographics, language, dialect, recording environment, and domain tags.

**Example of Metadata:**

| Audio File Name | Speaker Age | Speaker Gender | Language | Dialect | Environment | Domain Tags |
|-----------------|-------------|----------------|----------|---------|-------------|-------------|
| file1.wav       | 25          | Female         | English  | US      | Quiet       | Healthcare  |
| file2.wav       | 30          | Male           | Spanish  | MX      | Noisy       | Agriculture |

**B. Language Variants:**
   - **Supports different variants of languages (e.g., Brazilian Portuguese vs. European Portuguese).
   - Contributors can choose the variant they want to work with.

**Example:**
   - A contributor from Brazil can choose to record or review sentences specifically tagged as Brazilian Portuguese.

**C. Spontaneous Speech Platform:**
   - **Captures natural language use by asking volunteers to respond to prompts.
   - Supports social language variants and code-switching.

**Example:**
   - A prompt asks about daily routines, and a contributor responds with a mix of English and Spanish.
   - The recorded response captures natural code-switching between the two languages.

### Dataset Structure and Management:

**1. Data Storage:**
   - **Purpose:** To organize and store the collected voice data efficiently.
   - **Technical Details:** Data is stored in a cloud-based system, using a combination of file storage for audio files and databases for metadata.

**2. Metadata:**
   - **Purpose:** To provide additional context and improve the usability of the dataset.
   - **Technical Details:** Metadata includes information such as speaker demographics, language, dialect, recording environment, and domain tags.

**Example of Metadata:**

| Audio File Name | Speaker Age | Speaker Gender | Language | Dialect | Environment | Domain Tags |
|-----------------|-------------|----------------|----------|---------|-------------|-------------|
| file1.wav       | 25          | Female         | English  | US      | Quiet       | Healthcare  |
| file2.wav       | 30          | Male           | Spanish  | MX      | Noisy       | Agriculture |

**3. Data Access and API:**
   - **Purpose:** To provide easy access to the dataset for developers and researchers.
   - **Technical Details:** An API allows users to query the dataset based on various parameters (e.g., language, domain tags) and download the required audio files and metadata.

### Dataset View

Here’s a simplified view of how the dataset might look in table form:

| Audio File Name | Transcription                       | Speaker Age | Speaker Gender | Language | Dialect | Environment | Domain Tags |
|-----------------|-------------------------------------|-------------|----------------|----------|---------|-------------|-------------|
| file1.wav       | The quick brown fox jumps...        | 25          | Female         | English  | US      | Quiet       | General     |
| file2.wav       | Describe your favorite book.        | 30          | Male           | Spanish  | MX      | Noisy       | Education   |
| file3.wav       | Hola, ¿cómo estás?                  | 22          | Female         | Spanish  | ES      | Quiet       | Healthcare  |
| file4.wav       | I switch between English and...     | 40          | Male           | English  | IN      | Quiet       | CodeSwitch  |

### Step-by-Step Process Explanation

**1. Sentence Collection and Recording:**
   - **Technical Detail:** Sentences are sourced from various public domain texts or created by volunteers. The platform ensures diversity in sentence length and complexity to capture a range of speech patterns.
   - **Purpose:** To gather a wide variety of spoken data for training robust speech recognition models.

**2. Audio Quality Assurance:**
   - **Technical Detail:** Audio recordings are analyzed for quality using signal processing techniques. Factors like background noise, clipping, and speech clarity are assessed.
   - **Purpose:** To maintain high standards in the dataset, ensuring it is useful for training accurate models.

**3. Data Annotation and Metadata Tagging:**
   - **Technical Detail:** Metadata is automatically and manually added to each recording. Automated tagging can include aspects like speaker demographics based on user profiles, while manual tagging involves domain-specific labels.
   - **Purpose:** To provide rich, searchable context that enhances the dataset's utility for specific applications.

**4. Transcription and Validation:**
   - **Technical Detail:** Speech-to-text systems provide initial transcriptions, which are then validated and corrected by volunteers. The platform uses a user-friendly interface to streamline this process.
   - **Purpose:** To ensure the transcriptions are accurate, which is crucial for training and evaluating speech recognition models.

**5. Dataset Distribution:**
   - **Technical Detail:** The dataset is made available through a public API. Users can query and download subsets of the data based on their needs (e.g., specific languages, dialects, or domain tags).
   - **Purpose:** To facilitate easy access to the data for developers, researchers, and other stakeholders.

### Conclusion

The Common Voice platform by Mozilla is a comprehensive and inclusive project designed to create a diverse dataset for speech recognition. By understanding the technical details and the purpose of each step, contributors and users can better appreciate the effort involved in making voice technology accessible to everyone. This tutorial should equip you with the knowledge to contribute effectively and utilize the dataset in your projects.

**Get Involved:**
- Visit the [Common Voice website](https://commonvoice.mozilla.org) to start contributing.
- Record your voice, review contributions, and help build a diverse and inclusive voice dataset.

By participating in Common Voice, you help shape the future of voice technology, ensuring it serves and reflects the diversity of our global community.

### Diagram showing the process
![Common Voice Dataset Process](https://github.com/javadasoodeh/Common_Voice_Introduction/raw/main/diagram.png)

### References
- [Common Voice 2024 Roadmap](https://www.youtube.com/watch?v=JyPEZhMCfcU)

- [Mozilla Common Voice Website](https://commonvoice.mozilla.org/)
