# Alfred-workflow-reduce-size-of-JPEG-PNG-file
# Introduction

This workflow, which works as a Universal Action on a single, selected JPEG or PNG file:

- saves the *original* image in a temporary folder specified in the User Configuration;
- resizes the image file to the default longest side measurement specified in the User Configuration (measured in pixels);
- optionally allows saving of the resized image to the clipboard.

**Note**: The workflow does *not* enlarge images that already have a shorter longer side than specified in the User Configuration.

# Important note

If you use the default backup folder in the User Configuration the backup is to a temporary folder which is:
- automatically created if it does not exist; and
- *automatically deleted when your Mac restarts*.

*If you need to retrieve a backup you must move it from that default temporary folder before your Mac restarts*.

# Usage

Select a single JPEG or PNG file in Finder, use your Universal Actions hotkey and choose `Reduce size of JPEG/PNG file` to run the workflow.
