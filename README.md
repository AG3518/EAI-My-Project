
# Mood Tracker Project

MoodMirror: Daily Mood Tracker Using AI

## Summary

MoodMirror is a simple AI-based mood tracker that helps users reflect on their emotional state by analyzing short daily journal entries. The app uses natural language processing to detect mood and gives feedback with emotion tags and visuals.

## Background

Problem: Many people experience emotional ups and downs without understanding what causes them. Keeping track of mood patterns can improve self-awareness and mental well-being, but traditional journaling is time-consuming and inconsistent.

This project solves:
Lack of emotional awareness
No easy tool for mood reflection
Early support for mental well-being

Why it matters:
Mental health is a growing concern, especially for students, young professionals, and people under stress. A simple AI tool can encourage daily reflection without the pressure of formal therapy.

My motivation:
As an international student managing academics and adapting to new environments, I realized how important it is to understand emotional patterns. This project is my effort to make mood tracking easy, private, and accessible.


## How is it used?

Users open the app (or website), write a short sentence about how their day went, and submit it. The AI model analyzes the text and returns the emotion (e.g., happy, sad, anxious). The app shows a mood history graph over time.

Typical usage situation:
At the end of the day

At work, school, or home

Takes less than 1 minute daily

Users:
Students
Busy workers
People interested in self-reflection

Needs:
Easy to use
Mobile-friendly
Private (no sharing of personal data)

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">



## Data sources and AI methods
Data Sources:

GoEmotions Dataset by Google: 58k+ emotion-labeled English sentences

HuggingFace Pretrained Emotion Classifier

AI Methods:
Natural Language Processing (NLP)
Emotion classification using pre-trained DistilRoBERTa model
Visualization with basic charts (e.g., matplotlib or Plotly)

## Challenges

This project does not:
Replace mental health professionals
Handle complex language, sarcasm, or mixed emotions well
Support multiple languages yet (only English now)

Ethical considerations:
Data must not be stored without consent
Users must understand it’s only a reflective tool, not medical advice
Emotional predictions can sometimes be wrong or vague



## What next?

Future improvements:
Multilingual support (e.g., Finnish,English, Sinhala)
Voice input and reminders
Better emotion visualization and pattern detection
Privacy-protecting backend storage

Support needed:
Collaboration with psychology students
UI/UX designer for a cleaner interface
Deployment help to make it live

## Acknowledgments

Dataset: GoEmotions by Google Research
Emotion model: HuggingFace - DistilRoBERTa Emotion Classifier
Libraries used: transformers, streamlit, matplotlib, scikit-learn
Inspired by: Wysa, Moodpath, and Youper (AI mental wellness tools)
