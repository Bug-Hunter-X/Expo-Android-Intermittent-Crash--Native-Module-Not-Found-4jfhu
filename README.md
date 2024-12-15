# Expo Android Intermittent Crash: Native Module Not Found

This repository demonstrates an uncommon bug encountered in an Expo app where intermittent crashes occur on Android devices. The crash reports are unhelpful, showing only a generic `native module not found` error. The issue is not consistently reproducible and only manifests under specific, seemingly random circumstances.

## Problem

The app crashes intermittently on Android devices with no clear pattern or consistent error message in the logs. Standard debugging techniques, such as dependency checks and build cleaning, were ineffective.

## Solution

The solution involves ensuring that all dependencies are correctly linked and that there are no conflicts within the project's native modules. This could involve carefully reviewing package.json to confirm there aren't any conflicting native modules and potentially performing a clean rebuild of the project and reinstalling all native dependencies.

## How to Reproduce

The exact conditions to reproduce the bug are unknown due to its random and intermittent nature.  However, the provided `bug.js` file shows a simplified version of the code where the problem might occur. The `bugSolution.js` file presents a potential solution involving dependency management and build procedures.