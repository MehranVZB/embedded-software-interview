# **Fundamentals & Basic Concepts**
## **Questions**
1. What is an embedded system?  
2. What are its essential components (MCU, memory, I/O, etc.)?  
3. Microcontroller vs. microprocessor — explain differences.  
4. Define RTOS and its benefits.  
5. Hard vs soft real‑time systems.  
6. What is a semaphore? Mutex? Differences?  
7. Explain priority inversion, priority inheritance, priority ceiling.  
8. What is an interrupt? How are ISRs handled?  
9. Explain volatile keyword in C. Significance in ISRs.  
10. Static vs global vs local variables in C.  
11. Explain memory-mapped I/O.  
12. Define DMA and its trade-offs.  
13. Compare UART, SPI, I²C, CAN protocols.  
14. Explain pull-up/pull-down resistors on I²C.  
15. Explain ADC and DAC operation.  
16. What is endianness? Big vs little in data exchange.  
17. Use cases for fixed-point vs floating-point math.  
18. What is RISC architecture?  
19. Von Neumann vs Harvard architecture. Pros/cons.  
20. What is cache? Cache coherence, associativity basics.  
21. What is MMU and which architectures use it?
## **Answers**
1. ???  
2. ???

# **Embedded C & Algorithms**
## **Questions**
1. Write ISR skeleton in C.  
2. Explain reentrant functions; when avoid non‑reentrant functions.  
3. When to use memcpy vs memmove?  
4. Implement memset, memcpy in C.  
5. Reverse bits of an integer.  
6. Count set bits in a binary stream.  
7. Implement CLZ (count leading zeros) without built‑in instruction.  
8. Swap nibble high bits in a byte.  
9. Detect endianness at runtime.  
10. Reverse digits of an integer.  
11. Draw patterns (triangle, diamond, X, Z with '\*').  
12. Compute GCD of 3 numbers.  
13. Palindrome test for integer.  
14. Linear search vs binary search differences.  
15. Stack, linked list, queue implementation in C.  
16. Circular buffer design and applications.  
17. Memory pool allocator without malloc/free.  
18. Aligned malloc implementation wrapper.  
19. When to malloc large blocks? Alternatives when malloc unavailable.  
20. Caller-provider function application over array.  
21. Determine stack growth direction.  
22. Optimize arithmetic e.g. multiply 256-bit numbers on 32-bit CPU.  
23. Maximum of two numbers without branches.  
24. Implement fast integer square root.  
25. Date calculation logic (leap-year aware).  
26. Longest subarray with ≤2 distinct ints.  
27. Bitstream pattern search with offset.
## **Answers**
1. ???

# **RTOS & Concurrency**
## **Questions**
1. FreeRTOS task implementation in C.  
2. Preemptive vs non‑preemptive kernels.  
3. CPU load measurement in RTOS.  
4. Intertask communication: message queues, mailboxes, event flags.  
5. Explain spinlocks and test‑and‑set operations.  
6. Race condition example and detection.  
7. Thread states in RTOS.  
8. Priority inversion example resolution.  
9. Event-driven systems vs shared concurrency systems.  
10. Scheduler latency, jitter, deadlines in RTOS systems.  
11. RTOS metrics: context switch time, tick overhead.  
12. Deadlock, livelock definitions and avoidance.  
13. Implement priority inheritance in RTOS.  
14. Design RTOS for power-saving systems.
## **Answers**
1. ???  
2. 

# **Debugging & Toolchains**
## **Questions**
1. Explain bootloader stages and their roles.  
2. Bootloader design trade‑offs: eMMC vs SD, secure boot.  
3. Secure boot, encrypted firmware, TrustZone.  
4. Toolchains: GCC, Keil, IAR, optimization flags.  
5. Compiler flags for size vs speed.  
6. What is linker script? Sections (.text/.data/.bss).  
7. Use of JTAG, logic analyzers, oscilloscopes.  
8. Debugging “system goes blank”: hardware check, logs.  
9. Diagnosing intermittent failures: logic analyzer approach.  
10. Diagnosing software vs hardware causes post‑update bug.  
11. Firmware update mechanisms: OTA, secure updates.  
12. Version control: Git/SVN/Jenkins.  
13. Ensuring live debugging doesn’t affect functionality.  
14. QA/testing tools like Unity, Google Test.  
15. Code coverage and static analysis.
## **Answers**
1. ???
2.

