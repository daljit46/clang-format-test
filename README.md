To test:

1. Install `pre-commit` via `pip install pre-commit` (note that you may need to add the pip scripts folder to your PATH).
2. Run `pre-commit install` in the source directory. This will install the clang-format git hook.
3. Now you can stage and commit files.

The commits should fail if the code isn't formatted properly. The formatting will be applied to fix the problem, and you will have to stage and commit those files again.
