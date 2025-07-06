This repository contains the results of an experiment comparing **guided** and **unguided** LLM-generated RML mappings across three real-world scenarios from Irish open data.

## Scenarios

- **Scenario 1:** Irish County Boundaries (CSV)
- **Scenario 2:** Population per NUTS 3 Region (JSON)
- **Scenario 3:** Electoral Divisions (CSV)

Each folder contains:

- `guided_prompt.txt`: The full prompt used for the guided version
- `unguided_prompt.txt`: The unguided prompt
- `rml_guided.ttl`: RML mapping generated from the guided prompt
- `rml_unguided.ttl`: RML mapping generated from the unguided prompt
- The original dataset file used


