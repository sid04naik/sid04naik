# 📋 Codebase Index - Siddhant Naik Resume

## 🎯 Project Overview
This is a LaTeX-based resume project using the AltaCV template. The project creates a professional resume for Siddhant Naik, a Backend Engineering Specialist with expertise in Go, Node.js, Cloud, Docker, NoSQL, caching & queues.

## 📁 File Structure

### Core Resume Files
- **`siddhant.tex`** (9.8KB, 296 lines)
  - **Purpose**: Main LaTeX source file containing Siddhant's resume content
  - **Content**: Personal information, work experience, skills, education, and achievements
  - **Key Features**:
    - Uses AltaCV document class with custom styling
    - Includes profile photo (OFFICE-PROFILE.JPG)
    - Custom color scheme (VividPurple, SlateGrey, LightGrey)
    - Two-column layout with paracol package
    - Hyperlinked contact information

### Template & Styling
- **`altacv.cls`** (17KB, 501 lines)
  - **Purpose**: LaTeX document class for creating professional resumes/CVs
  - **Version**: v1.7.3 (31 Oct 2024) by LianTze Lim
  - **Features**:
    - Modern, clean design with customizable colors
    - Support for photos (circular or normal)
    - FontAwesome5 icons integration
    - Hyperlink support for contact information
    - Flexible layout options
    - Multiple photo placement options

### Build Configuration
- **`latexmkrc`** (93B, 3 lines)
  - **Purpose**: Configuration file for latexmk build tool
  - **Content**: Optimization settings for xelatex compilation with pdfx
  - **Function**: Speeds up compilation by ignoring timestamp patterns in hash calculation

### Assets
- **`OFFICE-PROFILE.JPG`** (888KB)
  - **Purpose**: Professional headshot photo for the resume
  - **Usage**: Referenced in siddhant.tex as profile photo
  - **Format**: High-resolution JPEG image

### Documentation
- **`README.md`** (986B, 27 lines)
  - **Purpose**: Project overview and usage instructions
  - **Content**:
    - Brief description of the resume
    - About Siddhant (Backend Engineering Specialist)
    - License information (Creative Commons)
    - File listing

- **`LICENCE.md`** (828B, 15 lines)
  - **Purpose**: License terms for the project
  - **License**: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
  - **Terms**: Allows sharing and adaptation with attribution, non-commercial use, and share-alike requirements

### Reference Materials
- **`reference/`** directory
  - **`readme.md`** (9.8KB, 196 lines)
    - **Purpose**: Original AltaCV template documentation
    - **Content**:
      - Template usage instructions
      - Compilation requirements
      - Sample templates and examples
      - Advanced customization options
      - Font and styling guidelines

### Version Control
- **`.git/`** directory
  - **Purpose**: Git version control repository
  - **Status**: Active repository with commit history

- **`.gitignore`** (50B, 6 lines)
  - **Purpose**: Git ignore patterns
  - **Content**: Standard LaTeX build artifacts to exclude from version control

## 🔧 Technical Stack

### Primary Technologies
- **LaTeX**: Document preparation system
- **AltaCV**: Professional resume template class
- **XeLaTeX**: LaTeX compiler with Unicode support
- **FontAwesome5**: Icon library for contact information
- **Lato Font**: Modern typeface for clean appearance

### Build Tools
- **latexmk**: Automated LaTeX compilation tool
- **pdfx**: PDF/A compliance package
- **paracol**: Multi-column layout package

## 🎨 Design Elements

### Color Scheme
- **VividPurple** (#3E0097): Primary accent color for headings and rules
- **SlateGrey** (#2E2E2E): Emphasis text color
- **LightGrey** (#666666): Body text color

### Typography
- **Primary Font**: Lato (modern, clean sans-serif)
- **Icons**: FontAwesome5 for contact information and bullet points

### Layout
- **Structure**: Two-column layout using paracol package
- **Ratio**: 6:4 left-to-right column ratio
- **Photo**: Right-aligned circular profile photo
- **Margins**: 1.25cm left/right, 1.5cm top/bottom

## 📋 Content Sections

### Personal Information
- Name: Siddhant Naik
- Title: Lead Engineer & Aspiring Staff Engineer
- Contact: Email, phone, location, LinkedIn, GitHub
- Photo: Professional headshot

### Professional Profile
- Backend Engineering Specialist
- Expertise: Go, Node.js, Cloud, Docker, NoSQL, caching & queues
- Focus: Scalable systems, platform reliability, mentoring
- Availability: 15-day notice

### Resume Sections
1. **Profile**: Professional summary
2. **Experience**: Work history and achievements
3. **Skills**: Technical competencies
4. **Education**: Academic background
5. **Additional**: Projects, certifications, etc.

## 🚀 Build Process

### Compilation Command
```bash
xelatex -shell-escape -output-driver="xdvipdfmx -z 0" siddhant.tex
```

### Output
- **Primary**: `siddhant.pdf` (compiled resume)
- **Build Artifacts**: Various LaTeX auxiliary files (ignored by git)

## 📄 License & Usage

### Project License
- **Type**: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
- **Permissions**: Share, adapt, remix
- **Requirements**: Attribution, non-commercial use, share-alike
- **Attribution**: Credit to Siddhant Naik

### Template License
- **AltaCV**: LaTeX Project Public License
- **Fonts**: Lato font license
- **Icons**: FontAwesome license

## 🔄 Maintenance

### Regular Updates
- Resume content updates in `siddhant.tex`
- Profile photo updates (replace `OFFICE-PROFILE.JPG`)
- Template updates (check for AltaCV updates)

### Build Verification
- Ensure all LaTeX packages are installed
- Verify font availability (Lato)
- Test compilation with xelatex

## 📝 Notes

- The resume is designed for professional use in backend engineering roles
- Focus on technical leadership and scalable systems expertise
- Clean, modern design suitable for tech industry applications
- Mobile-friendly PDF output with proper hyperlinks
- Optimized for ATS (Applicant Tracking System) compatibility

---

*Last Updated: [Current Date]*
*Index Version: 1.0*