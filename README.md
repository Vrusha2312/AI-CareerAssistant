# AI Career Assistant

Final project for the Building AI course

## Summary

AI Career Assistant is an AI-powered platform that helps students and job seekers identify suitable career paths based on their skills, education, and interests, using NLP and recommendation systems to suggest careers, learning resources, and jobs.

Building AI course project

## Background

Many students and fresh graduates struggle to find the right career direction. They often apply to jobs without knowing which skills are missing, or spend time learning skills that don't match what employers actually want. Personalized career counseling is expensive or simply unavailable to most people.

This is a problem I've experienced directly — after graduating, figuring out what skills to prioritize and which roles to target felt overwhelming with no clear guidance.

* Lack of access to personalized career counseling
* Difficulty identifying skill gaps for a target role
* Wasted time learning skills that don't match job market demand
* Overwhelming number of career paths with no way to filter by personal fit

## How is it used?

A user enters their education background, current skills, and interests into the assistant. The AI analyzes this against real job market data and returns:

* A ranked list of suitable career paths
* The specific skills missing for each path
* Recommended courses or resources to close those gaps
* Relevant job/internship listings matching their profile

**Users:** Recent graduates, students choosing a specialization, career switchers, and college placement cells that want to guide students at scale.

## Data sources and AI methods

**Data:**
* Job postings and required-skills data (e.g. from public job board APIs)
* Online course catalogs (e.g. Coursera, edX metadata) for learning resource suggestions
* User-provided profile data (skills, education, interests)

**AI methods:**
* Natural Language Processing (NLP) — to parse resumes/profiles and job descriptions
* Recommendation systems — to match user profiles to career paths and resources
* Machine learning classification — to rank career-fit based on skills and interests

## Challenges

This project does not replace human career counselors, especially for nuanced decisions involving personal circumstances, mental health, or non-quantifiable factors. It also depends heavily on the quality and freshness of job market data — outdated data could lead to bad recommendations. There's also a risk of reinforcing bias if training data over-represents certain roles or demographics, so fairness in recommendations needs ongoing checking.

## What next?

* Add resume-analysis to auto-detect current skills instead of manual entry
* Partner with college placement cells to pilot with real students
* Expand to India-specific job market and course data
* Add a mentorship-matching feature connecting users with professionals in their target field

## Acknowledgments

* Building AI Course (Reaktor Innovations and University of Helsinki)
* Open-source NLP and recommendation system libraries
* Public job market and course datasets
