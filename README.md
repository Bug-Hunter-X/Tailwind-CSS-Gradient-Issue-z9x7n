# Tailwind CSS Gradient Issue

This repository demonstrates an issue with unexpected color transitions or a missing gradient when using Tailwind CSS's `bg-gradient-to-r` utility.

## Bug Description:

The gradient transition between `from-blue-500` and `to-purple-500` does not render correctly or is missing entirely, resulting in a solid color.

## Steps to Reproduce:

1. Include Tailwind CSS in your project.
2. Use the provided code snippet in your HTML.
3. Observe that the gradient does not apply as expected.

## Expected Behavior:

The div element should display a smooth gradient transition from blue to purple.

## Actual Behavior:

The div element displays a solid color (usually the starting color of the gradient).

## Solution:

The problem may arise from missing or improperly configured Tailwind CSS setup. Ensure you have the correct Tailwind configuration, including the `purge` and `safelist` options if necessary.  Ensure also your HTML and CSS file are correctly linked to your project and that your build process includes postcss compilation.