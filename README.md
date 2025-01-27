# Expo Go Incompatibility with Native Modules

This repository demonstrates a bug encountered when using Expo Go with a native module. The issue arises from incompatibility between the module and the Expo Go environment, resulting in crashes or unexpected behavior within the application.

## Problem Description

The application utilizes a native module that functions correctly when built and deployed via EAS Build. However, when running the application in Expo Go, it experiences crashes or unpredictable behavior.  The root cause seems to be limitations or discrepancies in the Expo Go runtime environment's support for the native module's capabilities.

## Solution

The solution provided in this repository addresses the compatibility issues by modifying how the native module is integrated with the Expo Go environment. This might involve using a different approach for interaction, implementing workarounds for missing functionalities, or utilizing alternative modules within Expo Go's limitations.

## Steps to Reproduce

1. Clone the repository.
2. Navigate to the project directory.
3. Install the dependencies using `npm install`.
4. Attempt to run the application in Expo Go.  Observe the error or unexpected behavior.
5. Run the application using EAS Build and observe the expected functionality.
6. Review the solution provided in `bugSolution.js` to understand the changes that correct the problem.

## Note

This bug highlights a specific limitation when testing native modules directly within the Expo Go environment. For reliable testing and deployment, consider utilizing alternative methods such as EAS Build.