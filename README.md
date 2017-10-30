# cs3700-project3
Project 3: Simple Transport Protocol

Approach
1. First made sure that tests were working by sending individual packets
2. Handled duplicate packets
3. Handled dropped packets
4. Handled reordered packets
5. Handled delayed packets
6. Handled latency issue with dynamic RTTs
7. Implemented sliding window

Challenges:
1. Did not know about the --live command until later
2. When changing code, some tests ran while others failed. Fixing one problem lead to another thing breaking.
3. It was hard to find out how to get the ideal side for sliding window

Overview:
1. Tested the code after each time changes were made, kept different copies in git repo
2. If one thing failed, set up the netsim with the failed settings and --live to debug
3. Repeat until fixed, then run the whole test again to see what it broke.
