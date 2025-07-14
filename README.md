# 💤 BetterRest

A SwiftUI iOS app that uses **Create ML** and **Core ML** to predict your ideal bedtime based on wake time, desired sleep, and coffee intake.

BetterRest is a SwiftUI-based iOS app that helps you calculate the optimal bedtime based on when you want to wake up, how much sleep you need, and how much coffee you drink.

This project is part of [Paul Hudson's 100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) – Day 27.

## 🧠 How It Works

The app uses a custom **machine learning model** created with [Create ML](https://developer.apple.com/machine-learning/create-ml/). Based on your:

- Desired wake-up time  
- Amount of sleep you want  
- Daily coffee intake  

…it predicts the amount of sleep you actually need, and tells you the ideal time to go to bed.

## 💻 Features

- Native SwiftUI interface  
- Sleep prediction using a Core ML model built with Create ML  
- Interactive UI with `DatePicker`, `Stepper`, and `Alerts`  
- Accessibility-friendly and simple UX  
