# AndroidTestCoverageIssue
This is a repository to demonstrate the 0% code coverage being reported by jacoco in Android despite the fact that it should be 100%.

## Steps to reproduce
1) clone the repository
2) run ./gradlew connectedCheck
3) open 'AndroidTestCoverageReport/app/build/reports/coverage/debug/index.html'
4) verify test coverage reads 0%, when it should be 100%
