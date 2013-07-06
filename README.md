# Perfect Spot
The idea behind this library is to allow for optimization of AWS Spot Requests.

## Motivation
Spot requests are a great way to reduce costs for processing that does not need to be guaranteed.
Examples include EMR jobs, one off provisioned EC2 instances.

Unfortunately, bidding on Spot Requests is far from optimized. There are many different instance types and EC2 regions where competition and volatility is not consistent so you may have `m1.large` beind more expensive than `c1.xlarge`.

In other words, it is a imperfect marketplace of computing commodity.

The idea behind this package is to do a quick analysis of volatility and pricing between different instance types and regions and report the best instance and price to bid on at this particular point of time.

## Different ways to access

### REST API

### Command line

### Using a library


