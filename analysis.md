# RTT vs Speed of Light Analysis

## 1. Which city has the highest inefficiency ratio?

London has the highest inefficiency ratio (~2.61), followed by Frankfurt (~2.40). This means the measured RTT is more than double the theoretical minimum.

This inefficiency is primarily due to transatlantic routing. Data from Boston to Europe travels through submarine fiber optic cables such as MAREA or AC-1, but not in a straight line. It also passes through multiple routers and exchange points, adding processing delays and congestion.

---

## 2. Which city is closest to the theoretical minimum?

Sydney has the lowest inefficiency ratio (~1.00), meaning its measured RTT is almost identical to the theoretical minimum. Singapore is also very close (~1.05).

This suggests that these routes are highly optimized, likely using modern, direct submarine cable infrastructure with minimal congestion and efficient routing paths.

---

## 3. Why are some cities unreachable?

Several cities such as Sendai, Seoul, New Delhi, Santiago, Johannesburg, Berlin, London (Imperial), and Canberra were unreachable.

This is likely because many university websites block automated HTTP requests or do not respond reliably to repeated probing. Some servers may also restrict access based on geographic region or rate-limit incoming requests.

Even though RTT could not be measured, the theoretical distances were still computed correctly.

---

## 4. Why is real RTT higher than the speed-of-light limit?

Real-world RTT is higher than the theoretical minimum because:
- Fiber paths are not straight lines (they follow cable routes)
- Data passes through multiple routers and switches
- Network congestion adds delay
- TCP/HTTP overhead introduces additional latency
- Undersea cables may take indirect routes between continents

---

## 5. Observations

- European cities (London, Frankfurt) show higher inefficiency due to transatlantic routing.
- African and Asian cities (Lagos, Mumbai) show moderate inefficiency.
- Long-distance routes (Sydney, Singapore) can still be efficient if routing is optimized.
- Unreachable hosts highlight real-world measurement limitations when using HTTP-based probing.