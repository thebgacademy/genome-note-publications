# genome-note-publications

#BGA24/sessions #GitPod #Pipeline #Nextflow

This session is part of [**Biodiversity Genomics Academy 2024**](https://thebgacademy.org)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/thebgacademy/genome-note-publications) 

## Session Leader(s)

Wellcome Sanger Institute

- [Bethan Yates](https://uk.linkedin.com/in/bethanyates)
- [Tyler Chafin](https://www.sanger.ac.uk/person/chafin-tyler/)
- [Matthieu Muffato](https://www.sanger.ac.uk/person/muffato-matthieu/)

## Description

In this session you will learn how to automatically generate content for genome note publications using our suite of analysis pipelines <https://pipelines.tol.sanger.ac.uk/>.

## Part 1: An introduction to Genome Notes

By the end of this part you will have:

1. Obtained an overview of the Tree of Life programme and our genome note concept
2. Understood the purpose of a genome note and the information it reports
3. Gained an idea of why automating genome note production is important and how this can be achieved

## Part 2: Hands on - Running the sanger-tol/genomenote pipeline and exploring the outputs

By the end of this part you will be able to:

1. Run the sanger-tol/genomenote pipeline to produce a genome note document
2. Understand how to use the pipeline to generate genome notes for your own genomes
3. Gained an idea of how different pipelines can be combined to go from raw sequencing data to a publication reporting a genome assembly

## The nextflow command to run the pipeline

    nextflow run genomenote/main.nf \
    -profile docker,arm \
    -params-file assets/BGA-test.json \
    --outdir BGA_test_results

## Useful links 

- The published [genome note](https://wellcomeopenresearch.org/articles/9-539) for the species used in this session.
- The HiGlass link to the [Hi-C map](https://genome-note-higlass.tol.sanger.ac.uk/l/?d=N0lSy7fGQ7SSE1afN54MCg) for the species used in this session.
- The [sanger-tol pipelines website](https://pipelines.tol.sanger.ac.uk/) 

## Prerequisites

1. Familiarity with linux command line basics (cd, mv, rm)
2. Knowledge of the Nano editor will be helpful

!!! warning "Please make sure you MEET THE PREREQUISITES and READ THE DESCRIPTION above"

    You will get the most out of this session if you meet the prerequisites above.

    Please also read the description carefully to see if this session is relevant to you.
    
    If you don't meet the prerequisites or change your mind based on the description or are no longer available at the session time, please email damon at thebgacademy.org to cancel your slot so that someone else on the waitlist might attend.
