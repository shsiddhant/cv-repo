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
│       │   └── womens_wc.tex
│       ├── projects.tex
│       ├── skills.tex
│       └── summary.tex
├── README.md
├── tailored/
│   └── company_role_date/
└── templates/
    └── simple_cv_template.tex
```

##  Typical Workflow

1. Start from the main CV:

   ```
   base/main_cv.tex
   ```

2. Create a new tailored version:

   ```
   cp -r base/ tailored/company_role_date/
   ```

3. Edit CV:

   * Remove irrelevant content
   * Reorder sections
   * Adjust bullet points to match the job description

4. Compile the PDF.


##  Version Control

- Use branches for major variations:

  ```
  git checkout -b company-name
  ```

- Tag submitted versions:

  ```
  git tag company-role-v1
  ```
