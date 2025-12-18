# Osman Hadi Memorial & Legacy Archive

A digital repository dedicated to preserving and sharing the works, ideas, and legacy of Sharif Osman Hadi for present and future generations.

**Website:** [osman-hadi.org](https://osman-hadi.org)

---

## Mission

This project exists to **preserve, celebrate, and share the intellectual, creative, and spiritual legacy** of Sharif Osman Hadi. Through curated collections of his writings, poetry, speeches, and ideas, we create an enduring digital archive that allows people around the world to discover, understand, and build upon his contributions.

We believe that legacies grow stronger when they are:
- **Accessible** — available to anyone, anywhere, at any time
- **Living** — evolving through community contributions and engagement
- **Documented** — carefully preserved for future generations
- **Shared** — fostering dialogue and deeper understanding

---

## What This Project Contains

This repository holds the source code and content infrastructure for a static website built with **Hugo**, designed to be simple, fast, and maintainable. The site showcases:

- **Writings & Essays** — Philosophical pieces, analysis, and reflective works
- **Poetry & Creative Works** — Poems, creative expressions, and artistic contributions
- **Speeches & Lectures** — Recorded talks, transcripts, and spoken word
- **Biographical Context** — Background information to understand his life and times
- **Resource Links** — References, related works, and external materials
- **Community Contributions** — Guest posts, analyses, and reflections from admirers and students

---

## How to Contribute

We welcome contributions from anyone who wishes to help preserve and expand Osman Hadi's legacy. This is a community-driven project.

### Types of Contributions

1. **Content Submissions**
   - Written works (essays, letters, unpublished writings)
   - Poetry or creative pieces
   - Transcripts of speeches or interviews
   - Photos, audio, or video files
   - Biographical information or anecdotes

2. **Analysis & Interpretation**
   - Literary analyses of his works
   - Contextual essays explaining his ideas
   - Research papers or academic studies
   - Personal reflections on his impact

3. **Technical Contributions**
   - Website improvements and bug fixes
   - Better content organization
   - Enhanced search or navigation features
   - Accessibility improvements

4. **Curation & Organization**
   - Tagging and categorizing content
   - Creating thematic collections
   - Writing descriptions and metadata
   - Fact-checking and verification

### How to Contribute

1. **Fork the repository** on GitHub
2. **Create a new branch** for your contribution
3. **Add your content** following the guidelines below
4. **Submit a pull request** with a clear description of your additions
5. **Engage in discussion** with maintainers for review and feedback

### Content Guidelines

- **Accuracy First** — Verify all information and cite sources
- **Respectful Tone** — Maintain dignity and respect for the subject and audience
- **Clear Attribution** — Always credit original sources and authors
- **Proper Formatting** — Use consistent Markdown formatting
- **File Organization** — Place content in appropriate directories (writings/, poetry/, speeches/, etc.)
- **Metadata** — Include date, author, and contextual information where available

### Large or Complex Contributions

For substantial additions (full books, extensive archives, video collections), please open an issue first to discuss:
- Storage and format requirements
- Metadata and tagging approach
- Integration with existing content
- Timeline and next steps

---

## Technical Setup

### Requirements
- **Hugo** (v0.88 or later)
- **Git** (for version control)
- Basic familiarity with Markdown

### Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/osman-hadi.git
cd osman-hadi

# Serve the site locally
hugo server

# Visit http://localhost:1313 to preview
```

### Building for Deployment

```bash
# Generate the static site
hugo

# The `public/` directory contains your deployable site
```

### Content Structure

```
content/
├── about.md
├── writings/
│   ├── essays/
│   └── reflections/
├── poetry/
│   ├── collections/
│   └── individual-works/
├── speeches/
│   ├── transcripts/
│   └── audio-notes/
├── resources/
│   └── external-links.md
└── contributors/
    └── index.md
```

---

## Content Guidelines for Contributors

### Front Matter (Metadata)

Every content file should include YAML front matter at the top:

```yaml
---
title: "Title of Work"
author: "Sharif Osman Hadi"
date: 2024-01-15
category: "essays" # or poetry, speeches, etc.
tags: ["philosophy", "society", "spirituality"]
draft: false
summary: "A brief one-line summary of the content"
source: "Where this work originally appeared"
---
```

### Writing Standards

- Use clear, readable Markdown formatting
- Include section headers to organize long pieces
- Add footnotes for references and citations
- Provide context for unclear historical or cultural references
- Preserve original formatting and style while maintaining readability

### Media Files

- Place images in `static/images/` and reference them in content
- Audio/video files should be hosted externally (YouTube, archive.org, etc.) and embedded
- Include alt text for all images for accessibility
- Optimize file sizes before uploading

---

## Maintenance & Sustainability

### Regular Tasks

- **Content Review** — Monthly verification of links and accuracy
- **Community Moderation** — Respectful, timely responses to contributions and questions
- **Backups** — Regular backups of all content to multiple locations
- **Updates** — Documentation updates as the site evolves
- **Engagement** — Highlighting new contributions and community involvement

### Long-Term Preservation

- **Version Control** — All history preserved in Git
- **Multiple Backups** — Content backed up to multiple services
- **Open Formats** — Using Markdown and standard formats for longevity
- **Static Site** — No database dependencies; easy to migrate or archive
- **Community Stewardship** — Encouraging multiple maintainers to ensure continuity

---

## Code of Conduct

All contributors agree to:

1. **Respect the Legacy** — Treat Osman Hadi's work and memory with reverence and accuracy
2. **Be Respectful** — Engage thoughtfully with other contributors
3. **Verify Information** — Only submit content you believe to be accurate
4. **Cite Sources** — Give credit where credit is due
5. **Stay On Topic** — Keep discussions focused on Osman Hadi's legacy and related scholarship
6. **No Misinformation** — Do not submit deliberately false or misleading content

Violations of this code may result in contributions being declined or removed.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International License** (CC-BY 4.0).

**What this means:**
- You can share, adapt, and distribute this content
- You must give appropriate credit to Sharif Osman Hadi and the contributors
- You cannot restrict others' use of the work
- You must include a copy of the license

---

## Contact & Support

- **Issue Tracker** — Report bugs, suggest features, or ask questions on GitHub Issues
- **Pull Requests** — Submit contributions via GitHub Pull Requests
- **Email** — [contact information, if applicable]
- **Community Forum** — [Link to discussion forum, if applicable]

---

## Acknowledgments

This project was created with deep respect for Sharif Osman Hadi's contributions and with gratitude to all who have known him, studied his work, and are committed to preserving his legacy for generations to come.

Special thanks to:
- All contributors who have shared content and resources
- Community members who have provided feedback and guidance
- The broader community dedicated to preserving intellectual heritage

---

## FAQ

**Q: How do I know if content is authentic?**
A: We prioritize verification through original sources, documentation, and community expertise. All significant content includes source attribution and context.

**Q: Can I use this content for my own project?**
A: Yes, under the CC-BY 4.0 license. Please provide attribution to Osman Hadi and this project.

**Q: What if I find an error or inaccuracy?**
A: Please open an issue on GitHub or contact us directly. We appreciate corrections and improvements.

**Q: How can I support this project?**
A: You can contribute content, help with organization, provide technical improvements, or help spread awareness of the project.

**Q: Is this an official project?**
A: This is a community-driven memorial project. It is not affiliated with any particular organization, but welcomes input from anyone committed to preserving Osman Hadi's legacy.

---

**Last Updated:** December 2024  
**Current Version:** 1.0  
**Repository:** [GitHub Link]

---

*"A legacy lives not in monuments, but in minds and hearts. Through preserving his words, we ensure his ideas continue to inspire, challenge, and illuminate."*
