+++
[info]
title = "Rust"
subtitle = "Why is Rust so Popular?"
author = "Atharva"
category = "Elitism"

[data]
layout = "blogpost_layout"

[globals]
ssg = "Misato"
+++

One of Rust’s best features is zero-cost abstractions, meaning you don’t have to pay for features you don’t use, so whether you use abstractions or go the “manual” implementation, costs around speed, memory consumption, etc., is the same.

With zero-cost abstractions, compile time memory checks, and garbage collections, Rust doesn’t check and collect memory at runtime but tracks the lifetime of code at compile time. This means it doesn’t matter if you use loops or closures — they all compile down to the same assembly.

For software engineers, many issues around systems programming are memory errors. Their goal is to design a project with quality code management, readability, and quality performance at runtime.

To accomplish this, engineers try to limit code optimizations and memory overhead, which pushes indirect memory access that can cause performance at runtime. Rust solves this with zero-cost abstractions.