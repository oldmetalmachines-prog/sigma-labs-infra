# Sigma Labs Infrastructure

Infrastructure design and Docker Compose stacks for the Sigma Labs robotics lab.

Contents:
- design/ : infrastructure blueprint and design decisions
- compose/ : Phase 0 Docker Compose stacks (S410 staging)
- docs/ : runbooks and procedures

Quick Deploy on S410:
cd compose/networking && docker compose up -d
cd compose/telemetry  && docker compose up -d
cd compose/management && docker compose up -d
