# 6_1_ELK_STACK

A.  Create two linux servers,
     server1 => install and configure kibana and elasticsearch with basic username and password authentication
     server2 => install and configure metricbeat.

   Collect metric from following sources in server1 and send them to elasticsearch. Store them in an index named "server1-metrics".
    a. Memory usage
    b. Disk usage
    c. Load average

  1. Create a dashboard in kibana and generate visual report(line graph) for Memory usage and load average of server1 with relation to time

  2. Generate alerts through kibana system for following thresholds
    a. when memory usage > 80% for last 2 minutes send alert to a slack channel
    b. When Disk usage > 70%   send alert to a slack channel
    c. When load average > 1  for last 2 minutes  send alert to a slack channel
