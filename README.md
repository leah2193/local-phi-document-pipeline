Local PHI Document Pipeline

A fully local, privacy-preserving AI pipeline for extracting structured data — patient name, date of birth, and treatment dates — from ~65,000 scanned medical documents ranging from typed insurance forms to decades of handwritten chart notes. Built for a small HIPAA-regulated healthcare practice with a real, unsolved problem: an undifferentiated archive of scans with no way to search, index, or make informed retention decisions on it. No document or patient data ever leaves local hardware — extraction runs entirely on-device using local OCR and local LLMs, with a confidence-based routing system that sends clean, typed text through a lightweight text-only model and routes handwriting or low-confidence scans to a vision-capable model for direct image reading.

Status: Phase 1 (pilot) in progress. This README will be filled in with real results, architecture details, and the Harness Design section as the pilot completes.

Table of Contents (placeholder — build out as sections are written)
 Problem & Motivation
 Architecture Overview
 Harness Design (see harness-design-outline.md)
 Pilot Results (accuracy, confidence distribution, per-file timing)
 Tech Stack
 Setup / Usage
 Phase 2 Plan
 Lessons Learned

(Full README to follow once Phase 1 pilot results are in — see project-scope.md for current project status and decisions made to date.)
