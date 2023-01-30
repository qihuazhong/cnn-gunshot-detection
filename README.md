# cnn-gunshot-detection

## Introduction

This repo contains an archived notebook that won the #1 place of Team Challenge 3 (Gunshot Audio Detection) in the CodeML 2022 Hackathon, hosted in Polytechnique Montréal. Coded in collaboration with [Oulbacha Reda](https://github.com/Roulbac).

## The challenge

from: https://hxbuddy.codeml.ca/

![description of the challenge](.\asset\description.png "Description")

## The Winning Solution

- [x] A custom CNN that scans globally on the feature axis but locally on the time axis.

- [x] **Over-sampling positive samples during training**

## Other Solutions we tried
Solutions/techniques that we tried but not included in the final submission.

- [x] XGboost

- [x] Data augmentation (Augmentation does not improve result in this challenge)

## Result

Team - The careless sparks

Accuracy: 99.64%, Fq_score: 97.49%, Robustness: 95.5%

![leaderboard](.\asset\leaderboard.png "Leaderboard")
