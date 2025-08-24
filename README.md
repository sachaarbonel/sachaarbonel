# Hi, I'm Sacha 👋

[Twitter](https://twitter.com/sachaarbonel) • [LinkedIn](https://www.linkedin.com/in/sacha-arbonel/) • [GitHub](https://github.com/sachaarbonel) • [Medium](https://medium.com/@sachaarbonel) • [Email](mailto:sacha.arbonel@hotmail.fr)

I’m a Software Engineer with **7+ years** in backend and mobile. I’ve shipped systems that reached **over a billion users** and ran services that process **millions of messages a day**. I care about open source, clear design, and reliable scale.

---

## What I work on
- Pion/WebRTC–based media I/O library used by other services (egress/ingestion for transcription & recording; ingress for **HLS**, **WHIP**, **SRT**).
- Whisper infrastructure: language **hot-reload config** (no restart), **Prometheus**/**CloudWatch** metrics, **Grafana** dashboards, rollout speed-ups with **Packer-baked AMIs**, and **CloudFormation** maintenance.
- VAD with **Silero** via **ONNX Runtime (Go)** to enable **real-time captions** (no VAD → no live captions) and reduce waste.
- Accuracy work: built a hallucination dataset (transcribed a noise corpus) + **Aho-Corasick** matcher in Go, with **deloops** and **Unicode range filters** to remove hallucinations; important for most customers and critical for **healthcare**.
- Codegen & SDKs: internal **OpenAPI → server-side SDK** tooling; owner of the **Python** and **Go** SDKs (**35k+ LOC** each).
- Product support: outages on rotation, post-mortems, indexes for big imports, quick fixes across chat and dashboard (picked up **Django** fast when needed).

## Highlights
- p95 live transcription/closed captions: **~650 ms → ~300 ms**.  
- Cost: **~36× cheaper** than OpenAI 4o transcribe for our load.  
- Rollouts: **~11 min → ~1 min** with Packer AMIs + trimmed Puppet.  
- One service for transcription **and** captions → **~50% infra/ops reduction**.  
- Proved **CPU wasn’t the bottleneck**; eased GPU concurrency with **NVIDIA MPS**.  
- Quality: sales team **dogfoods** our app as a Gong replacement.  

## Tech
Go • Rust • Python • C++/CUDA • Whisper • ONNX Runtime • Pion/WebRTC • HLS • WHIP • SRT • AWS • CloudFormation (maintenance) • CloudWatch • Prometheus • Grafana • Packer/AMIs • Puppet • Logs Insights • Nsight • NVIDIA MPS • OpenAPI • Aho-Corasick

## Writing
- Medium: https://medium.com/@sachaarbonel

## Contact
- Issues welcome: https://github.com/sachaarbonel/sachaarbonel/issues
- Email: sacha.arbonel@hotmail.fr

---

![Sacha's GitHub stats](https://github-readme-stats.vercel.app/api?username=sachaarbonel&show_icons=true&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)
