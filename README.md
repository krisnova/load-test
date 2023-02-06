# Load Test

Load testing for online hosts. 

### Running a test 

 1. Edit the `hosts` file with the hosts you have SSH backend access to. Each of these hosts will be used to execute your test in parallel.
 2. Edit the `test` file which is a bash script which will be executed on every host in the `hosts` file.
 3. Run the `./run`file to begin the tests.
 4. Tail the logs `tail -f out/*.log` to see stdout and stderr from the tests.

Note: You may add the same host to the `hosts` file more than once to run multiple copies of the same test on the host!
