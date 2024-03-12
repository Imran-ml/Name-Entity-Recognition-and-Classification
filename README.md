<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">Description</a>
    </li>
    <li>
      <a href="#getting-started">Setting Up a Virtual Environment</a>
      <ul>
        <li><a href="#dependencies">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- Description -->
## Description

In this project, I trained a machine learning model to read doctor notes and understand key details like patient names and health-related terms. Using a process called Name Entity Recognition (NER) and Classification, it sorts the notes into two categories: "Others" for general information and "Syndrome" for specific health issues. This makes it simpler for the computer and ultimately for doctors, to quickly grasp the important bits in the notes, making healthcare decisions faster and more accurate. It's a smart assistant for doctors in understanding and organizing medical information!

For a more detailed exploration of our methodology and results, refer to my [Kaggle notebook](https://www.kaggle.com/code/muhammadimran112233/name-entity-recognition-and-classification).

To access the dataset used in this project, visit the [Kaggle dataset](https://www.kaggle.com/datasets/muhammadimran112233/clinical-documents-on-syndromes-disease).

<!-- GETTING STARTED -->
## Getting Started

In this section you should provide instructions on how to use this repository to recreate your project locally.

### Dependencies

Here, list all libraries, packages and other dependencies that need to be installed to run your project. Include library versions and how they should be installed if a special requirement is needed.

For example, this is how you would list them:
* Transformers 4.8.0
  ```sh
  conda install -c conda-forge transformers
  ```
* OpenCV 4.5.2
  ```sh
  conda install -c conda-forge opencv
  ```
### Alternative: Export your Environment

Alternatively, you can export your Python working environment, push it to your project's repository and allow users to clone it locally. This way, anyone can install it and they will have all dependencies needed. Here is how you export a copy of your Python environment:

  ```sh
  conda env export > requirements.yml
  ```

The user will be able to recreate it using:

  ```sh
  conda env create -f requirements.yml
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/catiaspsilva/README-template.git
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f requirements.yml
  ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. For course projects, include which file to execute and the format of any input variables.

Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/catiaspsilva/README-template/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)

## Thank you

<!-- If this is useful: [![Buy me a coffee](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg)](https://www.buymeacoffee.com/catiaspsilva) -->
