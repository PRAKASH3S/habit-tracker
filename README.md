# HabitForge — Daily Habit Tracker

A sleek, dark-themed habit tracker that runs entirely in your browser. No backend, no signup — just discipline.

## Habits tracked
- Exercise / Gym
- Reading
- Coding / Side projects
- Prayer / Devotional
- Job applications (20/day)
- Build 1 project/week
- Wake up by 6 AM
- + Add custom habits anytime

## Features
- **Two modes**: Simple done/not-done, or rate quality 1–5
- **Dashboard**: Overall consistency score, streak tracking (current + longest), monthly completion bars, heatmap, weekly trend charts
- **Persistent**: Data saved in localStorage — survives browser restarts
- **PWA ready**: Add to homescreen on mobile for app-like experience
- **Responsive**: Works on phone, tablet, desktop
- **Offline**: No internet needed after first load

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g., `habit-tracker`)
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/habit-tracker.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**
4. Your tracker is live at `https://YOUR_USERNAME.github.io/habit-tracker/`

## Add to homescreen (mobile)
- **iOS**: Open in Safari → Share → Add to Home Screen
- **Android**: Open in Chrome → Menu → Add to Home Screen

## Tech
Pure HTML/CSS/JS. Chart.js for visualizations. Zero dependencies to install.
