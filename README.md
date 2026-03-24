<div align="center">

```
┌──────────────────────────────────────────────────────────────────┐
│  omer@smartalpha:~$ whoami                                       │
│  > Senior ML Engineer · Computer Vision · Generative AI          │
└──────────────────────────────────────────────────────────────────┘
```

</div>

---

```
omer@smartalpha:~$ cat about.txt

I got into ML because real-time computer vision is a genuinely hard problem;
tight latency budgets, noisy inputs, and a model that has to be right while
running on constrained hardware. That kind of constraint is where things get
interesting. Five years in, the problems haven't gotten easier, and that makes
it much more interesting.

I sit somewhere between researcher and engineer depending on the week. Some
weeks it's running ablations. Others it's making sure a distributed
pipeline doesn't silently corrupt your dataset at scale. I've stopped trying
to pick a lane, both matter, and the overlap is where the interesting work
lives. The domain shifts, the craft doesn't.

I actively use AI tooling and think seriously about what it actually changes
for engineers (not the hype, the real shift). The ceiling moved up. You're
still responsible for the system, the decisions, the failure modes. But the
floor of what one person can build and maintain has risen significantly.
Engineers who get that are operating in a different league.

You can't ignore it. Embrace and adapt.
```

---

```
omer@smartalpha:~$ ls shipped/

shipped/
│
├── Nerveblox®  ─────────────────────────────────────────────────────
│   ├── Real-time ultrasound guidance system (FDA 510(k) + MDR cleared)
│   ├── Integrated into GE Healthcare Venue & Siemens Healthineers
│   ├── CNN-based anatomical structure detection & segmentation
│   └── CPU edge inference: ~120ms init · ~9 FPS on Intel Core i3
│
└── Patent  ──────────────────────────────────────────────────────────
    ├── TR 2022-GE-975452 (Issued Dec 2022)
    └── Adaptive annotation stabilization for DL-based medical imaging
        └── Temporal + motion-aware annotation adaptation in ultrasound
```

---

```
omer@smartalpha:~$ ls research/

research/
│
├── Generative Modeling  ─────────────────────────────────────────────
│   ├── Latent diffusion framework for pathological variation synthesis
│   ├── VQ-VAE + Transformer encoder → structured latent codebook
│   ├── Class-conditioned diffusion for targeted pathology generation
│   ├── Framed as structured inpainting (localized, anatomy-preserving)
│   └── Distributed training: multi-cluster · DDP · mixed precision
│
├── Vision–Language & Data  ──────────────────────────────────────────
│   ├── Multimodal platform for visual reasoning & action planning
│   ├── ~25,000 hours of video → ~1.7B tokens (dedup'd, QA-validated)
│   ├── Airflow on GKE: vendor ingest → GCS staging → post-processing
│   ├── OpenTelemetry → Loki → Grafana: zero manual intervention
│   └── DVC-based reproducible dataset versioning + OpenLineage
│
└── Representation Learning  ─────────────────────────────────────────
    ├── DenseCL-style contrastive pretraining on video
    ├── MobileNetV4-Small encoders with spatial feature alignment
    └── Multi-task segmentation/classification (uncertainty + GradNorm)
```

---

```json
// omer@smartalpha:~$ cat stack.json
{
  "languages":       ["Python", "C++", "SQL", "MATLAB", "Rust (incoming)"],
  "ml_core":         ["PyTorch", "PyTorch Lightning", "TensorFlow", "Diffusers", "ONNX", "TensorRT"],
  "specializations": ["Latent Diffusion", "VQ-VAE", "Real-time CNNs", "Model Quantization & Pruning",
                      "Distributed Training (DDP + mixed precision)", "Edge Inference"],
  "data":            ["Large-scale dataset construction", "DVC", "OpenLineage", "500k+ labeled images"],
  "cloud":           ["GCP", "GKE Autopilot", "GCS", "Cloud SQL", "Docker", "Kubernetes", "Helm"],
  "observability":   ["OpenTelemetry", "Grafana", "Loki", "Airflow", "RBAC", "Audit Logging"],
  "systems":         ["Linux", "shell scripting", "git", "PostgreSQL"]
}
```

---

```
omer@smartalpha:~$ tail -n 5 active.log

[ACTIVE]   CNN+Transformer hybrid for temporal stability in tiny model inference
[ACTIVE]   CLI tooling for large-scale dataset versioning and lifecycle management
[ONGOING]  Keeping small encoders consistent across distribution shifts
```

---

```
omer@smartalpha:~$ cat links.txt

  linkedin  →  linkedin.com/in/omerfsarioglu
  company   →  smartalpha.ai
```

---

<div align="center">
<sub>

```
omer@smartalpha:~$ echo "systems that learn · models that ship · experiments that mean something" █
```

</sub>
</div>
