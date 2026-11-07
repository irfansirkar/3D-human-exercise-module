# Robust-3D · 3D human exercise module

A fitness coach that turns a photo into a 3D body model, then builds targeted workouts, a diet plan and progress tracking around it.

**Live demo:** https://irfansirkar.github.io/3D-human-exercise-module/

**Mohammad Irfan Sirkar** was lead developer at **HackRev 2025**.

## How it works

1. **Photo in.** Pose estimation finds key body points in a front-facing photo.
2. **3D body.** The points fit a parametric 3D body model, which gives measurements.
3. **Plan.** Weak areas and the user's goal (lose fat, build muscle or posture) choose exercises, sets and a calorie target.
4. **Track.** New photos update the model to show progress.

## About the demo

The demo in `docs/` runs in the browser. It has 3 sample body profiles, a 3D mannequin you can drag to rotate, a 4-week plan for each goal, daily nutrition and a projected progress chart. The mannequin is a simple adjustable model, not one reconstructed from a real photo. **It is not medical advice.**
