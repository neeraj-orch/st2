python_tests(
    overrides={
        "test_action_download.py": {
            "dependencies": [
                # imports tests.fixtures which is ambiguous. Tell pants which one to use.
                "contrib/packs/tests/fixtures",
            ],
        }
    },
)
