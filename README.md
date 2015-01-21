# Packet routing - Dijkstra's shortest path-algorithm in PHP

Simple implementation that emulates packet travel in network, between routers with random connection weight changes. App firstly calculate shortest path and on each hop randomize connections and does recalculation.

- **Author: Zoran Antolovic, Croatia**
- Forked from: https://github.com/shivas/PHP-Dijkstra


# CLI command start
- `php main.php h2 p2` for basic SP calculation
- `php main.php h2 p2 --simulate` for basic SP calculation and packet routing simulation