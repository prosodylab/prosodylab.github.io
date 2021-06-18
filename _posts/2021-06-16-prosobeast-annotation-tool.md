---
layout: post
title: "prosoBeast"
excerpt_separator: "<!--more-->"
categories:
  - news
tags:
  - software
---

At this fall's interspeech, we'll be presenting a paper on our *prosoBeast*, an annotation tool for looking at intonation:

Gerazov B. and M. Wagner (in press). ProsoBeast Prosody Annotation Tool. Proceedings of Insterspeech in Brno. ArXiv e-prints. [[paper]](https://arxiv.org/abs/2104.02397) [[git]](https://github.com/prosodylab/prosobeast-annotation-tool)


<img src="{{ site.baseurl }}/assets/images/2021/06/tool.png" width="500">


> The labelling of speech corpora is a laborious and time-consuming process.
The ProsoBeast Annotation Tool seeks to ease and accelerate this process by providing an interactive 2D representation of the prosodic landscape of the data, in which contours are distributed based on their similarity.
This interactive map allows the user to inspect and label the utterances.
The tool integrates several state-of-the-art methods for dimensionality reduction and feature embedding, including variational autoencoders.
The user can use these to find a good representation for their data.
In addition, as most of these methods are stochastic, each can be used to generate an unlimited number of different prosodic maps.
The web app then allows the user to seamlessly switch between these alternative representations in the annotation process.
Experiments with a sample prosodically rich dataset have shown that the tool manages to find good representations of varied data and is helpful both for annotation and label correction.
The tool is released as free software for use by the community.