## 1.7.0.20250425 (2025-04-25)

Complete `flake8-docstrings` (#13872)

## 1.7.0.3 (2023-07-20)

Add an upstream_repository field to METADATA.toml (#10487)

Closes: #10478

## 1.7.0.2 (2023-05-10)

Add `partial_stub` metadata field (#10157)

## 1.7.0.1 (2023-02-21)

Stubtest settings: change `ignore_missing_stub` default to `false` (#9779)

If you're reading about this commit from an autogenerated changelog entry, this should have no user-visible impact on how the stubs are interpreted by a type checker; it's just an internal change to how typeshed's tests work.

## 1.7.0.0 (2023-01-26)

[stubsabot] Bump flake8-docstrings to 1.7.* (#9589)

Release: https://pypi.org/pypi/flake8-docstrings/1.7.0
Homepage: https://github.com/pycqa/flake8-docstrings
Diff: https://github.com/pycqa/flake8-docstrings/compare/1.6.0...1.7.0

Stubsabot analysis of the diff between the two releases:
 - 0 public Python files have been added.
 - 0 files included in typeshed's stubs have been deleted.
 - 1 file included in typeshed's stubs has been modified or renamed: `flake8_docstrings.py`.
 - Total lines of Python code added: 93.
 - Total lines of Python code deleted: 94.

If stubtest fails for this PR:
- Leave this PR open (as a reminder, and to prevent stubsabot from opening another PR)
- Fix stubtest failures in another PR, then close this PR

Note that you will need to close and re-open the PR in order to trigger CI

Co-authored-by: stubsabot <>

## 1.6.3.1 (2022-10-15)

Use `Incomplete` instead of `Any` in `__getattr__` (#8903)

## 1.6.3 (2022-04-16)

Third-party stubs: import from `collections.abc` where possible (#7637)

## 1.6.2 (2022-01-08)

Use lowercase `type` everywhere (#6853)

## 1.6.0 (2021-12-06)

Add stubs for flake8-docstrings (#6507)

Co-authored-by: Akuli <akuviljanen17@gmail.com>

