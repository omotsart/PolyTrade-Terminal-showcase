# Архитектура (RU)

## Слои системы
1. Ingestion/Intel: market snapshot, rules extraction, news collection.
2. AI reasoning: multi-agent pipeline, consensus, validation.
3. Forecast orchestration: unified forecast contract, edge/ranking, report assembly.
4. UI layer: Hub + AI Forecast (multi-table, heatmap, explainability).
5. Quality/ops: logging, calibration, readiness reports, rollout/canary controls.

## Ключевые свойства
- Explainable output (reasons/risks/citations).
- Binary + multi-outcome совместимость.
- No-raise gateway поведение для устойчивости runtime.
- Runtime telemetry для agreement/edge/agent metrics.
