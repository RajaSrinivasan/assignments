# Clarks Tables

## Background

Decades ago, before the days of computers, calculators the [Clarks Tables](https://www.scribd.com/doc/36294170/Clarks-table)
was an essential for any science student. You looked up logarithms, trigonometric functions
and the like to an impressive level of precision.

For example, you could lookup the Sin of 45 degrees 31 minutes just as easily as the
natural logarithm of arguments of 5 decimal digits. [Angles](https://www2.clarku.edu/faculty/djoyce/trig/angle.html#:~:text=Each%20degree%20is%20divided%20into,2°%205%27%2030%22.) measured in degrees or radians may turn up equally in an exam.

## Example

[example implementation](https://gitlab.com/ada23/adagsl) has an Ada implementation for Sines. Others should be very similar

A section of the Sin table looks like:
```
10.0    |  0.1736  0.1754  0.1771  0.1788  0.1805  0.1822  0.1840  0.1857  0.1874  0.1891  |  3  6  9 11 14 
11.0    |  0.1908  0.1925  0.1942  0.1959  0.1977  0.1994  0.2011  0.2028  0.2045  0.2062  |  3  6  9 11 14 
12.0    |  0.2079  0.2096  0.2113  0.2130  0.2147  0.2164  0.2181  0.2198  0.2215  0.2233  |  3  6  9 11 14 
13.0    |  0.2250  0.2267  0.2284  0.2300  0.2317  0.2334  0.2351  0.2368  0.2385  0.2402  |  3  6  8 11 14 
14.0    |  0.2419  0.2436  0.2453  0.2470  0.2487  0.2504  0.2521  0.2538  0.2554  0.2571  |  3  6  8 11 14 
15.0    |  0.2588  0.2605  0.2622  0.2639  0.2656  0.2672  0.2689  0.2706  0.2723  0.2740  |  3  6  8 11 14 
```
## Projectlet

The goal of this projectlet is to generate the table of a trigonometric function such as Sine for angles of 0 to 360 to enable lookup with a granularity of minutes.

A stretch goal might be to go to a granularity of seconds.

### Learning objectives

The primary learning objective is to utilize/explore the predefined language environment available for computation of trigonometic functions.

Producing reports without the aid of any markup or word processing - still readable and comprehensible. 

If you attempt a solution (in a language of your choice) and would like to offer your solution as a reference, create a PR for this file.

