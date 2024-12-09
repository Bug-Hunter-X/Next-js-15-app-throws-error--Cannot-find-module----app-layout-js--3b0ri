# Next.js 15 - Cannot find module './app/layout.js'

This repository demonstrates a common error encountered when upgrading to Next.js 15: the inability to find the `./app/layout.js` module.  This error typically arises due to incorrect directory structure or missing configuration within the Next.js application.

## Problem

When running a Next.js 15 application, the following error may occur:

`Error: Cannot find module './app/layout.js'`

This indicates that Next.js cannot locate the `layout.js` file, which is crucial for the application's layout and routing.  The problem could stem from a mismatch between the expected file path and the actual file location. 

## Solution

The solution involves ensuring the `layout.js` file exists in the correct directory (`pages` or `app`) and that Next.js is configured correctly.

Ensure that your Next.js project has a file at `app/layout.js` for the new app directory routing style. If using the pages directory, ensure that a file named `pages/_app.js` exists.