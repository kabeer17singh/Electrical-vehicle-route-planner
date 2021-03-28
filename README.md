# Electrical-vehicle-route-planner
# Problem description
Consider a city network where we need to route a set of electric vehicles
which may require to be charged during its journey from some source to some destination. Let
us assume that we have n cities (v1, v2, . . . , vn) and the distance between cities vi and vj be
eij (if two cities are not connected directly then eij = ∞ and eij = eji). Assume that each city
has a single charging station which can charge one EV at a time. Consider a set of k EVs namely
P1, P2, . . . , Pk. For each EV the following information is provided -
(a) Sr - source node
(b) Dr - destination node
(c) Br - battery charge status initially
(d) cr - charging rate for battery at a charging station (energy per unit time)
(e) dr - discharging rate of battery while traveling (distance travel per unit charge)
(f) Mr - maximum battery capacity
(g) sr - average traveling speed (distance per unit time).

# Implementation Details
Our E-VRPTW Solver consists of two parts:
Construction heuristic
Metaheuristic


