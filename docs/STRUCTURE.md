# Repository Structure

This document outlines the complete directory and file structure of the BAC-2026 English Study Guide repository. Understanding this structure will help contributors navigate the project, locate relevant content, and maintain consistency.

```
BAC-2026/
├── .github/                       # GitHub-specific configurations (issue templates, PR templates, workflows)
├── assets/                        # General assets like icons, logos, illustrations
├── cheatsheets/                   # Quick reference guides and summary sheets
├── diagrams/                      # Visual representations, flowcharts, mind maps
├── docs/                          # Project documentation (e.g., this structure guide, contribution guidelines)
│   └── STRUCTURE.md               # This file
├── exams/                         # Past Baccalaureate exams, mock exams, practice tests
│   ├── Past-Papers/               # Official past exam papers
│   ├── Mock-Exams/                # Simulated full-length exams
│   ├── Practice-Tests/            # Shorter, focused practice tests
│   ├── Timed-Exams/               # Exams designed for timed practice
│   ├── Answer-Keys/               # Solutions for all exams
│   ├── Mark-Schemes/              # Grading criteria for exams
│   └── Exam-Analysis/             # Detailed analysis of exam patterns and common mistakes
├── exercises/                     # General exercises for various topics
├── flashcards/                    # Digital and printable flashcards for vocabulary and concepts
├── grammar/                       # Comprehensive grammar lessons and exercises
│   ├── Tenses/                    # Lessons on verb tenses
│   ├── Passive/                   # Lessons on passive voice
│   ├── Reported-Speech/           # Lessons on reported speech
│   ├── Conditionals/              # Lessons on conditional sentences
│   ├── Relative-Pronouns/         # Lessons on relative pronouns
│   ├── Articles/                  # Lessons on articles (a, an, the)
│   ├── Prepositions/              # Lessons on prepositions
│   ├── Modals/                    # Lessons on modal verbs
│   ├── Word-Formation/            # Lessons on word formation (prefixes, suffixes)
│   ├── Linking-Words/             # Lessons on conjunctions and linking adverbs
│   ├── Question-Tags/             # Lessons on question tags
│   ├── Phrasal-Verbs/             # Lessons on phrasal verbs
│   ├── Irregular-Verbs/           # Lists and exercises for irregular verbs
│   ├── Practice/                  # Practice exercises for grammar topics
│   └── PDF/                       # Printable grammar resources
├── images/                        # General images used across the repository (not specific to units)
├── printable/                     # Resources designed for printing (e.g., worksheets, blank templates)
├── quizzes/                       # Interactive quizzes for self-assessment
├── reading/                       # Reading comprehension passages and strategies
│   ├── Question-Types/            # Explanation of different question types
│   ├── Strategies/                # Reading comprehension strategies
│   ├── Examples/                  # Example passages with guided analysis
│   ├── Exercises/                 # Practice exercises
│   ├── Solutions/                 # Solutions to reading exercises
│   ├── Common-Mistakes/           # Common pitfalls in reading comprehension
│   ├── Speed-Reading/             # Techniques for speed reading
│   ├── Keyword-Detection/         # Strategies for identifying keywords
│   ├── Inference/                 # Lessons on inferring meaning
│   ├── Synonyms/                  # Vocabulary related to synonyms
│   ├── Antonyms/                  # Vocabulary related to antonyms
│   ├── Reference-Questions/       # Lessons on reference questions
│   ├── True-False/                # Exercises for true/false questions
│   └── Gap-Filling/               # Exercises for gap-filling questions
├── references/                    # External references, academic papers, style guides
├── templates/                     # Reusable templates for various content types (e.g., essay templates)
├── translations/                  # Translated content (e.g., key terms in Arabic/French)
├── units/                         # Content organized by official Baccalaureate units
│   ├── Unit-01-Ethics-in-Business/
│   │   ├── README.md              # Unit overview and objectives
│   │   ├── summary.md             # Concise summary of the unit
│   │   ├── vocabulary.md          # Unit-specific vocabulary list
│   │   ├── verbs.md               # Key verbs for the unit
│   │   ├── expressions.md         # Common expressions for the unit
│   │   ├── grammar.md             # Grammar points relevant to the unit
│   │   ├── reading.md             # Reading passages for the unit
│   │   ├── writing.md             # Writing tasks for the unit
│   │   ├── mindmap.md             # Mind map of unit concepts
│   │   ├── flashcards.md          # Flashcards for unit vocabulary/concepts
│   │   ├── cheatsheet.md          # Quick reference for the unit
│   │   ├── practice/              # Practice exercises for the unit
│   │   ├── quiz/                  # Quizzes for the unit
│   │   ├── images/                # Images specific to the unit
│   │   └── pdf/                   # Printable PDF resources for the unit
│   ├── Unit-02-Science-and-Technology/ # Similar structure as Unit 01
│   ├── Unit-03-Sustainable-Development/ # Similar structure as Unit 01
│   └── Unit-04-Citizenship-and-Global-Issues/ # Similar structure as Unit 01
├── vocabulary/                    # General vocabulary lists, organized by theme, difficulty, etc.
│   ├── Theme/                     # Vocabulary organized by themes
│   ├── Difficulty/                # Vocabulary organized by difficulty levels
│   ├── Frequency/                 # High-frequency vocabulary
│   ├── BAC-Units/                 # Vocabulary specific to BAC units (cross-referenced)
│   ├── Alphabetically/            # Alphabetical vocabulary lists
│   ├── Flashcards/                # Flashcards for general vocabulary
│   ├── Images/                    # Visual vocabulary aids
│   ├── PDF/                       # Printable vocabulary resources
│   ├── CSV/                       # Vocabulary in CSV format
│   └── JSON/                      # Vocabulary in JSON format
├── website/                       # Files related to the GitHub Pages/Docusaurus website deployment
│   ├── Homepage/                  # Homepage content
│   ├── Documentation/             # Website documentation
│   ├── Search/                    # Search functionality assets
│   ├── Sidebar/                   # Sidebar configuration
│   ├── Dark-Mode/                 # Dark mode styling
│   ├── Navigation/                # Navigation structure
│   ├── Interactive-Quizzes/       # Interactive quiz components
│   ├── Download-PDFs/             # PDF download links
│   └── Progress-Tracker/          # Progress tracking components
├── .gitignore                     # Specifies intentionally untracked files to ignore
├── CONTRIBUTING.md                # Guidelines for contributing to the project
├── EXAM_STRATEGY.md               # Strategies and tips for the Baccalaureate exam
├── LEARNING_ROADMAP.md            # Detailed learning path and phase breakdown
├── LICENSE.md                     # Project license information
├── README.md                      # Project overview, mission, vision, and quick start guide
└── RESOURCES.md                   # Curated list of external learning resources
```

