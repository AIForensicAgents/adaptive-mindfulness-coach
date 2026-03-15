┌──────────────────────────────────────────────────────────────────────┐
│                          USER LAYER                                  │
│                                                                      │
│   📱 Mobile / Tablet / Web       🎧 Wearable (opt-in)               │
│   ┌──────────────┐               ┌──────────────┐                   │
│   │ Audio/Video   │               │ HR · HRV ·   │                   │
│   │ Check-In      │               │ Sleep · Accel │                   │
│   └──────┬───────┘               └──────┬───────┘                   │
│          │                               │                           │
└──────────┼───────────────────────────────┼───────────────────────────┘
           │           ┌───────────┐       │
           └──────────►│  Ingestion │◄──────┘
                       │  Gateway   │
                       └─────┬─────┘
                             ▼
              ┌──────────────────────────┐
              │   🧠 AI ADAPTATION CORE  │
              │                          │
              │  ┌────────────────────┐  │
              │  │ Multimodal Fusion  │  │
              │  │ (NLP + CV + Bio)   │  │
              │  └────────┬───────────┘  │
              │           ▼              │
              │  ┌────────────────────┐  │
              │  │ Personalization    │  │
              │  │ Engine             │  │
              │  │ (Cognitive/Physi-  │  │
              │  │  cal Profile)      │  │
              │  └────────┬───────────┘  │
              │           ▼              │
              │  ┌────────────────────┐  │
              │  │ Real-Time Session  │  │
              │  │ Orchestrator       │  │
              │  └────────┬───────────┘  │
              │           ▼              │
              │  ┌────────────────────┐  │
              │  │ Micro-Goal &       │  │
              │  │ Progress Tracker   │  │
              │  └────────────────────┘  │
              └──────────┬───────────────┘
                         ▼
              ┌──────────────────────────┐
              │  🎵 SESSION DELIVERY     │
              │                          │
              │  Adaptive Audio/Visual   │
              │  Guided Experience       │
              │  + Post-Session Summary  │
              │  + Document Simplifier   │
              └──────────────────────────┘