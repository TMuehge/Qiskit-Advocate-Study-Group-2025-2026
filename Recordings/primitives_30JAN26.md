Link to the recording:
https://teams.microsoft.com/l/meetingrecap?driveId=b%21-8Th9JRvJkW5nCDSubo9G7umiDa77zxOiIvUQQRLhGh9Xqz4fXvgRo2K9PArSNtm&driveItemId=01XSTDWN43YWIAZUECCRFKL3YTNVDXSAQD&sitePath=https%3A%2F%2Fibm-my.sharepoint.com%2F%3Av%3A%2Fp%2Fmuehge_de%2FIQCbxZAM0IIUSqXvE21HeQIDAfpI5o3ApCCM7PKg6LKYd24&fileUrl=https%3A%2F%2Fibm-my.sharepoint.com%2Fpersonal%2Fmuehge_de_ibm_com%2FDocuments%2FRecordings%2FQiskit%2520Advocate%2520Study%2520Group%25202025%2520%25202026-20260130_143518-Meeting%2520Recording.mp4%3Fweb%3D1&iCalUid=040000008200E00074C5B7101A82E00807EA0110C61F32F9F565DC01000000000000000010000000FE743BA1C105874BAFDCF801C1EE3B1A&masterICalUid=040000008200E00074C5B7101A82E00800000000C61F32F9F565DC01000000000000000010000000FE743BA1C105874BAFDCF801C1EE3B1A&threadId=19%3Ameeting_ZmI4MDAxOWEtYzAwNS00NzdiLWEzYWItZGUyYmM5ZjRmMDFj%40thread.v2&organizerId=9f5ef063-9507-4a55-8329-1c3bded492cd&tenantId=fcf67057-50c9-4ad4-98f3-ffca64add9e9&callId=19890d42-0103-492d-8162-78c747618561&threadType=Meeting&meetingType=Recurring&subType=RecapSharingLink_RecapCore

## Session topic: Running quantum circuits on real hardware using Qiskit primitives.
### Overall quantum workflow

General steps for solving problems on a quantum computer:

Map a real‑world problem to a quantum circuit.
Optimize the circuit for target hardware (transpilation).
Execute on quantum hardware or simulator.
Post‑process and interpret probabilistic results.

### Qiskit Primitives

Introduction of IBM Qiskit primitives:

Estimator: computes expectation values of observables.
Sampler: returns measurement bitstrings and their probabilities.

Explanation of when and why each primitive is used.

### Execution modes

Overview of Qiskit job execution modes:

Single job
Batch
Session mode (important for variational/optimization algorithms, but not available in the free Open Plan on real hardware).

### Hands-on examples

Demonstration of executing circuits on IBM quantum backends (or simulators when sessions are required).
Use of QAOA (Quantum Approximate Optimization Algorithm) as an illustrative algorithm.

### Certification-oriented discussion

Walkthrough of exam-style questions related to:

Primitives
Sampler and estimator options
Shots, precision, and error mitigation
Session usage and runtime APIs

### Realistic use case

End-to-end example: Max-Cut optimization problem

Explanation of the problem and its real-world relevance (e.g., scheduling, chip design, supply chain optimization).
Comparison of classical brute-force vs. quantum approaches.
Mapping the problem to a quantum formulation.
Optimization via QAOA using estimator → solution extraction using sampler.
Interpretation of probabilistic outputs.
