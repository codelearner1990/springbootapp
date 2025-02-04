Toxic Type	Purpose	Real-World Use Case
Limiter	Limits the total amount of data allowed through a proxy connection.	Simulate rate limiting (e.g., API throttling).
Slicer	Cuts the stream into smaller chunks, making it erratic and fragmented.	Test how a system handles incomplete or fragmented responses.
Bandwidth (Degradation)	Limits the network speed to a specified rate in KB/s.	Simulate low network bandwidth (e.g., slow internet).
Slow Connection	Simulates a slow handshake before sending data.	Mimic slow initial connections (e.g., slow TLS handshake).
Timeout	Drops connections if they exceed a specified time limit.	Test timeouts and retries in APIs.
Latency	Delays packets by a specific time (ms) before forwarding them.	Simulate high network latency (e.g., slow API responses).
