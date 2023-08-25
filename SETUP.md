# Setup

- [Overview](#overview)
- [Fetching code](#fetching-code)

## Overview

This file provides detailed setup instructions for developers and maintainers, such as fetching the source code, managing the dependencies, setting up environments, build generation, running tests etc.

> **Note**: Any dependencies added to this project (or modifying it) which affect the running of the code in this git repository must be listed in this file. All developers must ensure that the instructions mentioned in this file are sufficient to enable a new developer to obtain a executable copy of the lastest code in this repository, without involvement from any other human assistance.

## Fetching code

This section includes the commands required to fetch the source code from the git repository to the local system.

1. Add SSH key

    First, add your SSH public key to the project:

    - [x] [https://gitlab.com/fullstack-react-pm/fullstack-react](https://gitlab.com/fullstack-react-pm/fullstack-react)
    - [x] [https://github.com/study-pm/fullstack-react](https://github.com/study-pm/fullstack-react)

2. Clone repository

    For GitLab

    Clone the repository from [GitLab](https://gitlab.com/fullstack-react-pm/fullstack-react.git):

    ```sh
    $ git clone git@gitlab.com:fullstack-react-pm/fullstack-react.git
    ```

    Clone the repository from [GitHub](https://github.com/study-pm/fullstack-react.git) [mirror]:

    ```sh
    git clone git@github.com:study-pm/fullstack-react.git
    ```

    > **❗** Do not ever push manually to this mirror repository! This may lead to errors.

    > If you have multiple git accounts prepend the host name with your git account name (with a dot separator), like that: 
    > 
    > ```sh
    > $ git clone git@study-pm.gitlab.com:fullstack-react-pm/fullstack-react.git
    > ```

3. Change current working directory to Project directory

    ```sh
    $ cd fullstack-react
    ```
