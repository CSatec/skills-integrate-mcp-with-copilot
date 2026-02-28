# Support file I/O and PDF conversion

Allow the application to write generated documents (e.g. DOCX) to disk and optionally convert them to PDF. The workflow might involve invoking external tools such as `abiword` or using a library.

**Requirements:**
- Save output files with sanitized names
- Convert to PDF automatically or on demand
- Clean up temporary files after conversion
