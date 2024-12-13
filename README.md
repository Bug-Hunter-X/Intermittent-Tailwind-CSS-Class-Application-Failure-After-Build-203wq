# Intermittent Tailwind CSS Class Application Failure After Build

This repository demonstrates an uncommon bug encountered with Tailwind CSS where the application of classes becomes inconsistent after the build process.  The issue is intermittent and difficult to reproduce reliably.  The `bug.js` file contains example code illustrating where the problem manifests.  The `bugSolution.js` provides a potential solution (though the root cause remains unclear).

## Bug Description

Classes defined in the Tailwind CSS configuration file are not consistently applied after running the build process. The issue is not related to syntax errors or obvious configuration problems. The application of Tailwind CSS classes sometimes works correctly, and other times it fails without an easily identifiable pattern.