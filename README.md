<!-- ===================== HERO 3D HEADER ===================== -->

<div align="center">

<h1 style="
font-size: 3rem;
font-weight: 800;
background: linear-gradient(90deg, #00DBDE, #FC00FF, #00DBDE);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
animation: glow 6s infinite linear;
">
SYSTEMS ENGINEER · FULL-STACK & AI INFRASTRUCTURE
</h1>

<p style="font-size: 1.1rem; opacity: 0.85;">
Designing scalable software systems, intelligent automation pipelines, and production-grade AI architectures.
</p>

<!-- Floating 3D badge -->
<div style="
display:inline-block;
padding:10px 18px;
margin-top:12px;
border-radius:12px;
background: rgba(255,255,255,0.05);
backdrop-filter: blur(10px);
box-shadow: 0 10px 30px rgba(0,0,0,0.4);
transform: perspective(800px) rotateX(10deg);
animation: float 4s ease-in-out infinite;
">
⚙️ High-Performance Systems · 🧠 AI Engineering · ☁️ Cloud Architecture
</div>

</div>

---

<!-- ===================== ANIMATIONS ===================== -->

<style>

@keyframes float {
  0% { transform: perspective(800px) translateY(0px) rotateX(10deg); }
  50% { transform: perspective(800px) translateY(-10px) rotateX(12deg); }
  100% { transform: perspective(800px) translateY(0px) rotateX(10deg); }
}

@keyframes glow {
  0% { filter: hue-rotate(0deg); }
  100% { filter: hue-rotate(360deg); }
}

.card {
  transition: transform 0.4s ease, box-shadow 0.4s ease;
  transform-style: preserve-3d;
}

.card:hover {
  transform: perspective(1000px) rotateX(8deg) rotateY(-8deg) scale(1.02);
  box-shadow: 0 25px 60px rgba(0,0,0,0.5);
}

.section-title {
  font-size: 1.3rem;
  font-weight: bold;
  margin-top: 30px;
  opacity: 0.9;
}

</style>

---

## 🧠 EXECUTIVE SUMMARY

<div class="card">

I am a Full-Stack & AI Engineer focused on building  
**high-throughput systems**, **LLM-powered applications**, and **distributed backend architectures**.

My work sits at the intersection of:
- Scalable backend engineering  
- Applied machine learning & LLM systems  
- Cloud-native architecture design  
- Performance-critical API development  

I prioritize **engineering rigor, observability, maintainability, and system resilience** over superficial feature delivery.

</div>

---

## ⚙️ CORE COMPETENCIES

<div class="card">

### SYSTEM DESIGN & BACKEND ARCHITECTURE
- Microservices & distributed systems design  
- Event-driven architecture (Kafka / queues)  
- High-performance REST & GraphQL APIs  
- Redis caching & low-latency optimization  
- Hybrid SQL + NoSQL systems  

### AI / MACHINE LEARNING ENGINEERING
- LLM integration (OpenAI / open-source models)  
- Retrieval-Augmented Generation (RAG) pipelines  
- Vector search & embedding systems  
- Multi-agent orchestration systems  
- AI workflow automation engines  

### FRONTEND ENGINEERING
- React / Next.js architecture  
- Performance optimization & hydration tuning  
- Scalable component systems  
- State management (Redux / Zustand)  

### CLOUD & DEVOPS
- Docker & Kubernetes fundamentals  
- CI/CD pipelines (GitHub Actions)  
- AWS architecture (Lambda, EC2, S3, RDS)  
- Observability-first system design  

</div>

---

## 🧬 ARCHITECTURE VISUALIZATION (CONCEPT)

<div align="center">

```mermaid
flowchart TD
A[Frontend Layer] --> B[API Gateway]
B --> C[Microservices Cluster]
C --> D[(Database Layer)]
C --> E[Event Queue / Kafka]
E --> F[AI / LLM Engine]
F --> G[Vector Database]
G --> F
F --> B
