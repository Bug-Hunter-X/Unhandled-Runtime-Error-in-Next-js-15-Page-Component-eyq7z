# Unhandled Runtime Error in Next.js 15 Page Component

This repository demonstrates a common runtime error in Next.js 15 applications where accessing an undefined variable within a page component leads to an unhandled error, resulting in a blank screen.

## Problem

The `about.js` file attempts to access the undefined variable `unexist`. This results in a runtime error that Next.js doesn't gracefully handle by default.

## Solution

The `aboutSolution.js` file shows how to resolve the issue using appropriate error handling techniques.  The solution implements a `try...catch` block to capture the error and display a user-friendly message instead of crashing the page.