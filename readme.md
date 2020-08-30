# Multithreading Simulation with Go-lang
The code simulates birds flock flying in a cluster using ebiten library

Some features:
- Every bird starts with a random position and a random velocity
- Each bird point is implemented as a seperate thread (goroutine)
- Thread interacts with each others through memory sharing
- Readers writer lock is implemented to prevent overlapping

