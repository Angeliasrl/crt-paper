# CRT: Causal Resolution via Topology

**Deterministic Event Ordering Without Synchronous Consensus Rounds**

[![Demo](https://img.shields.io/badge/Demo-Live-green)](https://crt-certifications.org/execution-trace)
[![Paper](https://img.shields.io/badge/Paper-PDF-blue)](./crt_paper.pdf)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

---

## 📄 Abstract

CRT introduces deterministic causal ordering without synchronous consensus rounds, achieving **4,980 events/second** with mathematical guarantees unmatched by blockchain systems. By encoding causality explicitly in a DAG structure and applying deterministic topological sorting, CRT derives a unique, reproducible event ordering in **O(V + E)** time complexity—without leader election, voting rounds, or quorum requirements.

## 🎯 Key Results

- **Throughput:** 4,980 events/second
- **Latency:** 0.30ms P99
- **Complexity:** O(V + E) optimal
- **Security:** Post-quantum ready (Dilithium3)
- **Compliance:** EU AI Act Article 12 compliant

## 🚀 Live Demo

**AI Execution Trace Viewer:**  
https://crt-certifications.org/execution-trace

Try the interactive demonstration showing INTENT→EXECUTION→FINAL phases with cryptographic verification.

## 📊 Comparison

| System | Throughput | Ordering | Determinism | PQC |
|--------|-----------|----------|-------------|-----|
| Trillian | 500/s | Append | No | No |
| Fabric | 3,500/s | Consensus | No | No |
| **CRT** | **4,980/s** | **Topological** | **Yes** | **Yes** |

## 🏗️ Architecture

**Core Innovation:** Structure-derived ordering
- Causality encodes precedence
- Topology derives sequence
- No consensus rounds needed

**Three-phase certification:**
1. **INTENT** - User query, parameters
2. **EXECUTION** - Reasoning steps, model calls
3. **FINAL** - Output, confidence, proofs

## 📖 Paper

**Full paper:** [CRT_Paper.pdf](./crt_paper.pdf) - 15 pages

**Sections:**
- Mathematical foundations (Theorems 4.1-6.1)
- Post-quantum cryptography (Dilithium3)
- EU AI Act compliance implementation
- Performance evaluation
- Production deployment

## 📬 arXiv Status

**Seeking endorsement for cs.DC (Distributed, Parallel, and Cluster Computing)**

Endorsement code: `JOM7QS`

If you can endorse for cs.DC category, please contact: francesco.riva@angelia.cloud

## 💬 Citation
```bibtex
@article{riva2026crt,
  title={CRT: Causal Resolution via Topology for Deterministic Event 
         Ordering Without Synchronous Consensus Rounds},
  author={Riva, Francesco},
  year={2026},
  institution={Angelia srl SB},
  url={https://github.com/Angeliasrl/crt-paper}
}
```

## 📧 Contact

**Author:** Francesco Riva  
**Organization:** Angelia srl SB, Clusone (BG), Italy  
**Email:** francesco.riva@angelia.cloud  
**Website:** https://crt-certifications.org

## 📜 License

This work is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).

---

**Keywords:** causal ordering, deterministic systems, distributed certification, post-quantum cryptography, temporal integrity, eIDAS, AI Act
