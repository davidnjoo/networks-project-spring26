# RTT vs Speed of Light Analysis

## 1. Which city has the highest inefficiency ratio?

London has the highest inefficiency ratio (~3.75). This means the measured RTT is almost 4 times higher than the theoretical minimum based on the speed of light.

This is likely due to indirect routing paths across the Atlantic. Data does not travel in a straight line and must pass through multiple routers and submarine cables. Transatlantic cables such as MAREA or AC-1 connect North America to Europe, but routing decisions and congestion can increase latency significantly.

---

## 2. Which city is closest to the theoretical minimum?

Singapore has the lowest inefficiency ratio (~1.06), meaning it is very close to the theoretical limit.

This suggests that the network path is highly optimized, with efficient routing and minimal congestion. It may also benefit from modern infrastructure and high-quality submarine cable connections across Asia and the Pacific.

---

## 3. Why does Lagos often route through Europe first?

Lagos frequently shows inefficiency because many African internet routes are not directly connected to North America. Instead, traffic is often routed through Europe due to historical infrastructure development and limited direct transatlantic cables to West Africa.

Submarine cables like SAT-3 and WACS connect West Africa to Europe, so traffic may travel:
North America → Europe → Africa

This indirect path increases latency.

To improve this, more direct submarine cables between North America and West Africa would be needed, along with improved regional internet exchange points (IXPs) to reduce dependency on European routing.
