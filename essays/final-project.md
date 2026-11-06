---
layout: essay
type: essay
title: "Final Project Idea"
# All dates must be YYYY-MM-DD format!
date: 2026-11-04
published: true
labels:
  - Software Engineering
  - Nextjs
  - AI Assistant
  - Campus Community
  - ICS 314
---

## Project: Studymate

**Proposers:**

- Chicco Ray Marquez (chicco@hawaii.edu)
- Rocky Acasio (rocky99@hawaii.edu)
- Rodemar Cadiz (rcadiz24@hawaii.edu)

## Overview

**The Problem:** Students have a hard time finding other students to study with. It's hard to find people with the same classes, similar schedules, and similar academic goals to each other. 

**The Solution:** StudyMate is a web app available to UH students to find study partners or groups. Students can enter their classes, availability, study preferences, and GPA and the site matches them with compatible students. This GPA is a hidden value that's never shown to other users. Users can filter by course, schedule, study style, group size, and in-person or online sessions.

## Approach

The site will use Next.js, React, Bootstrap 5, Prisma with PostgreSQL, and GitHub.

## Roles

- **Users:** UH Manoa students who sign up with their UH email. The users get to build their profile (with classes, availability, study goals, and GPA) search and filter for study partners or groups, send and accept study requests, and join or create groups.
- **Admins:** Manage the course list, remove accounts that violate rules, view usage stats.

## Mockup Page Ideas

- **Landing Page:** Explains what StudyMate is with a "how it works" section, a tutorial, and sign up and login buttons.
- **Sign Up / Profile Setup Page:** Form for UH email, major, classes, availability, study style,  GPA range (not required).
- **Find a Studymate Page:** List of suggested matches with filters for course, availability, study style, group size, and location. Swipe left or right and look at the description of the Studymate on your screen
- **My Groups Page:** Shows groups you’ve joined, upcoming sessions, and members.
- **Group / Session Page:** Details for a study session, including time, meeting spot (on campus), and a member list.
Admin Dashboard: User management, and course list editor.

## Use Case Ideas

- Student signs up with their UH email and sets up a profile with their classes and availability.
- Student filters by a specific course and finds others who also have those courses or had.
- Student sends a study request to a match, and the other student also has them queued in their feed.
- Student creates a study group for an upcoming exam and sets a size limit and meeting spot.
- Student leaves a group or cancels a session.
- Admin reviews accounts and suspicious accounts could be deleted.
- Admin adds a new course to the course list. 

## Beyond the Basics

After implementing the basic functionality, here are ideas for more advanced features:

- Calendar sync (Google Calendar) to find shared free times automatically
- In-app chat or messaging between matched students
- Ratings or “good study partner” badges after sessions
- Email or push reminders for upcoming study sessions
- A campus map showing suggested meeting spots
- Tutor or peer mentor connections
