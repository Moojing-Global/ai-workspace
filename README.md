# AI Workspace Documentation

## Overview
This workspace contains comprehensive documentation for Innov8tif's products, processes, and technical specifications. It serves as the central knowledge repository for engineers working with Innov8tif's eKYC solutions and related technologies.

## Quick Start

### For New Engineers
1. Start with [Company Overview](./context/company-overview.md) to understand Innov8tif
2. Review [EMAS eKYC](./context/products/emas-ekyc.md) and [EMAS CIDA](./context/products/emas-cida.md) products
3. Explore the [eKYC Modules](./context/README.md#ekyc-modules-okay-prefix) to understand core capabilities
4. Check [SOPs](#standard-operating-procedures-sop) for process guidance

### For Specific Tasks
- **Converting HTML to Bricks**: See [HTML to Bricks Conversion SOP](./SOP/html-to-bricks-conversion.md)
- **Updating Documentation**: See [Documentation Maintenance SOP](./SOP/documentation-maintenance.md)
- **Understanding Past Work**: Browse [Tasks Directory](./Tasks/)

---

## Documentation Structure

### 📁 Wiki (`Wiki/`)
WordPress-ready HTML wiki pages for all EMAS eKYC features matching the official sitemap. Production-ready content with embedded images, optimized for Gutenberg editor.

**[Full Wiki Index →](./Wiki/README.md)**

- **13 feature pages** organized by category (matching sitemap)
- **90+ sourced images** from Unsplash/Pexels
- **Journalistic writing style** (William Zinsser principles: concise, clear, valuable)
- **HTML format** ready to copy-paste into WordPress
- **Verified accuracy**: Okay-branded features verified against `/context/` documentation

**Categories**:
- **Identity Verification** (5): Facial Matching, Remote Video Verification, ID Data Extraction, ID Verification, Liveness Detection
- **User Screening** (4): Digital Footprint Analysis, Credit/Bankruptcy Checks, AML/CFT Screening, Face Recognition Search
- **Additional Verification** (4): Income/Address Proofing, Device Binding & Intelligence, Digital Signatures, Deepfake Detection

---

### 📁 Context (`context/`)
Information about Innov8tif, its products, technologies, and market position.

**[Full Context Index →](./context/README.md)**

#### Company Information
- [Company Overview](./context/company-overview.md) - About Innov8tif, mission, and market position
- [Branding Strategy 2025](./context/branding-strategy.md) - Product-first branding, EMAS eKYC focus
- [Website Revamp 2025](./context/website-revamp-2025.md) - Website project overview and content strategy

#### Core Products
- [EMAS eKYC](./context/products/emas-ekyc.md) - Electronic Know Your Customer verification platform
- [EMAS CIDA](./context/products/emas-cida.md) - Customer ID Assurance framework

#### eKYC Modules (Okay Prefix)
The five core modules of EMAS eKYC:
- [OkayID](./context/modules/okayid.md) - Document data capture via OCR/NFC
- [OkayDoc](./context/modules/okaydoc.md) - Document authentication using AI
- [OkayLive](./context/modules/okaylive.md) - Passive liveness detection
- [OkayFace](./context/modules/okayface.md) - Facial matching verification
- [OkayDB](./context/modules/okaydb.md) - Database checks and API integration

#### Additional Features & Services
- [Video Call Verification](./context/features/video-call-verification.md)
- [Digital Footprint Analysis](./context/features/digital-footprint-analysis.md)
- [Device Fingerprinting](./context/features/device-fingerprinting.md)
- [Financial Risk Checks](./context/features/financial-risk-checks.md)
- [Income & Address Proofing](./context/features/income-address-proofing.md)
- [Biometric Alert List](./context/features/biometric-alert-list.md)
- [Device Risk Screening](./context/features/device-risk-screening.md)
- [Device Binding](./context/features/device-binding.md)
- [Biometric Authentication](./context/features/biometric-authentication.md)

#### Technology Deep Dives
- [Facial Recognition Technology](./context/technologies/facial-recognition.md)
- [Liveness Detection](./context/technologies/liveness-detection.md)
- [Document Authentication](./context/technologies/document-authentication.md)
- [Device Fingerprinting Technology](./context/technologies/device-fingerprinting-tech.md)
- [Traditional KYC Shortcomings](./context/technologies/traditional-kyc-shortcomings.md)
- [ID Capture Best Practices](./context/technologies/id-capture-best-practices.md)

---

### 📁 Standard Operating Procedures (`SOP/`)
Step-by-step procedures for common tasks and processes.

#### Available SOPs
1. **[HTML to Bricks Conversion](./SOP/html-to-bricks-conversion.md)**
   - Converting Tailwind CSS HTML to Bricks Builder JSON format
   - Element mapping, ID generation, settings configuration
   - Quality checklist and troubleshooting

2. **[Documentation Maintenance](./SOP/documentation-maintenance.md)**
   - How to update and maintain documentation
   - Documentation standards and conventions
   - Quality guidelines and review checklists
   - Version control best practices

3. **[Feature Page Template](./SOP/feature-page-template.md)**
   - Standardized structure for feature and module wiki pages
   - Business-focused, educational content guidelines
   - Writing guidelines and quality checklist
   - Includes blank template for quick starts

#### When to Use SOPs
- You need to perform a specific task with a defined process
- You want to ensure consistency across implementations
- You're new to a process and need step-by-step guidance
- You want to understand best practices for a task

---

### 📁 Tasks (`Tasks/`)
Historical records of implementations, bug fixes, and significant work.

**[Tasks Index →](./Tasks/README.md)**

#### Recent Tasks
- **[2025-11-04: Initial Documentation Setup](./Tasks/2025-11-04-initial-documentation-setup.md)**
  - Created comprehensive documentation structure
  - Set up Context, SOP, and Tasks directories
  - Generated initial SOPs and master README

#### Task Categories
- **Feature Implementation**: New functionality added to systems
- **Bug Fixes**: Resolution of defects or issues
- **Refactoring**: Code improvements and maintenance
- **Integration**: Connections with external systems
- **Optimization**: Performance and efficiency improvements

---

### 📄 Technical Specifications
Detailed technical documentation for specialized tools.

#### [Converter Instructions](./converter_instructions.md)
Complete technical specification for converting Tailwind HTML to Bricks Builder JSON format.
- JSON structure definitions
- Element type mapping
- Settings object rules
- Parent-child relationships
- Special cases and examples

**Note**: For practical usage, refer to the [HTML to Bricks Conversion SOP](./SOP/html-to-bricks-conversion.md)

---

## Documentation Organization

### Structure Overview
```
ai-workspace/
├── README.md                    # This file - master index
├── converter_instructions.md    # Technical specification
│
├── Wiki/                       # WordPress-ready wiki pages
│   ├── README.md              # Wiki index and usage guide
│   ├── core-modules/          # 5 core EMAS eKYC modules (HTML)
│   └── additional-features/   # 9 additional features (HTML)
│
├── context/                     # Company & product information
│   ├── README.md               # Context documentation index
│   ├── company-overview.md     # About Innov8tif
│   ├── products/               # Main products
│   ├── modules/                # eKYC modules
│   ├── features/               # Additional features
│   └── technologies/           # Technical deep dives
│
├── SOP/                        # Standard Operating Procedures
│   ├── html-to-bricks-conversion.md
│   ├── documentation-maintenance.md
│   └── feature-page-template.md
│
└── Tasks/                      # Implementation history
    ├── README.md              # Task documentation overview
    └── YYYY-MM-DD-task-name.md
```

### Content Types

#### Wiki Pages
**Purpose**: Production-ready content for website
- WordPress Gutenberg-compatible HTML
- Business-focused feature descriptions
- Embedded images from Unsplash/Pexels
- Ready to publish on public website

#### Context Documents
**Purpose**: Provide information about what exists
- Company background and positioning
- Product capabilities and specifications
- Technical explanations
- Use cases and benefits

#### SOP Documents
**Purpose**: Explain how to perform tasks
- Step-by-step procedures
- Best practices and guidelines
- Quality checklists
- Troubleshooting guides

#### Task Documents
**Purpose**: Record what was done and why
- Implementation details
- Challenges and solutions
- Lessons learned
- Historical context

---

## How to Use This Documentation

### Finding Information

#### I need website content for EMAS eKYC features
→ Check [Wiki directory](./Wiki/)
→ Find the relevant feature HTML page
→ Copy-paste into WordPress Gutenberg

#### I want to understand Innov8tif's products
→ Start with [context/README.md](./context/README.md)
→ Read [Company Overview](./context/company-overview.md)
→ Explore specific products and modules

#### I need to perform a specific task
→ Check [SOP directory](#standard-operating-procedures-sop)
→ Follow the step-by-step procedure
→ Use quality checklists to verify work

#### I want to know what has been done before
→ Browse [Tasks directory](./Tasks/)
→ Search for relevant task documents
→ Review implementation history

#### I need technical specifications
→ See [converter_instructions.md](./converter_instructions.md)
→ Check relevant context technology docs
→ Review related SOP for practical application

### Navigating the Documentation

- **Use relative links**: All documentation is cross-referenced
- **Check "Related Documentation" sections**: Found at the bottom of each document
- **Start with README files**: Each directory has a README for navigation
- **Search by keyword**: Use your editor's search across files

---

## Documentation Standards

### File Naming
- Use lowercase with hyphens: `file-name.md`
- Be descriptive but concise
- Use consistent terminology
- Date prefix for tasks: `YYYY-MM-DD-task-name.md`

### Document Structure
Every document should include:
1. **Title** (# heading)
2. **Overview/Introduction**
3. **Main content** with clear headings
4. **Related Documentation** section
5. **Back navigation** where applicable

### Quality Standards
- Write in clear, professional English
- Use active voice
- Include practical examples
- Define technical terms
- Link to related documentation
- Keep formatting consistent

**See [Documentation Maintenance SOP](./SOP/documentation-maintenance.md) for complete guidelines**

---

## Contributing to Documentation

### When to Update Documentation

Update **Context** when:
- Company information changes
- Products or features are added/modified
- Technical specifications change
- Market positioning evolves

Update **SOPs** when:
- Processes improve or change
- Common mistakes are identified
- New tools are adopted
- Quality issues arise

Create **Task documents** when:
- Implementing significant features
- Fixing complex bugs
- Making architectural changes
- Completing integration work

### How to Update

1. **Read first**: Check [Documentation Maintenance SOP](./SOP/documentation-maintenance.md)
2. **Review related docs**: Ensure consistency
3. **Make updates**: Follow documentation standards
4. **Update cross-references**: Fix affected links
5. **Update this README**: Add new documents to index
6. **Commit with clear message**: Describe what was changed

---

## Maintenance

### Documentation Health
- All documents follow consistent structure ✅
- Cross-references are complete ✅
- No duplicate or overlapping content ✅
- Clear navigation paths ✅
- Master index is up to date ✅

### Last Updated
**2025-11-04**: Initial comprehensive documentation structure created

### Review Schedule
- **Monthly**: Review README.md for accuracy
- **Quarterly**: Review all context docs for outdated information
- **After major changes**: Update all affected documentation
- **New hire onboarding**: Test completeness, update gaps

---

## Quick Reference

### Key Documents
| Document | Purpose | When to Use |
|----------|---------|-------------|
| [context/company-overview.md](./context/company-overview.md) | Learn about Innov8tif | Onboarding, presentations |
| [context/products/emas-ekyc.md](./context/products/emas-ekyc.md) | Understand core product | Product discussions, integrations |
| [SOP/html-to-bricks-conversion.md](./SOP/html-to-bricks-conversion.md) | Convert HTML to Bricks | Frontend development |
| [SOP/documentation-maintenance.md](./SOP/documentation-maintenance.md) | Update documentation | Documentation work |
| [SOP/feature-page-template.md](./SOP/feature-page-template.md) | Create feature wiki pages | Content creation, wiki documentation |
| [converter_instructions.md](./converter_instructions.md) | Technical specification | Technical reference |

### Common Questions

**Where do I find information about OkayFace?**
→ [context/modules/okayface.md](./context/modules/okayface.md)

**How do I convert Tailwind HTML to Bricks JSON?**
→ [SOP/html-to-bricks-conversion.md](./SOP/html-to-bricks-conversion.md)

**What tasks have been completed recently?**
→ [Tasks/README.md](./Tasks/README.md)

**How do I update documentation?**
→ [SOP/documentation-maintenance.md](./SOP/documentation-maintenance.md)

**What makes Innov8tif's solution unique?**
→ [context/company-overview.md](./context/company-overview.md)

---

## Support

For questions or issues with documentation:
1. Check relevant SOP for guidance
2. Review related task documents for context
3. Consult [Documentation Maintenance SOP](./SOP/documentation-maintenance.md)
4. Update documentation as needed

---

**Documentation Version**: 2.1
**Last Major Update**: 2025-11-04
**Total Documents**: 50+ across Wiki, Context, SOP, and Tasks directories
**Wiki Pages**: 13 production-ready HTML pages (reorganized by sitemap) with 90+ images
