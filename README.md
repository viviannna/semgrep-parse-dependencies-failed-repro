# Dependency parsing repro

Minimal Python project with an intentionally unsupported format version in `uv.lock`.

Scan with Supply Chain enabled. Lockfileless scanning is not required.
Expected error: `ParseDependenciesFailed`.
