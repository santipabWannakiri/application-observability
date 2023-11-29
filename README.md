# application-observability
## Introduction
As I've been tasked with exploring solutions for application observability, I've invested time in researching the concept and conducting several POC. I aim to document all the insights gained during this process, with the hope that it proves beneficial to others.

## Observability
<p align="center">
  <img src="images/observability.png" alt="image description" width="450" height="250">
</p>

In the realm of observability theory, three fundamental components exist: `Logging`, `Metrics`, and `Tracing`, collectively known as the `Three Pillars of Observability`. An application that incorporates all three pillars empowers us to comprehensively assess the health of our system. This holistic approach enables us to anticipate and safeguard against potential issues in the future. Moreover, in the event of an issue, it facilitates efficient investigation and swift resolution of problems.

The reason that we need to gather 3 components, because each one it can only provide to some aspect of applicationIn for example if we keep only logging, It quite good for debug or investigate per txn. but still lack of overview of system. Moreover, each components also require tools or framework in difference to gather info from application as well. So I'm going to describe in detail in next section below.

## Logging 
