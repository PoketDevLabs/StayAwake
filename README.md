# <br />
<div align="center">
  <a href="https://github.com/PoketDevLabs/StayAwake">
    <img src="logo.png" alt="StayAwake" width="500" height="100">
  </a>
  <p align="center">
    A minimalist app that prevents your computer from going to sleep.
    <br/>
  </p>
  <p align="center">
  <a href="https://github.com/PoketDevLabs/StayAwake">
    <img src="app.gif" alt="StayAwake" width="" height="">
  </a>
  </p>
  <p align="center">
  <a href="https://github.com/PoketDevLabs/StayAwake">
    <img src="notification.png" alt="StayAwake" width="" height="">
  </a>
  </p>
  <p align="center">
  <a href="https://github.com/PoketDevLabs/StayAwake">
    <img src="tray.png" alt="StayAwake" width="" height="">
  </a>
  </p>
</div>

<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#clone-the-repository">Clone the Repository</a></li>
    <li><a href="#run-the-code">Run the Code</a></li>
    <li><a href="#additional-tools">Additional Tools</a></li>
    <li><a href="#thank-you-for-choosing-poket-dev">Thank you for choosing Poket Dev!</a></li>
  </ol>
</details>



# Contact
For any project-related questions, bug fixes, feature requests, or communication needs regarding StayAwake, please utilize the comment section within your StayAwake request card on your Trello board. This centralizes all discussions, ensuring efficient and effective communication throughout the project's development.  

# Prerequisites
- [Python](https://www.python.org/downloads/) (latest version)  
  - If using windows, in the python installer make sure to select the "Add Python to PATH" option  
- [Pycharm](https://www.jetbrains.com/pycharm/download/#section=windows) (optional)


# Clone the Repository
## Option 1: via Command Line Interface
- Install [GitHub CLI](https://cli.github.com/) (if not already installed)
  ```
  git clone https://github.com/PoketDevLabs/StayAwake
  ```
## Option 2: via GitHub Desktop
1. Install [GitHub Desktop](https://desktop.github.com/) (if not already installed)  
2. Follow instructions [here](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop) to clone
# Run the Code
###**While Docker is typically our recommended method for running Python applications, it is important to note that Stay Awake is specifically designed as a Windows desktop application. Consequently, there is no advantage to running it within a Docker container. Additionally, it is worth mentioning that pyqt5 is incompatible with Linux Docker containers. For Stay Awake, we recommend using  Option 2: Poetry to run.**

## ~~Option 1: Docker (Recommended)~~
~~Docker is a free tool that simplifies the process of running applications by packaging them with everything they need, so you can easily move them between different machines and ensure they work quickly and consistently, saving you time and reducing potential conflicts. If you're not familiar with docker, we STRONGLY recommend taking a few minutes to become familiar [here](https://www.docker.com/blog/getting-started-with-docker-desktop/#:~:text=Docker%20Desktop%20is%20an%20easy,%2C%20Kubernetes%2C%20and%20Credential%20Helper.).~~
1. ~~Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) (if not already installed)~~
2. ~~Open Docker Desktop~~
3. ~~Build the Docker image:~~
```
cd StayAwake
docker build -t stayawake .
```

4. ~~Run the Docker container:~~
```
docker run stayawake
```
## Option 2: Poetry (Recommended for StayAwake)
1. Install Poetry (if not already installed)
```
pip install poetry
```
2. Install StayAwake dependencies
```
cd StayAwake
poetry install
```
3. Run StayAwake
```
poetry run python main.py
```
## Option 3: requirements.txt
1. Create the virtual environment:
```
cd StayAwake
python -m venv venv
```
2. Activate the virtual environment:
- For Windows:
```
venv\Scripts\activate
```
- For macOS/Linux:
```
source venv/bin/activate
```
Once activated, you will notice that the prompt in your terminal or command prompt changes to indicate that you are now working within the virtual environment.  
3. Install StayAwake dependencies
```
pip install -r requirements.txt
```
4. Run StayAwake
```
python main.py
```

# Additional Tools
All StayAwake code was formatted, linted, and secured with the following tools:
- [black](https://black.readthedocs.io/en/stable/)
- [flake8](https://flake8.pycqa.org/en/latest/)
- [radon](https://radon.readthedocs.io/en/latest/)
- [bandit](https://bandit.readthedocs.io/en/latest/)
- [isort](https://pycqa.github.io/isort/)
- [mypy](https://mypy.readthedocs.io/en/stable/)

# Thank you for choosing Poket Dev!
Thank you for choosing Poket Dev, LLC (www.PoketDev.com) as your unlimited software development partner. We greatly appreciate you and are committed to delivering exceptional solutions and exceeding your expectations.  

If you'd like to refer someone to Poket Dev, and they subscribe to any of our packages, you'll receive a $500 referral bonus.  