This document specifies a cautious method for IETF transports that
enables fast startup of congestion control for a wide
range of connections.

It reuses a set of computed congestion control parameters that
are based on previously observed path characteristics between
the same pair of transport endpoints. These parameters
are stored, allowing them to be later used to modify the congestion control behavior
of a subsequent connection.
          
It describes assumptions and defines requirements for how a
sender utilizes these parameters to provide opportunities for a
connection to more rapidly get up to speed and rapidly utilize available
capacity. It discusses how use of the method impacts the capacity at a
shared network bottleneck and the safe response that is needed after any
indication that the new rate is inappropriate.
