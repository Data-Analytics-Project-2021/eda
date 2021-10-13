# eda

## Clone this repo

1. Clone the repo (make sure you have created GitHub personal access tokens as password authentication is no longer supported).

    ```shell
    git clone https://<token>@github.com/Data-Analytics-Project-2021/eda
    ```

2. Initialise submodules

    ```shell
    git submodule init
    ```

3. Fetch the data from the submodule to your local system (will take a very long time as it will clone 2GB of data; decide on whether it is necessary or not)

    ```shell
    git submodule update
    ```

4. You may wish to recursively clone this repository in a single step by passing the `--recurse-submodules` option to `git clone`

    ```shell
    git clone --recurse-submodules https://<token>@github.com/Data-Analytics-Project-2021/eda
    ```
