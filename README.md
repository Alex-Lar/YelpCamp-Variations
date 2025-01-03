# YelpCamp Variations

This repository contains various variations of the original YelpCamp project, each implemented as a Git submodule. These variations showcase different technologies, frameworks, and approaches to building the YelpCamp application.

## Overview

YelpCamp is a full-stack web application that allows users to create and review campgrounds. This project includes multiple implementations, each demonstrating unique features and technologies used in web development.

## Project Structure

An example of a project structure:

```
.
├── README.md
├── variation1/ # Submodule for Variation 1
│ ├── README.md
│ └── ...
├── variation2/ # Submodule for Variation 2
│ ├── README.md
│ └── ...
└── variation3/ # Submodule for Variation 3
├── README.md
└── ...
```

### Submodules

Each variation is a separate Git repository linked as a submodule within this main repository. To work with these submodules:

1. **Cloning the Repository**: When cloning this repository, use the `--recurse-submodules` flag to ensure all submodules are cloned as well:

```
git clone --recurse-submodules <repository_url>
```

2. **Updating Submodules**: If you've already cloned the repository without the `--recurse-submodules` flag, you can initialize and update the submodules with:

```
git submodule init
git submodule update
```

3. **Working with Submodules**: Navigate into any variation's directory to work on that specific implementation:

```
cd variation1 # or variation2, variation3, etc.
```

4. **Committing Changes**: After making changes in a submodule, make sure to commit those changes in the submodule's repository before returning to the main repository and committing the updated reference.

## Variations Included

- **Vanilla YelpCamp**: Original version of the YelpCamp project. It is built using Node.js, Express, MongoDB, and Bootstrap.

## Getting Started

To get started with any of the variations:

1. Navigate to the desired variation directory.
2. Follow the specific setup instructions provided in each variation's README file.

## Acknowledgments

Special thanks to Colt Steele for providing an excellent curriculum that inspired these variations of the YelpCamp project.

Feel free to explore each variation and contribute to this project by submitting pull requests or opening issues!