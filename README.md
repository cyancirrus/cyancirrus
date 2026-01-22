Hi, I’m Raven (Autumn / Raven Echo)

🌿 blog: https://cyancirrus.github.io/autumn_leaves.io/

My current focus is robotics and autonomous navigation. I’m working toward a fully embodied system — perception, planning, and control — with the concrete goal of getting a robot to reliably navigate my apartment.

To support that, I’m rebuilding the computational stack bottom-up in Rust, with an emphasis on algorithms, numerics, and real-time systems rather than black-box abstractions.

Areas I’m actively working in:
- Path planning and online replanning (A*, D*, quadtree-compressed search)
- Closed-loop control and state estimation (PPA loops, EKF, stabilization)
- Numerical linear algebra and scientific computing
- Low-level systems work: Rust, C, async execution, memory layout, and FFI
- GPU acceleration experiments (CUDA + Rust)

A large part of this effort lives in a from-scratch Rust math and compute ecosystem:
- `stellar-math` — custom linear algebra, decompositions, FFTs, solvers, and filtering
- Learning and optimization methods built directly on top of these primitives
- Experiments bridging numerics, learning, and control

I’m also deliberately rebuilding algorithmic fundamentals — especially graph search and dynamic programming — through focused problem solving in [`algo`](https://github.com/cyancirrus/algo/tree/main/solutions), as preparation for real-time planning and control systems.

🛠 Selected projects:
- **sabrina** — Robotics and navigation experiments (planning, control, autonomy)
- **stellar-math** — Numerical linear algebra, solvers, FFTs, and control primitives
- **neural-net** — From-scratch neural networks in Rust
- **algo** — Algorithmic fundamentals (graphs, DP, search)
- **lru-cache** — Unsafe Rust and memory management experiments

All of this work is aimed at building expressive, transparent tools for scientific computing and autonomous systems — and at understanding how algorithms behave when they’re embedded in real, time-dependent loops.

Always happy to talk about robotics, planning, numerics, Rust’s borrow checker, async systems, or low-level performance.

Discord: magenta#2449  
If I’m slow to reply, I’m probably mid-problem 😅
