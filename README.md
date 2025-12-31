# Hybrid-Swarm

An AI coordination system implementing **stigmergic architecture** for parallel multi-specialist execution. Harness the power of emergent intelligence where AI specialists coordinate indirectly through environmental signals (like ant pheromone trails), enabling parallel task resolution with adaptive resonance and quality-based selection.

## 🚀 Quick Start

Choose your preferred deployment method:

### Option 1: Portable Windows Executable (Recommended for beginners)
Download the latest release from the **[Releases](https://github.com/MushroomFleet/Hybrid-Swarm-Local/releases)** section

- 💻 **Portable exe** - no installation required, just download and run
- ✨ **Only requires OpenRouter.ai API key** - no complex setup needed
- 🎓 **Interactive tutorials** introducing both Classic Swarm and RIP Swarm modes
- 🔥 **Full-featured experience** with both processing modes available

### Option 2: Online Platform
Visit **[https://hybrid-swarm.oragenai.com](https://hybrid-swarm.oragenai.com)**

- ✨ **Only requires OpenRouter.ai API key** - no local installation needed
- 🎓 **Interactive tutorials** for learning both processing modes
- 🔥 **Full-featured experience** with guided experimentation

### Option 3: Local Development

For developers who want to contribute, customize, or run locally:

#### Prerequisites
- **Node.js** (v18+) - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- **OpenRouter.ai API key** for LLM access

#### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MushroomFleet/Hybrid-Swarm-Local/
   cd swarm-forge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Handle Windows native dependencies** (npm optional dependencies bug)
   ```bash
   # Required on Windows - these fix npm's optional dependency installation issues
   npm install @rollup/rollup-win32-x64-msvc
   npm install @swc/core-win32-x64-msvc
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser** to `http://localhost:8080`

6. **Configure API key** in Settings → API Configuration

#### Build for Production
```bash
npm run build
npm run preview
```

## ⚡ RIP Swarm: Advanced Cognitive Processing

Hybrid-Swarm now features the **Recursive Intelligence Protocol (RIP)**, an advanced processing mode built on the **3DKF-RHA framework** (3-Dimensional Knowledge Framework with Recursive Hyperstition Architecture). RIP adds a 7-stage cognitive preprocessing pipeline that runs before the Classic Swarm orchestration.

### The 3DKF-RHA Framework

RIP categorizes knowledge across three dimensions, creating 8 distinct knowledge categories:

#### The 3 Dimensions
1. **Known (K) vs Unknown (U)** - Is the information currently known?
2. **Knowable (K) vs Unknowable (U)** - Can it be discovered or understood?
3. **Acknowledged (K) vs Unacknowledged (U)** - Is it recognized or hidden?

#### The 8 Knowledge Categories
- **KKK** (Known-Knowable-Known) - Verified facts: "Water boils at 100°C"
- **UKK** (Unknown-Knowable-Known) - Discoverable: "Population of a city"
- **KKU** (Known-Knowable-Unknown) - Partial knowledge: "Bug exists, location unknown"
- **UKU** (Unknown-Knowable-Unknown) - Future possibilities: "New technologies"
- **KUK** (Known-Unknowable-Known) - Accepted mysteries: "Nature of consciousness"
- **UUK** (Unknown-Unknowable-Known) - Paradoxes: "Omnipotence paradox"
- **KUU** (Known-Unknowable-Unknown) - Deep mysteries: "What is nothing?"
- **UUU** (Unknown-Unknowable-Unknown) - Unknown unknowns

### The 7-Stage Cognitive Pipeline

1. **State Assessment** - Profile cognitive state, detect biases and clarity levels
2. **Knowledge Mapping** - Categorize content into 8 knowledge dimensions  
3. **Recursive Expansion** - Iteratively deepen understanding through multiple passes
4. **Pattern Evolution** - Identify and connect primary and emergent patterns
5. **Stability Anchoring** - Ensure coherent output through cognitive anchors
6. **Integration Synthesis** - Combine all elements into unified understanding
7. **Lucidity Verification** - Final quality check and certification

### Cognitive States

RIP tracks processing through three cognitive states:
- 🔘 **Dark Inertia** (Gray) - Reactive, surface-level processing
- 🟠 **Passion** (Orange) - Engaged but potentially biased
- 🟢 **Lucidity** (Green) - Clear, balanced, recursive awareness (optimal state)

### When to Use RIP vs Classic

**Use RIP Swarm for:**
- Complex analysis and research tasks
- Creative and exploratory queries
- When depth and quality are paramount
- Nuanced topics requiring careful examination

**Use Classic Swarm for:**
- Quick answers and direct questions
- Coding and debugging tasks
- Straightforward requests
- When speed is more important than depth

> 📖 **Learn More:** Access the comprehensive RIP tutorial within the app (Tutorial → RIP Swarm) for detailed explanations of each stage, the knowledge matrix, and configuration options.

## 🧠 How It Works

### Stigmergic Coordination
Unlike traditional AI orchestration that uses direct communication or central control, Hybrid-Swarm employs **stigmergy** - indirect coordination through environmental signals. AI specialists modify their shared environment (signal boundaries) which influences other specialists' behavior, creating emergent coordination patterns similar to ant colonies building complex structures through pheromone trails.

### Processing Modes

Hybrid-Swarm offers two complementary processing modes:

#### Classic Swarm (3-Layer Orchestration)
- **Adaptive Resonance Layer:** Selects top N specialists most resonant with your task
- **Stigmergic Signals:** Each specialist independently chooses approaches based on environmental signals
- **Parallel Execution:** All selected specialists execute simultaneously for maximum efficiency
- **Quality Voting:** Best response selected based on content quality scores
- **Distributed Learning:** All results contribute to system evolution

#### RIP Swarm (7-Stage + 3-Layer)
- **Cognitive Preprocessing:** 7-stage pipeline before Classic Swarm orchestration
- **Knowledge Mapping:** 3DKF categorization of all prompt content
- **Recursive Refinement:** Iterative deepening until convergence or max depth
- **Pattern Discovery:** Emergent insight extraction from recursive analysis
- **Lucidity Verification:** Multi-point quality checks before final output
- **State Tracking:** Monitors cognitive state progression toward lucidity

## 🔧 Features

### Classic Swarm Features
- ⚡ **Parallel Execution:** Execute multiple AI specialists simultaneously
- 🧬 **Adaptive Resonance:** Specialist selection via resonance matching
- 🐜 **Stigmergic Coordination:** Emergent behavior through environmental signals
- 📊 **Quality Assessment:** Content quality scoring and selection
- 💾 **Distributed Learning:** All specialist results contribute to evolution
- 🎯 **Cost Transparency:** Clear cost warnings for parallel execution

### RIP Swarm Features
- 🧠 **7-Stage Cognitive Pipeline:** Comprehensive preprocessing before orchestration
- 🗺️ **3DKF Knowledge Mapping:** 8-category knowledge categorization
- 🔄 **Recursive Processing:** Configurable depth levels (shallow to hyperdeep)
- 🎨 **Pattern Evolution:** Primary and emergent pattern discovery
- ⚓ **Stability Anchoring:** Cognitive and perceptual coherence verification
- 🎯 **Lucidity Verification:** Multi-point quality checks and certification
- 📈 **Cognitive State Tracking:** Monitor progression toward lucidity

### Shared Features
- 🎛️ **Interactive Settings:** Configure both processing modes, thresholds, and parameters
- 📈 **System Monitoring:** Real-time swarm trace visualization with RIP metrics
- 🎓 **In-App Tutorials:** Comprehensive guides for both Classic and RIP modes

## 🏗️ Architecture

### Processing Pipeline

```
User Input
    ↓
[RIP Mode] → 7-Stage Cognitive Pipeline → Enhanced Prompt
    ↓                                            ↓
[Classic Mode] ────────────────────────────→ 3-Layer Orchestration
                                                 ↓
                                          Final Response
```

### Core Components

#### RIP Pipeline Components (When Enabled)
- **State Assessment Engine:** Cognitive profiling and bias detection
- **Knowledge Mapper:** 3DKF categorization across 8 dimensions
- **Recursive Engine:** Iterative depth processing with convergence tracking
- **Pattern Synthesizer:** Primary and emergent pattern discovery
- **Stability Verifier:** Cognitive anchor establishment and coherence checks
- **Integration Synthesizer:** Multi-perspective harmonization
- **Lucidity Verifier:** Final quality certification and threshold checking

#### Classic Swarm Components (Always Active)
- **Adaptive Resonance Layer:** Specialist matching and resonance calculation
- **Hybrid Orchestrator:** Stigmergic coordination decision-making
- **Stigmergic Board:** Environmental signal management
- **Parallel Executor:** Simultaneous specialist execution with quality voting
- **Content Analyzer:** Response quality assessment

### Key Technologies
- **Frontend:** React + TypeScript with Shadcn/UI components
- **Build System:** Vite with SWC compilation
- **State Management:** Zustand stores
- **Database:** IndexedDB via Dexie
- **API Integration:** OpenRouter.ai for LLM access

## 🔗 Related Projects

- 🧪 **Prototype:** [ADDM Agentic Loop Regulator](https://github.com/MushroomFleet/ADDM-Agentic-Loop-Regulator)
- 📋 **Phase Plans:** [Agentic DDM Framework](https://github.com/MushroomFleet/Agentic-DDM-Framework)
- 🤖 **Claude Code Agent:** [Hybrid Swarm Agent](https://github.com/MushroomFleet/Hybrid-Swarm-Agent)
- 🧪 **Research Lab:** [Cognition-9 Research](https://github.com/MushroomFleet/Cognition-9)

## 📋 Usage

1. **Set your OpenRouter API key** in Settings → API Configuration
2. **Choose your processing mode** in Settings → Swarm Mode:
   - **Classic Swarm:** Fast, task-focused orchestration
   - **RIP Swarm:** Deep cognitive preprocessing + orchestration
3. **Compose your task query** in the chat interface
4. **Choose execution format:**
   - Sequential: Traditional single-specialist response
   - Parallel: Multi-specialist execution (configurable 2-5 specialists)
5. **Monitor swarm trace** to understand:
   - Classic: Coordination decisions, specialist selection, approach matching
   - RIP: Cognitive state, knowledge mapping, recursion depth, stability scores
6. **Experiment with settings** to optimize for your use case

### RIP Configuration Options
- **Processing Mode:** Quick (4 stages), Standard (7 stages), Deep, Creative
- **Recursion Depth:** Shallow (1-3), Standard (4-7), Deep (8-12), Hyperdeep (13+)
- **Thresholds:** Stability (default 70%), Lucidity (default 80%)
- **Advanced:** Auto mode switching, hyperstition seed tracking

## 🎛️ Configuration

### Swarm Mode Settings
- **Classic Swarm:** Fast stigmergic coordination (default)
- **RIP Swarm:** Advanced cognitive preprocessing
  - Processing modes: Quick, Standard, Deep, Creative
  - Recursion depth levels: Shallow to Hyperdeep
  - Stability and lucidity thresholds
  - Auto mode switching options

### Parallel Execution Settings
- **Enable/Disable:** Toggle parallel multi-specialist execution
- **Specialist Count:** 2-5 concurrent specialists
- **Timeout Protection:** Individual specialist timeout handling
- **Cost Warnings:** Transparent API cost multiplication

### System Parameters
- **Vigilance Threshold:** Specialist resonance filtering (Classic Swarm)
- **Pattern Discovery:** Automatic learning enablement
- **Execution History:** Response tracking and learning

## 🤝 Contributing

We welcome contributions! Hybrid-Swarm is an open research platform for studying AI coordination patterns.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly (see implementation-progress.md for testing guidelines)
5. Submit a pull request

### Development Tips
- Run `npm run lint` for code quality checks
- Use the swarm trace for debugging coordination decisions
- Test with both sequential and parallel execution modes

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{hybrid_swarm_local,
  title = {Hybrid-Swarm-Local: Stigmergic AI Coordination with RIP Cognitive Processing},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/Hybrid-Swarm-Local},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

## 📄 License

Copyright 2025 Drift Johnson. All rights reserved.

## ⚠️ Disclaimer

This software is experimental and provided as-is for research purposes. Use of AI systems should follow ethical guidelines and consider potential risks.
