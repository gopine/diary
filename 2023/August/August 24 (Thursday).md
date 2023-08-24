# August 24, 2023

I added support for web workers to improve performance.

The heavy computations are now done in background threads.

This prevents the UI from freezing during long operations.

The initial implementation was challenging, but the performance gains are significant.