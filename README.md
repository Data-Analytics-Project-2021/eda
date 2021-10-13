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

3. Fetch the data from the submodule to your local system (will take a very long time as it will clone 2GB of data from COVID-19 and ; decide on whether it is necessary or not)

    ```shell
    git submodule update
    ```

4. You may wish to recursively clone this repository in a single step by passing the `--recurse-submodules` option to `git clone`

    ```shell
    git clone --recurse-submodules https://<token>@github.com/Data-Analytics-Project-2021/eda
    ```

## Data sourcing and cleaning

- Data sourcing and level 1 cleaning is performed in `aggregate_cases_vaccines.ipynb`
- After sourcing and cleaning, the four files obtained are
  1. `india_cases_<last_source_date_dd-mm-yyyy>.csv` - state-wise daily COVID-19 cases in India
  2. `india_vaccines_<last_source_date_dd-mm-yyyy>.csv` - state-wise daily COVID-19 vaccinations in India
  3. `usa_cases_<last_source_date_dd-mm-yyyy>.csv` - state-wise daily COVID-19 cases in USA
  4. `usa_vaccines_<last_source_date_dd-mm-yyyy>.csv` - state-wise daily COVID-19 vaccinations in USA
