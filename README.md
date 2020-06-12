# distributed-python

## Comparisons

- [Dask and Celery](https://matthewrocklin.com/blog/work/2016/09/13/dask-and-celery)
- [Ray comparison with Dask](https://github.com/ray-project/ray/issues/642)
- [Ray vs Dask](https://medium.com/@coolgeng/ray-vs-dask-d0154a774f2a)
- [Airflow + celery or dask. For what, when?](https://stackoverflow.com/questions/49310136/airflow-celery-or-dask-for-what-when)


## Dask
https://docs.dask.org/en/latest/

Dask is a flexible library for parallel computing in Python. Dask is composed of two parts:

1. Dynamic task scheduling optimized for computation. This is similar to Airflow, Luigi, Celery, or Make, but optimized for interactive computational workloads.
2. "Big Data" collections like parallel arrays, dataframes, and lists that extend common interfaces like NumPy, Pandas, or Python iterators to larger-than-memory or distributed environments. These parallel collections run on top of dynamic task schedulers.

## Dask (Distributed)
https://distributed.dask.org

Dask.distributed is a lightweight library for distributed computing in Python. It extends both the `concurrent.futures` and `dask` APIs to moderate sized clusters. It is a centrally managed, distributed, dynamic task scheduler.

## Ray
https://ray.io/

A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library.
Ray programs can run on a single machine, and can also seamlessly scale to large clusters.

## SCOOP
https://scoop.readthedocs.io/en/0.7/

SCOOP (Scalable COncurrent Operations in Python) is a distributed task module allowing concurrent parallel programming on various environments, from heterogeneous grids to supercomputers.

SCOOP has many features and advantages over Futures, multiprocessing and similar modules, such as:

- Harness the power of multiple computers over network;
- Ability to spawn subtasks within tasks;
- API compatible with PEP 3148;
- Parallelizing serial programs with only minor modifications;
- Efficient load-balancing.

## Celery

https://docs.celeryproject.org

Celery is a simple, flexible, and reliable distributed system to process vast amounts of messages, while providing operations with the tools required to maintain such a system.

It’s a task queue with focus on real-time processing, while also supporting task scheduling.




