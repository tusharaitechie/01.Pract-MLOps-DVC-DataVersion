# 📦 MLOps Practice - DVC Data Versioning

> Learn how to version datasets efficiently using **DVC (Data Version Control)** with Git as part of an MLOps workflow.

---

## 📖 About the Project

This repository demonstrates how to use **DVC (Data Version Control)** for tracking and versioning datasets in Machine Learning projects.

In traditional Git repositories, storing large datasets is not practical. DVC solves this problem by tracking dataset versions while keeping the actual data in remote storage.

This project is created for practicing the fundamentals of **MLOps** and understanding how Git and DVC work together.

---

## 🎯 Objectives

* Learn Data Version Control (DVC)
* Track datasets using DVC
* Understand `.dvc` files
* Manage dataset versions with Git
* Practice reproducible Machine Learning workflows

---

## 🛠️ Tech Stack

* Python
* Git
* GitHub
* DVC (Data Version Control)

---

## 📂 Project Structure

```text
.
├── data/
├── .dvc/
├── .gitignore
├── dvc.yaml (if available)
├── requirements.txt
├── README.md
└── other project files
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tusharaitechie/01.Pract-MLOps-DVC-DataVersion.git

cd 01.Pract-MLOps-DVC-DataVersion
```

---

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Initialize DVC

```bash
dvc init
```

---

### 5. Add Dataset

```bash
dvc add data/
```

---

### 6. Commit Changes

```bash
git add .
git commit -m "Track dataset using DVC"
```

---

## 📚 Useful DVC Commands

Initialize DVC

```bash
dvc init
```

Track data

```bash
dvc add data/
```

Check status

```bash
dvc status
```

Push data to remote

```bash
dvc push
```

Pull data

```bash
dvc pull
```

Fetch latest data

```bash
dvc fetch
```

Remove cache

```bash
dvc gc
```

---

## 🌟 Why DVC?

* Version datasets like source code
* Works seamlessly with Git
* Handles large datasets efficiently
* Supports reproducible ML pipelines
* Integrates with cloud storage (AWS S3, GDrive, Azure, GCS, etc.)

---

## 📈 Learning Outcomes

After completing this practice, you will understand:

* Why Git alone is not enough for ML datasets
* How DVC tracks dataset versions
* Difference between Git and DVC
* Best practices for dataset management
* Basics of reproducible MLOps workflows

---

## 📌 Future Improvements

* Add DVC Remote Storage
* Create DVC Pipeline
* Data Version Comparison
* Model Versioning
* Experiment Tracking
* CI/CD Integration

---

## 🤝 Contributing

Contributions are welcome.

If you find improvements or want to add more MLOps practices, feel free to fork this repository and create a pull request.

---

## ⭐ Support

If you found this repository useful, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Tushar AI Techie**

Learning and sharing practical MLOps concepts one project at a time.

Happy Learning! 🚀
