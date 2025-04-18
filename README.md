# Resume_builder
Resume Builder

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Dependencies](#Dependencies)
7. [Documentation](#documentation)
8. [Troubleshooting](#troubleshooting)
9. [Conclusion](#conclusion)
10. [How to Contribute](#how-to-contribute)
   - [Web Designers](#web-designers)
   - [Prompt Engineers](#prompt-engineers)
   - [Software Engineers](#software-engineers)
   - [Other Contributions](#other-contributions)
11. [Credits](#credits)
12. [License](#license)
13. [Disclaimer](#disclaimer)


## Introduction

Resume_Builder_AIHawk is powerful Python tool that simplifies the creation of visually stunning resumes quickly and easily. With this tool, you can not only build a resume from scratch but also tailor it perfectly based on a specific job description. By inputting the URL of the job listing, Resume_Builder_AIHawk customizes your resume to match the exact requirements and skills needed, making it ideal for enhancing your chances of landing the job.


## Features

- **Interactive Command-Line Interface:** Navigate through options and prompts using a user-friendly CLI.
- **Dynamic Style Management:** Choose from a variety of pre-defined resume styles.
- **Job Description Integration:** Automatically tailor your resume based on a job URL.

## Installation

To get started with Resume_Builder_AIHawk, follow these steps:

1. **Download and Install Python:**

   Ensure you have the last Python version installed. If not, download and install it from Python's official website. For detailed instructions, refer to the tutorials:

   - [How to Install Python on Windows](https://www.geeksforgeeks.org/how-to-install-python-on-windows/)
   - [How to Install Python on Linux](https://www.geeksforgeeks.org/how-to-install-python-on-linux/)
   - [How to Download and Install Python on macOS](https://www.geeksforgeeks.org/how-to-download-and-install-python-latest-version-on-macos-mac-os-x/)

2. **Download and Install Google Chrome:**
   - Download and install the latest version of Google Chrome in its default location from the [official website](https://www.google.com/chrome).

3. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/resume_builder_AIHawk.git
    ```

4. **Navigate to the Project Directory:**

    ```bash
    cd resume_builder_AIHawk
    ```
5. **Install Dependencies:**

   Ensure you have `pip` installed, then run:

    ```bash
    pip install -r requirements.txt
    ```

## Configuration

### 1. Configuring `plain_text_resume.yaml`

The `plain_text_resume.yaml` file is crucial as it contains all your personal details and resume content. Follow these steps to configure it properly:

#### 1. Create the File

Create a file named `plain_text_resume.yaml` in the root directory of your project. This file will store all the necessary details to generate your resume.

#### 2. Define Personal Information

Fill in your personal information. This section includes your basic details and contact information:

```yaml
personal_information:
  name: [Name]
  surname: [Surname]
  date_of_birth: "[DD/MM/YYYY]"
  country: [Country]
  city: [City]
  address: [Address]
  phone_prefix: "[+Country Code]"
  phone: "[Phone Number]"
  email: [Email Address]
  github: [GitHub URL]
  linkedin: [LinkedIn URL]
```

- **name**: Your first name.
- **surname**: Your last name.
- **date_of_birth**: Your date of birth in the format `DD/MM/YYYY`.
- **country**: The country where you live.
- **city**: The city where you live.
- **address**: Your home address.
- **phone_prefix**: Your phone number prefix, e.g., `+1` for the USA.
- **phone**: Your phone number.
- **email**: Your email address.
- **github**: Your GitHub profile URL (optional).
- **linkedin**: Your LinkedIn profile URL (optional).

#### 3. Provide Education Details

List your educational qualifications. You can add multiple degrees:

```yaml
education_details:
  - degree: [Degree Type]
    university: [University Name]
    gpa: "[GPA]"
    graduation_year: "[Graduation Year]"
    field_of_study: [Field of Study]
    exam:
      [Course Name]: "[Grade]"
      [Course Name]: "[Grade]"
      [Course Name]: "[Grade]"
  - degree: [Degree Type]
    university: [University Name]
    gpa: "[GPA]"
    graduation_year: "[Graduation Year]"
    field_of_study: [Field of Study]
    exam:
      [Course Name]: "[Grade]"
      [Course Name]: "[Grade]"
      [Course Name]: "[Grade]"
```

- **degree**: Type of degree (e.g., BSc, MSc, PhD).
- **university**: Name of the university or institution.
- **gpa**: Your GPA (optional).
