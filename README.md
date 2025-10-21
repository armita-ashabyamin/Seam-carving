# Seam-carving
Seam Carving is a Python-based tool for content-aware image resizing and object removal. It uses energy maps and seam manipulation to resize images while preserving important content. Supports protection masks and object removal.
Seam Carving for Content-Aware Image Resizing

This project implements a seam carving algorithm for intelligent image resizing and object removal. Seam carving is a technique that resizes images by removing or inserting seams—paths of least importance—while preserving the image's key content. This implementation supports resizing with optional protection masks and object removal using energy maps and forward/backward cumulative energy calculations.
✨ Features

    Resize images vertically and horizontally by removing or inserting seams

    Protect important regions using a mask

    Remove unwanted objects from images

    Forward and backward energy map computation

    Seam tracking and reinsertion

    Rotation handling for horizontal seam operations

🧠 Algorithm Highlights

    Uses Scharr operator for energy map calculation

    Applies forward energy maps for optimal seam selection

    Seam insertion/removal with mask support

    Object removal by iterative seam deletion

    Seam tracking and reinsertion for image expansion

📦 Dependencies

    numpy

    cv2 (OpenCV)

    matplotlib
