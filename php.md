- **What are the difference between require, include, require_once and include_once.**

  The `require()` function is identical to `include()`, except that it handles errors differently. If an error occurs, the `include()` function generates a warning, but the script will continue execution. The `require()` generates a fatal error, and the script will stop.

  The `require_once()` statement is identical to `require()` except PHP will check if the file has already been included, and if so, not include (require) it again.
