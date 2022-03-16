---
title: Getting Started
---

Never touched software development a day in your life?
Then you are in the right place.

## Flowcharts

As content is added to this site, this flow chart will be expanded and will be linked to where you can find the information.

### First Flow Chart

My hope for this flow chart, is to allow you to get your feet wet in Software Development and DevOps.
This is a condensed version of how I got interested in technology to begin with, and how I developed my knowledge.

{{<mermaid class="text-center">}}
flowchart TD
    classDef checkpoint fill:#8a8481;

    FW(First Website)
    JS(JavaScript)
    WH(Web Hosting)
    GIT(Git)

    FW:::checkpoint-->JS
    FW-->WH

    JS-->GIT
    WH-->GIT

    FA(First API)
    NJ(NodeJS)
    NPM(NPM)
    PR(Proxy)

    GIT-->FA:::checkpoint

    FA-->NJ
    NJ-->NPM

    FA-->PR

    AWS(AWS)
    LM(Lambdas)
    TF(Terraform)

    NPM-->AWS:::checkpoint
    PR-->AWS

    AWS-->LM
    LM-->TF

    END(Done)

    TF-->END:::checkpoint

{{</mermaid>}}