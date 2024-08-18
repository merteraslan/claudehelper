Changelog
All notable changes to the Claude Folder Uploader extension will be documented in this file.
The format is based on Keep a Changelog,
and this project adheres to Semantic Versioning.
1.3.0 - 2024-08-18
Added

Automatic detection and skipping of image files during upload process.
Comprehensive upload summary message including:

Number of successfully uploaded files
Number of skipped image files
Number of failed uploads (if any)



Changed

Implemented a 5-second delay before page refresh to ensure visibility of the upload summary.
Page now only refreshes if at least one file was successfully uploaded.
Consolidated various status messages into a single, comprehensive upload summary.

Fixed

Resolved an issue where users couldn't see the upload summary due to rapid page refresh.
