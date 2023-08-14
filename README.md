# Mosaic
<img width="1394" alt="CompareFile-min" src="https://user-images.githubusercontent.com/92834188/198717141-8e8da76f-81c2-4e7e-936a-73de71dcc262.png">


<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>Mosaic
</h1>
<h3>◦ Unleash creativity, build wonders. #Mosaic</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Python-3776AB.svg?style&logo=Python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [📂 Project Structure](#project-structure)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project provides a set of functions for image processing tasks within the file DISCOVERY.py. These functions offer capabilities to load, resize, and convert images to arrays, as well as caching abilities for efficient image loading. Additionally, it can check if a file is an image file, list image files in a directory, run test cases, and find the average color of an image. The purpose of the project is to enhance image processing capabilities, making it easier to perform common tasks and analyses efficiently.

---

## ⚙️ Features

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Architecture**     | The system follows a modular architecture, with separate functions defined for different image processing tasks. Data caching and organization are used to improve performance and reduce redundant computations. The codebase follows a procedural style of programming.    |
| **📖 Documentation**   | The codebase lacks comprehensive documentation, making it difficult for new contributors to understand the system's functionality and usage. A detailed README file or code comments explaining the purpose and usage of each function would be beneficial.    |
| **🔗 Dependencies**    | The codebase relies on standard Python libraries for image processing and manipulation, such as PIL and numpy. No external dependencies or external systems are mentioned in the provided code snippets.    |
| **🧩 Modularity**      | The codebase is reasonably modular, with different functions defined for specific image-processing tasks. However, a more organized structure employing object-oriented programming principles could improve code clarity and maintainability.   |
| **✔️ Testing**          | There is no explicit mention of testing strategies or tools in the codebase. The inclusion of unit tests, integration tests, or at least a framework (like pytest) for automated testing would be beneficial for ensuring code quality and reliability.    |
| **⚡️ Performance**      | The provided codebase is designed to cache loaded images, preventing repeated disk I/O operations and enhancing performance. However, without performance benchmarks or information on the expected workload, it's difficult to ascertain the overall performance.   |
| **🔐 Security**        | The codebase doesn't explicitly handle security-related aspects. Depending on the system's deployment and use cases, precautions should be taken to ensure input sanitization, secure storage, and secure communication of sensitive data like image files.    |
| **🔀 Version Control** | Git is used for version control of the codebase, aiding collaboration and enabling code review processes. The provided code snippets showcase basic usage of Git by sharing the repository URL. Employing branches, commit messages, and pull requests would enhance version control practices further.   |
| **🔌 Integrations**    | The codebase doesn't have explicit integrations with external systems or services. Depending on the requirements, potential integrations might include connecting with cloud storage services (like AWS S3) or interacting with external image processing APIs.   |
| **📶 Scalability**     | The codebase's scalability depends on the specific use cases and workload requirements. System design modifications, such as leveraging cloud technologies for image storage and processing, implementing parallel processing, or adopting distributed architecture, would be necessary for scaling the system effectively.   |

---


## 📂 Project Structure




---

## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                          | Summary                                                                                                                                                                                                                                                                                                                             |
| ---                                                                           | ---                                                                                                                                                                                                                                                                                                                                 |
| [DISCOVERY.py](https://github.com/vpareek2/Mosaic.git/blob/main/DISCOVERY.py) | The provided code snippet defines various functions related to image processing. It includes functions to load and resize images, convert images to arrays, cache loaded images, check if a file is an image file, list image files in a directory, run test cases for different scenarios, and find the average color of an image. |
| [mosaic.ipynb](https://github.com/vpareek2/Mosaic.git/blob/main/mosaic.ipynb) | HTTPStatus Exception: 400                                                                                                                                                                                                                                                                                                           |

</details>

---

## 🚀 Getting Started

### 📦 Installation

1. Clone the Mosaic repository:
```sh
git clone https://github.com/vpareek2/Mosaic.git
```

2. Change to the project directory:
```sh
cd Mosaic
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🎮 Using Mosaic

```sh
python main.py
```

### 🧪 Running Tests
```sh
pytest
```

---


## 🗺 Roadmap

> - [ ] `ℹ️  Task 1: Transform into python script`
> - [ ] `ℹ️  Task 2: Create User Interface`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---
