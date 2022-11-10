# Core

DataJoint Core projects are fully open-source and are built to develop, define, manage,
and visualize [data pipelines](../glossary#data-pipeline). Below are the projects that
make up the family of core open-source projects.

## APIs

<div class="grid cards" markdown>

-   :fontawesome-brands-python:{ .lg .middle } **DataJoint Python**

    ---

    A low-level client for managing [data pipelines](../glossary#data-pipeline).

    [:octicons-arrow-right-24: Getting started](./datajoint-python/)

-   :fontawesome-brands-java:{ .lg .middle } **DataJoint MATLAB**

    ---

    A low-level client for managing [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

-   :fontawesome-solid-flask:{ .lg .middle } **Pharus**

    ---

    Expose [data pipelines](../glossary#data-pipeline) via a
    [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) interface.

    `Docs coming soon!`

</div>

## Web GUIs

<div class="grid cards" markdown>

-   :fontawesome-brands-chrome:{ .lg .middle } **LabBook**

    ---

    Data entry and data model browsing for [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

-   :fontawesome-brands-chrome:{ .lg .middle } **SciViz**

    ---

    A visualization framework for making
    [low-code](https://en.wikipedia.org/wiki/Low-code_development_platform) web apps
    for [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

</div>

## Container Images

``` mermaid
graph
  datajoint/mysql;
  datajoint/miniconda3 --> datajoint/djbase;
  datajoint/djbase --> datajoint/djtest;
  datajoint/djbase --> datajoint/datajoint;
  datajoint/djbase --> datajoint/djlab;
  datajoint/djlab --> datajoint/djlabhub;
```

<div class="grid cards" markdown>

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/mysql**

    ---

    An optimized, MySQL backend for [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/miniconda3**

    ---

    A minimal Python image with [conda](https://docs.conda.io/en/latest/).

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/djbase**

    ---

    Adds only dependencies for managing [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/djtest**

    ---

    Adds testing tools like [pytest](https://docs.pytest.org/en/7.1.x/).

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/datajoint**

    ---

    Official image for managing [data pipelines](../glossary#data-pipeline).

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/djlab**

    ---

    Adds a local [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) environment.

    `Docs coming soon!`

-   :fontawesome-brands-docker:{ .lg .middle } **datajoint/djlabhub**

    ---

    Adds a client to allow hosting with [Jupyter Hub](https://jupyter.org/hub).

    `Docs coming soon!`

</div>