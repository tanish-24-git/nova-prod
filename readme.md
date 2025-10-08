# tem file strcut #

```
nova-auto/
│
├── backend/
│   ├── python_core/
│   │   ├── main.py
│   │   ├── api/
│   │   │   ├── __init__.py
│   │   │   ├── routes.py
│   │   │   ├── planner.py
│   │   │   ├── validator.py
│   │   │   ├── recovery.py
│   │   │   ├── translator.py
│   │   └── agents/
│   │       ├── command_planner.py
│   │       ├── cross_platform.py
│   │       ├── validation.py
│   │       ├── error_recovery.py
│   │       ├── gui_automation.py
│   │       ├── ocr_module.py
│   │       └── llm_interface.py
│   │
│   ├── models/
│   │   ├── workflow_schema.py
│   │   ├── command_schema.py
│   │   └── system_logs.py
│   │
│   ├── utils/
│   │   ├── logger.py
│   │   ├── config.py
│   │   ├── os_helper.py
│   │   └── executor_interface.py
│   │
│   └── requirements.txt
│
├── rust_executor/
│   ├── Cargo.toml
│   ├── src/
│   │   ├── main.rs
│   │   ├── executor.rs
│   │   ├── system_control.rs
│   │   ├── gui_bridge.rs
│   │   ├── command_handler.rs
│   │   ├── error_handler.rs
│   │   └── logger.rs
│
├── ui/
│   ├── src/
│   │   ├── main.tsx
│   │   ├── components/
│   │   │   ├── Terminal.tsx
│   │   │   ├── WorkflowVisualizer.tsx
│   │   │   ├── CommandStatus.tsx
│   │   │   └── LogViewer.tsx
│   │   ├── hooks/
│   │   │   ├── useWorkflow.ts
│   │   │   ├── useSystemStatus.ts
│   │   │   └── useTheme.ts
│   │   ├── styles/
│   │   │   └── global.css
│   │   └── utils/
│   │       ├── api.ts
│   │       └── constants.ts
│   │
│   ├── tauri.conf.json
│   ├── package.json
│   └── vite.config.ts
│
├── data/
│   ├── logs/
│   ├── screenshots/
│   ├── workflows/
│   └── configs/
│
├── docker/
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── tests/
│   ├── python_tests/
│   ├── rust_tests/
│   ├── ui_tests/
│   └── integration_tests/
│
└── README.md
```