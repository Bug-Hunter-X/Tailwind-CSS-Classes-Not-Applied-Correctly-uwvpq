# Tailwind CSS Classes Not Applied Correctly
This repository demonstrates a common issue in Tailwind CSS where classes aren't applied as expected. The problem stems from unexpected CSS specificity or conflicting styles. The solution involves using the `!important` flag or adjusting the CSS specificity to ensure the Tailwind classes are prioritized. 

## Bug
The provided code snippet shows two divs with Tailwind CSS classes intended to set their background colors to red and blue respectively. However, due to unexpected specificity or a missing configuration, the background colors are not correctly rendered.