# E-Commerce Impulse Buy Behavior Analysis

**Objective:** To analyze large-scale e-commerce transaction logs 
and extract behavioral signatures of impulse purchasing without 
relying on self-reported psychological surveys.

## Key Findings

- **Peak Traffic:** 69.6% of transactions occur during peak hours (10 AM – 2 PM)
- **Targeted Buying:** 7.5% of all invoices are single-item checkouts — a key signature of low-friction buying
- **Impulse Indicator:** 19.62% of transactions matched the refined impulse indicator (Small Quantity + Below-Median Spend + Peak Hour)
- **Geography:** United Kingdom leads impulse-pattern purchases (75,956 transactions)

## Methodology

Data Cleaning, Datetime Feature Engineering, Custom Behavioral KPIs

**Dataset Limitation:** The UCI Online Retail Dataset represents a 
UK-based wholesale (B2B) retailer. Single-item and rush-hour 
correlations serve as a conservative lower-bound estimate. 
Consumer-facing (B2C) platforms would exhibit stronger impulse signals.

## Tools

Python, Pandas, NumPy, Matplotlib

## Dataset

UCI Online Retail Dataset  
Download: https://archive.ics.uci.edu/dataset/352/online+retail

## Motivation

Inspired by research on AI-driven personalization cues and their 
effect on cognitive overload and impulsive buying behavior 
(Rai, Shukla & Pandey, 2025).