## Description of Every Folder and File

*(This section will be expanded with detailed descriptions for each folder and key files, explaining their purpose and content. For now, the tree structure provides a high-level overview.)*

## Navigation Hierarchy

The content is organized hierarchically to facilitate easy navigation:

*   **Root Level:** Core project files, main documentation, and top-level directories.
*   **Category Level:** Major subject areas like `grammar`, `vocabulary`, `reading`, `writing`, `units`, `exams`.
*   **Sub-Category Level:** Specific topics within each category (e.g., `grammar/Tenses`, `vocabulary/Theme`).
*   **Lesson Level:** Individual lessons or specific content files within sub-categories.

## Documentation Strategy

All documentation is written in Markdown (`.md`) for readability and ease of contribution. Key documentation files include:

*   `README.md`: Project overview.
*   `CONTRIBUTING.md`: Contribution guidelines.
*   `LEARNING_ROADMAP.md`: Detailed study plan.
*   `EXAM_STRATEGY.md`: Exam preparation strategies.
*   `docs/STRUCTURE.md`: This document, detailing the repository structure.

## GitHub Best Practices

*   **Branching Model:** We use a feature-branch workflow. All contributions should be made on separate branches and merged via Pull Requests.
*   **Commit Messages:** Follow the Conventional Commits specification for clear and consistent commit history.
*   **Issue Tracking:** Use GitHub Issues for bug reports, feature requests, and general discussions.
*   **Pull Requests:** All changes must go through a Pull Request review process.

## Naming Conventions

*   **Folders:** Use `kebab-case` (e.g., `unit-01-ethics-in-business`).
*   **Files:** Use `kebab-case` for Markdown files (e.g., `learning-roadmap.md`).
*   **Images/Assets:** Use `kebab-case` (e.g., `project-banner.png`).

## Markdown Template for Every Lesson

Every lesson Markdown file should follow this structure:

```markdown
# Lesson Title

## Learning Objectives

*   Objective 1
*   Objective 2

## Prerequisites

*   Prerequisite 1
*   Prerequisite 2

## Estimated Time

*   e.g., 30 minutes - 1 hour

## Theory

*(Detailed explanation of the lesson's concept.)*

## Examples

*(Code examples, sentence examples, or usage scenarios.)*

## Visual Explanation

*(Link to a diagram, infographic, or image explaining the concept visually.)*

## Vocabulary

*(Key vocabulary introduced in this lesson, with definitions and examples.)*

## Common Mistakes

*(Common errors students make related to this topic and how to avoid them.)*

## BAC Tips

*(Specific tips and strategies for applying this knowledge in the Baccalaureate exam.)*

## Exercises

*(Practice questions or tasks related to the lesson.)*

## Solutions

*(Solutions to the exercises.)*

## Summary

*(Brief recap of the main points of the lesson.)*

## References

*(Sources used or recommended for further reading.)*

## Further Reading

*(Links to additional resources for deeper understanding.)*

## Related Lessons

*   [Previous Lesson Title](link-to-previous-lesson.md)
*   [Next Lesson Title](link-to-next-lesson.md)
```

## Future Expansion Roadmap

*   **Interactive Platform:** Develop a dedicated web platform (using Docusaurus or similar) for a more interactive learning experience, including quizzes, progress tracking, and multimedia content.
*   **Multilingual Support:** Expand translations to Arabic and French to cater to a broader audience.
*   **Community Features:** Implement forums, discussion boards, and collaborative tools for learners and educators.
*   **Mobile Application:** Develop a mobile application for on-the-go learning.
*   **AI Integration:** Explore AI-powered features for personalized learning paths, automated feedback, and intelligent tutoring.
*   **Teacher Resources:** Create dedicated sections for teachers, including lesson plans, teaching guides, and assessment tools.
