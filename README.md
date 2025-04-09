# ninjaone-qa-task

This is Jun Park's SQE assignment submission for NinaOne.

## Notes for reviewers

All test cases can be found in test_cases.txt file. Tests cases for the login page includes various types of test cases including security and load/performance test cases. These tests have been intentionally excluded for other non-login page tests to avoid repetitiveness but the same methods would apply. UI automated tests for the login page have been written using cypress and integrated to run using github action workflow on each commit using chrome as the main browser. To review automated test runs, simply navigate to [Actions](https://github.com/jpark-ninjaone/ninjaone-qa-task/actions).