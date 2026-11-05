Ping Fundamentals — Week 1

1. What is Ping?

Ping is a command-line networking tool used to test connectivity between my computer and another device or server over a network.

It sends small packets of data to a destination and measures whether a response is received and how long the round trip takes.

2. Exercise: Testing Network Connectivity

Command:

ping -c 4 tdmax.com

What I learned:

ping starts the connectivity test.

-c 4 tells the command to send 4 packets and then stop.

tdmax.com is the destination hostname being tested.

3. Results

My terminal returned the following results:

Metric

Result

Packets transmitted

4

Packets received

4

Packet loss

0%

Minimum latency

36.287 ms

Average latency

53.726 ms

Maximum latency

89.527 ms

4. Understanding the Results

Packet loss: 0%

All four packets received a response. No packet loss was recorded during this test.

Latency: 53.726 ms average

Latency measures the time it takes for a packet to travel to its destination and for the response to return.

Lower latency generally means faster communication between devices.

Minimum and maximum latency

The minimum was 36.287 ms, while the maximum was 89.527 ms. This shows that response times can vary during a network test.

5. What I Learned

Through this exercise, I learned:

How to test connectivity using the terminal.

How to interpret transmitted and received packets.

What packet loss means.

How to measure network latency.

Why connectivity testing is useful when troubleshooting network issues.

6. Why This Matters for Cloud Engineering

Cloud engineers need to understand network connectivity when working with cloud servers, virtual machines, and distributed applications.

Ping is a basic troubleshooting tool that can help determine whether a destination is responding over a network.

It is important to remember that some servers block ICMP traffic, so an unsuccessful ping does not always mean a service is unavailable.

Status: Week 1 — Completed ping connectivity exercise.
