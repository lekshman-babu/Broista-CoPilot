# 📄 **JobDescriptionExtractor – Job Description Scraper & Skill Ranker**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-green)
![NLP](https://img.shields.io/badge/NLP-NLTK-orange)
![Database](https://img.shields.io/badge/Database-SQLite-lightgrey?logo=sqlite)
![Status](https://img.shields.io/badge/Status-Learning%20Project-purple)
![License](https://img.shields.io/badge/License-Not%20Specified-red)

---

## ✨ Overview

**JobDescriptionExtractor** is a Python-based project that extracts job descriptions from online job-description pages, cleans the extracted text, stores job-skill information in a SQLite database, and ranks skills based on their frequency across job descriptions.

The project demonstrates a simple end-to-end data extraction pipeline using **web scraping**, **text preprocessing**, **database storage**, and **skill-frequency analysis**.

---

## 🎯 Problem Statement

Job seekers and recruiters often need to understand which skills are commonly required across different job roles.

Manually reading multiple job descriptions is time-consuming, repetitive, and difficult to compare.

This project solves that problem by automatically extracting job requirements and identifying commonly occurring skills.

---

## 💡 Solution: *Job Description Extractor*

| Feature | Description |
|----------|-------------|
| 🌐 **Job Description Scraping** | Scrapes job-description content from online sources using BeautifulSoup. |
| 🧹 **Text Cleaning** | Removes punctuation and stopwords from extracted job-description text. |
| 🗃️ **SQLite Storage** | Stores job names and extracted skill descriptions in a local SQLite database. |
| 🔍 **Skill Matching** | Checks extracted descriptions against a predefined skill list. |
| 📊 **Skill Ranking** | Ranks skills based on how often they appear across job descriptions. |

---

## 🧰 Tech Stack

| Layer | Technologies |
|-------|--------------|
| **Language** | Python |
| **Web Scraping** | Requests, BeautifulSoup |
| **NLP / Text Processing** | NLTK, String Processing |
| **Database** | SQLite |
| **Data Storage** | Text Files, SQLite Table |

---

## 🏗️ Project Workflow

```text
Online Job Description Website
        ↓
first_week.py
        ↓
Scrape selected job descriptions
        ↓
demo.txt
        ↓
second_week.py
        ↓
Clean text and remove stopwords
        ↓
demo2.txt
        ↓
third_week.py
        ↓
Store job-skill data in SQLite
        ↓
fourth_week.py
        ↓
Rank skills by frequency
