# distributed-python

## Comparisons

- [Dask and Celery](https://matthewrocklin.com/blog/work/2016/09/13/dask-and-celery)
- [Ray comparison with Dask](https://github.com/ray-project/ray/issues/642)
- [Ray vs Dask](https://medium.com/@coolgeng/ray-vs-dask-d0154a774f2a)
- [Airflow + celery or dask. For what, when?](https://stackoverflow.com/questions/49310136/airflow-celery-or-dask-for-what-when)

## [Airflow](https://airflow.apache.org/)
<img src="https://upload.wikimedia.org/wikipedia/commons/d/de/AirflowLogo.png" height="100">

Use Airflow to author workflows as directed acyclic graphs (DAGs) of tasks. The Airflow scheduler executes your tasks on an array of workers while following the specified dependencies. Rich command line utilities make performing complex surgeries on DAGs a snap. The rich user interface makes it easy to visualize pipelines running in production, monitor progress, and troubleshoot issues when needed.

## [Celery](https://docs.celeryproject.org)

<img src="https://docs.celeryproject.org/en/stable/_static/celery_512.png" height="100">

Celery is a simple, flexible, and reliable distributed system to process vast amounts of messages, while providing operations with the tools required to maintain such a system.

It’s a task queue with focus on real-time processing, while also supporting task scheduling.


## [Dask](https://docs.dask.org/en/latest/)

<img src="https://dask.org/_images/dask_horizontal_white_no_pad.svg" height="100">

Dask is a flexible library for parallel computing in Python. Dask is composed of two parts:

1. Dynamic task scheduling optimized for computation. This is similar to Airflow, Luigi, Celery, or Make, but optimized for interactive computational workloads.
2. "Big Data" collections like parallel arrays, dataframes, and lists that extend common interfaces like NumPy, Pandas, or Python iterators to larger-than-memory or distributed environments. These parallel collections run on top of dynamic task schedulers.

## [Dask (Distributed)](https://distributed.dask.org)

<img src="https://dask.org/_images/dask_horizontal_white_no_pad.svg" height="100">

Dask.distributed is a lightweight library for distributed computing in Python. It extends both the `concurrent.futures` and `dask` APIs to moderate sized clusters. It is a centrally managed, distributed, dynamic task scheduler.

## [Luigi](https://github.com/spotify/luigi)

<img src="https://raw.githubusercontent.com/spotify/luigi/master/doc/luigi.png" height="100">

Luigi is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built in. The purpose of Luigi is to address all the plumbing typically associated with long-running batch processes. You want to chain many tasks, automate them, and failures will happen. 

## [Ray](https://ray.io/)

<img src="https://github.com/ray-project/ray/raw/master/doc/source/images/ray_header_logo.png" height="100">

A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library.
Ray programs can run on a single machine, and can also seamlessly scale to large clusters.

## [SCOOP](https://scoop.readthedocs.io/en/0.7/)

<img src="https://scoop.readthedocs.io/en/0.7/_images/logo.png" height="100">

SCOOP (Scalable COncurrent Operations in Python) is a distributed task module allowing concurrent parallel programming on various environments, from heterogeneous grids to supercomputers.

SCOOP has many features and advantages over Futures, multiprocessing and similar modules, such as:

- Harness the power of multiple computers over network;
- Ability to spawn subtasks within tasks;
- API compatible with PEP 3148;
- Parallelizing serial programs with only minor modifications;
- Efficient load-balancing.


