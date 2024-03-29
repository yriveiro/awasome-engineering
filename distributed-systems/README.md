# Distributed Systems

## On Designing and DeployingInternet-Scale Services

* Paper: [On Designing and DeployingInternet-Scale Services](https://www.usenix.org/legacy/events/lisa07/tech/full_papers/hamilton/hamilton.pdf)
* Authors: James Hamilton

### Abstract

The system-to-administrator ratio is commonly used as a rough metric to understand
adminis-trative costs in high-scale services. With smaller, less automated services
this ratio can be as low as2:1, whereas on industry leading, highly automated
services, we’ve seen ratios as high as 2,500:1. With in Microsoft services,
Autopilot<sup>1</sup> is often cited as the magic behind the success of the Win-dows
Live Search team in achieving high system-to-administrator ratios. While
auto-administrationis important, the most important factor is actually the service
itself. Is the service efficient to auto-mate? Is it what we refer to more generally
as operations-friendly? Services that are operations-friendly require little
human intervention, and both detect and recover from all but the most obscurefailures
without administrative intervention. This paper summarizes the best practices
accumulatedover many years in scaling some of the largest services at MSN and
Windows Live.

### References

1 - Isard, Michael, "Autopilot: Automatic Data CenterOperation", Operating Systems Review, April,2007, http://research.microsoft.com/users/misard/papers/osr2007.pdf.

## Distributed Systems - A free online class

* Link: [Distributed Systems](https://www.distributedsystemscourse.com/)
* Authors: Chris Colohan

### Abstract

This is an introductory course in Distributed Systems. Distributed systems is
the study of how to build a computer system where the state of the program is
divided over more than one machine (or "node").

This course is in active development. At the moment, it consists of a series
of short videos. The intention is to create a complete set of video lectures
and then add additional content (such as more projects). Sadly progress is
slow due to my other commitments getting in the way...
