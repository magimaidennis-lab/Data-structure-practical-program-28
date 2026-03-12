# Data-structure-practical-program-28
import heapq

pq = []

heapq.heappush(pq, 30)
heapq.heappush(pq, 10)
heapq.heappush(pq, 20)

print("Priority Queue:", pq)

print("Removed element:", heapq.heappop(pq))
print("Priority Queue after deletion:", pq)
Priority Queue: [10, 30, 20]
Removed element: 10
Priority Queue after deletion: [20, 30]
