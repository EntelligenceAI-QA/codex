# ENT-4747 alpha PR-review smoke test

Trigger stamp: 20260921T233042Z

Verifies that a pull_request webhook on an alpha-connected repo
reaches the alpha backend and drives pr-review-alpha-alpha.

    def add(a, b):
        return a - b   # deliberate bug for the reviewer to find
