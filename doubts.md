
you always perform the build first, then test after build.

Why?
Build:
This step compiles your code, creates artifacts (binaries, Docker images, etc.), and prepares your project for execution.

Test:
Once the build is successful, you run tests (unit, integration, etc.) on the built output to verify everything works correctly.

Workflow Order
Build → 2. Test → (then maybe Deploy, etc.)
