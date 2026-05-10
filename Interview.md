What is the trigger? The trigger is push, but it is restricted by a branches filter.

What is ${{ github.ref_name }}? It’s a GitHub Context Variable. It allows the workflow to be "self-aware"—it knows exactly which branch it is running on without you having to hardcode it.

Why use ubuntu-latest? It is the standard, lightweight Linux runner provided by GitHub. It’s fast and compatible with most web and backend tools.

Common Error: Indentation. In YAML, - main must be indented exactly two spaces under branches:.