# **Hardware‑Software Co‑design & Interfaces**
## **Questions**
1. Explain hardware–software co‑design.
2. MCU bus structures: AMBA/AHB etc.
3. CPU <→ RAM/Flash/peripheral interfacing.
4. How SAR ADC works.
5. Signal integrity: rise time, reflection, termination.
6. Timer/counter peripherals and usage.
7. Watchdog hardware vs software.
8. Power design: regulators, decoupling.
9. Using DMA for performance/power saving.
10. SPI/I²C failure modes (mis‑config, no pull‑ups).
11. CAN bus specifics: collision handling.
12. Automotive protocols: CAN vs LIN speeds/applications.
13. Sensor interfacing: I²S, ARINC 429, FlexRay.
14. AUTOSAR and SWC/RTE.
15. Functional safety: ISO 26263 overview.
## **Answers**
1. ???

# **Software Architecture & Design Patterns**
## **Questions**
1. Component‑based vs object‑oriented design.
2. Design patterns used in embedded (state machine, singleton).
3. Modularization and HAL (hardware abstraction layer).
4. Portability strategies across platforms.
5. Memory optimization techniques.
6. I/O optimization techniques.
7. Trade‑offs: speed vs power vs memory.
8. Design of finite state machines in firmware.
9. Interrupt-heavy vs polling-based design.
10. Use of atomic operations.
11. Static vs dynamic allocation trade-offs.
## **Answers**
1. ???  
2. 

# **System Design Scenarios**
## **Questions**
1. Design a traffic-light controller state machine.  
2. Design smart garden watering device with zones/IoT.  
3. Design telemetry service from host to device.  
4. Design UART device driver interface.  
5. Microkernel system that loads a file and executes.  
6. Design async protocol for host‑device transfers.  
7. Embed C firmware for engine controller with timing constraints.  
8. Battery-powered device power management (sleep/wake).  
9. Bootloader stages from ROM → RAM → app.  
10. Secure firmware loader with rollback protection.  
11. Multi‑processor system synchronization strategy.  
12. Data throughput optimization over serial links.  
13. Designing device with DMA and zero‑copy buffer handling.  
14. Live update of firmware over unreliable link.  
15. OTA firmware update with rollback support.  
16. Secure OTA pipeline design.  
17. Real‑time scheduling under heavy interrupt load.  
18. Resource constraint negotiation (memory/power/time).  
19. Designing a sensor network using I²C/SPI and RTOS.  
20. Add encryption/authentication to embedded comms.  
## **Answers**
1. ???
2.

# **Optimization, Power & Reliability**
## **Questions**
1. Dynamic voltage and frequency scaling.  
2. Power gating and clock gating.  
3. Low‑power sleep modes on MCU.  
4. Energy profiling tools and strategies.  
5. Reducing fragmentation in embedded heap.  
6. Secure boot vs non‑secure boot pros/cons.  
7. Firmware rollback and fail-safe design.  
8. Fault‑tolerance and redundancy for mission‑critical systems.  
9. Error detection codes (CRC, parity).  
10. Watchdog reset strategies on failure.  
11. Defensive programming in safety‑critical contexts.  
12. Code review strategy for embedded safety.  
13. Static/dynamic testing in constrained systems.
## **Answers**
1. ???
2.

# **Behavioral & Problem‑Solving**
## **Questions**
1. Discuss a bug you encountered and how you resolved it.  
2. How do you stay current with embedded trends?  
3. Example of working cross‑discipline with hardware engineers.  
4. Explain a time you prioritized under tight deadlines.  
5. Communicating design to non‑technical stakeholders.  
6. Handling conflicting requirements in design.  
7. Working with QA to ensure reliability.  
8. Documenting system architecture and APIs.  
9. Mentoring junior engineers.  
10. Scaling embedded team processes.  
11. Dealing with legacy firmware and updates.  
12. Risk assessment for embedded release.  
## **Answers**
1. ???
2.

