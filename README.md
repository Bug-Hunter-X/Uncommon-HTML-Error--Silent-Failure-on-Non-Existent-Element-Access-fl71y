# Uncommon HTML Error: Silent Failure on Non-Existent Element Access

This repository demonstrates a subtle error in HTML/JavaScript interaction.  Attempting to access a non-existent element using `document.getElementById()` does not throw an error but simply fails silently. This can be a source of difficult-to-debug issues.

The `bug.html` file contains the erroneous code.  The `bugSolution.html` file demonstrates the correct approach, using error handling to gracefully manage the case where the element might not exist.