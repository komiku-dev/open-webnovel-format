<div align="center">
  <img src="/assets/wordmark.png" alt="Komiku Wordmark" width="600"/>
</div>

---

> [!NOTE]
> **This is an open-source initiative by Komiku** to create a modern, dynamic, and accessible file format standard for webnovels.

---

### Table of Contents

- [📜 About the Project](#-about-the-project)
  - [The Vision](#the-vision)
  - [The Problem](#the-problem)
  - [Our Motivation](#our-motivation)
- [📦 The Format Explained](#-the-format-explained)
  - [The Book & Chapter System](#the-book--chapter-system)
  - [Key Benefits](#key-benefits)
- [🛠️ Specification](#️-specification)
- [❤️ Contributing](#️-contributing)

---

## 📜 About the Project

### The Vision

The **WebNovel Standard** redefines digital fiction not as a simple block of text, but as a structured, portable, and intelligent document. We envision a future where webnovels are effortlessly translatable, fully accessible, and completely independent of any single platform. By creating a clear separation between content, formatting, and metadata, this standard empowers authors, translators, and platforms to build and share stories that are ready for a global, interconnected audience.

### The Problem

Today, the world of webnovels is built on a foundation of fragmented and inadequate formats. This creates a chaotic ecosystem that hinders authors and stifles innovation.

* **Plain text files (`.txt`)** are portable but primitive, stripping away vital formatting and metadata.
* **Word processor documents (`.docx`)** are designed for print, making them bloated, difficult for web applications to parse, and poor at handling the structured data needed for dynamic experiences.
* **Platform "walled gardens"** lock an author's life's work into a single service, making backups difficult and preventing authors from moving their content or using their own tools.
* **E-book Formats (`.epub`)** are excellent *distribution* formats, but they are not suited for the *authoring* process. They are the final, packaged product, not the living document that a writer edits, revises, and translates.

### Our Motivation

The WebNovel Standard isn't just a theoretical exercise; it's our answer to the real-world frustrations we faced building our own platform. We repeatedly confronted the inefficiencies caused by a lack of a unified format and saw how much it hurt both creators and the teams working to support them. Instead of building another proprietary solution on top of a flawed system, we decided to tackle the root of the problem and create an open, modern, and efficient standard that benefits everyone in the webnovel community.

---

## 📦 The Format Explained

### The Book & Chapter System

The standard uses a professional two-format system that separates the organization of the entire novel from the content of individual chapters.

* **The Book File: `.wnb`**
    The master file for an entire novel. This is a container that organizes all chapters, manages their reading order, and holds book-level metadata like the main title and cover art. It is the "project file" for the whole story.

* **The Chapter File: `.wnc`**
    The file for a single chapter. This is a self-contained, portable package that holds the rich text content in multiple languages, chapter-specific metadata, and associated images.

### Key Benefits

#### For Authors & Translators

This format is built to make your life easier. By separating content from presentation and providing clear structure, it creates a more professional workflow. The translation process is radically simplified—instead of juggling dozens of separate documents, translators can work with a single file containing parallel languages. Workflow statuses (`draft`, `final`) allow teams to track progress efficiently, and the non-destructive nature of the format means your original work is always preserved.

#### For Platforms & Readers

For the first time, webnovels can become truly accessible. Because text is semantically structured, it can be easily read aloud by screen readers or restyled for user comfort. The translation-native design allows platforms to offer on-the-fly language switching. This new foundation enables innovative features, lightning-fast content parsing, and a unified standard that developers can build upon with confidence.

---

## 🛠️ Specification

> [!WARNING]
> The full v1.0 specification for the `.wnc` and `.wnb` formats is currently under active development. Community feedback during this phase is highly encouraged and deeply valued.

---

## ❤️ Contributing

This is an open initiative, and we believe the best standards are built by a community. We welcome contributions of all kinds, from technical feedback and specification proposals to documentation improvements and tool development.

If you want to help shape the future of digital storytelling, please feel free to open an issue to share your thoughts or reach out to us directly at **oss@komiku.moe**.