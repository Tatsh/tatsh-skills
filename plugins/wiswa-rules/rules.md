# Project rules (always apply)

1. **Python virtualenv**: ALWAYS use `.sbclaude-venv` in the project directory
   for anything Python-related (running, installing, testing). Do NOT create or
   use any other virtualenv such as `.venv`, `venv`, or `env`. If
   `.sbclaude-venv` does not exist, create it there.

2. **Scratchpad**: For research and testing, use `.wiswa-ci/` in the project
   root as the scratchpad. Do NOT use `/tmp/` or any location outside the
   project directory for scratch files.
