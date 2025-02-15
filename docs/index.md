# Getting Started
Energy-dagster is the data orchestration and pipelining tool for the german energy system built with [Dagster](https://dagster.io/) and [dbt](https://docs.getdbt.com/). Its purpose is to collect and combine data from different sources which is relevant for the german energy system. This is done regularly to keep the database up to date.



## How to use it
1. Clone the repository [git.fortiss.org/ASCI-public/energy-dagster](https://git.fortiss.org/ASCI-public/energy-dagster) and open it in a terminal.
1. Make sure you have [docker](https://www.docker.com/) and [docker-compose](https://docs.docker.com/compose/install/standalone/) installed by running 
```bash
docker --version
docker-compose --version
```
1. Run `docker-compose up` and go to [localhost:3000](localhost:3000) to see the dagster UI. A documentation of the dagster UI can be found [here](https://docs.dagster.io/concepts/dagit/dagit).
1. Start exploring the data pipelines :tada:

For an alternative setup where dagster is running in a terminal, you can also follow the instructions in the [Setup for development](developing/setup_development.md).


