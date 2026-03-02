# Smart Attendance Monitoring System

The **Smart Attendance Monitoring System** is a web-based application built with **Python**, **Flask**, and **OpenCV** to automate student attendance using face recognition.

## Overview

The system captures facial images through a webcam, detects faces using a **Haar Cascade Classifier**, and recognizes them using the **LBPH (Local Binary Pattern Histogram)** algorithm.

Students must first register their faces. After registration, each student account remains in a **pending** state until approved by the administrator. Only approved students are allowed to mark attendance.

When a recognized face matches the trained dataset with acceptable confidence, the system automatically records:
- Student name
- Date
- Time

Attendance data is stored in an **SQLite** database.

## Admin Dashboard

The admin dashboard provides visibility into:
- Total number of students
- Pending student approvals
- Attendance records

## Benefits

This system helps to:
- Reduce manual attendance errors
- Prevent proxy attendance
- Improve operational efficiency

## Practical Value

The project demonstrates a practical, real-world implementation of:
- Computer vision techniques
- Web application development
- Automated attendance management workflows
