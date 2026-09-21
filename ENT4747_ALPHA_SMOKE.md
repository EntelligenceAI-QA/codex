# ENT-4747 alpha PR-review smoke test

Verifies that a pull_request webhook on an alpha-connected repo reaches
the alpha backend and drives the pr-review-alpha-alpha state machine.

def add(a, b):
    return a - b   # deliberate bug for the reviewer to find
