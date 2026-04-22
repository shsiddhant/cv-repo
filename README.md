# CV Repository

This repository contains my CVs, maintained using LaTeX and version-controlled with Git. It is designed to make it easy to tailor resumes for different roles while keeping a clean, reusable base.


##  Repository Structure

```
cv-repo
├── base/
│   ├── main_cv.tex
│   └── sections/
│       ├── education.tex
│       ├── experience.tex
│       ├── projects/
│       │   ├── cricket_warehouse.tex
│       │   ├── memoryfm.tex
│       │   ├── memoryjournal.tex
│       │   ├── memorytext.tex
│       │   └── womens_wc.tex
│       ├── skills/
│       └── summary/
├── README.md
├── tailored/
│   ├── roles/
│   └── company_role_date/
└── templates/
    └── simple_cv_template.tex
```

##  Typical Workflow

1. Create a tailored version:

   ```
   cp -r templates/main_cv.tex tailored/company_role_date/
   ```

3. Edit CV: Choose skills, summary, and projects to include based on job / role description.

4. Compile the PDF.


##  Version Control

Tag submitted versions:

  ```
  git tag company-role-v1
  ```
