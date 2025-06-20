

# Plagiarism Checker

A modern, web-based plagiarism checker built with Django, featuring a creative and user-friendly frontend. This tool allows users to check for plagiarism in text or uploaded documents using advanced algorithms, including cosine similarity.

---

## Features

- **Text & File Upload:** Check plagiarism by pasting text or uploading documents.
- **Web Search Integration:** Compares input against web sources for accurate detection.
- **Cosine Similarity Algorithm:** Robust backend for similarity measurement.
- **Modern UI:** Clean, responsive, and creative interface with a custom color palette.
- **Results Visualization:** Clear percentage and source links for detected plagiarism.
- **Author:** Owned and maintained by **BHARANI.K**

---

## Result Screenshot

![Result Screenshot](plagiarismchecker/assets/result.png)

---

## Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)
- (Recommended) [Anaconda](https://www.anaconda.com/products/individual) for environment management

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/plagiarism-checker.git
   cd plagiarism-checker
   ```

2. **Install dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

3. **Apply migrations:**

   ```sh
   python manage.py migrate
   ```

4. **Run the development server:**

   ```sh
   python manage.py runserver
   ```

5. **Open your browser and visit:**
   ```
   http://127.0.0.1:8000/
   ```

---

## Usage

- **Home:** Paste your text or upload a document to check for plagiarism.
- **Compare Documents:** Compare two documents for similarity.
- **Results:** View plagiarism percentage and matched sources.

---

## Project Structure

```
plagiarism-checker/
├── plagiarismchecker/        # Django app
│   ├── templates/pc/         # HTML templates
│   ├── static/pc/            # CSS, JS, images
│   └── assets/               # Screenshots and other assets
├── manage.py
├── requirements.txt
└── README.md
```

---

## Technologies Used

- **Backend:** Django, Python
- **Frontend:** Bootstrap, Material Design, Custom CSS
- **Algorithms:** Cosine Similarity, Web Search APIs

---

## Author

**BHARANI.K**  
_Designed and developed with creativity and passion._

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Django Documentation
- Bootstrap & MDBootstrap
- Google API Client Libraries

---

## _Author Name_

<!--Remove the below lines and add yours -->

[Bharani](https://github.com/Bharani1611)

---

> For any queries or contributions, please contact the author or open an issue on GitHub.
