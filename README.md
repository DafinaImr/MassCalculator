# MassCalculator
The main repository that clones all repositories as submodules

## Clone the Project

To clone and update your project on your machine:

* Clone the project:
    ```bash
    git clone https://github.com/MassCalculator/MassCalculator
    ```

* Go into the project folder:
    ```bash
    cd MassCalculator
    ```

* Initialize all submodules:
    ```bash
    git submodule update --init --recursive --remote
    ```

* Update all files and checkout to a specific branch (e.g., master):
    ```bash
    git submodule foreach git pull origin master
    git submodule foreach git checkout master
    ```