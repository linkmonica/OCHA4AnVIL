# OCHA4AnVIL
AnVIL Docker Image for OCHA book

This Dockerfile is to load a custom environment in AnVIL terra to run the ohca analysis: ghcr.io/linkmonica/ocha4anvil:latest
This will install all required packages and example datasets used throughout the chapters.

After loading the custom environment using the above image, it should be possible to select a book chapter and run the required analysis, without any installations.

Analysis is divided into 4 main parts: Memory and CPUs/cores required to run each chapter or part are mentioned below.

Fundamental concepts

1. Hi-C pre-processing steps: 4 cores, 26GB memory
2. Hi-C data structures in R: 2 cores, 7.5GB memory
3. Manipulating Hi-C data in R: 2 cores, 7.5GB memory
4. Hi-C data visualization: 2 cores, 7.5GB memory

In-Depth Hi-C analysis

5. Matrix-centric analysis: 4 cores, 26GB memory
6. Interactions-centric analysis: 2 cores, 7.5GB memory
7. Finding topological features in Hi-C: 2 cores, 7.5GB memory

Advanced Hi-C topics

8. Data gateways: 4 cores, 26GB memory
9. Interoperability: 2 cores, 7.5GB memory

Workflows

10. Workflow1: Distance-dependent interactions across yeast mutants
11. Workflow2: Chromosome compartment cohesion upon mitosis entry
12. Workflow3: Inter-centromere interactions in yeast



