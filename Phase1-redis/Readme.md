# Kubernetes DevOps Project

## Phase 1 — Redis DB Layer
- Redis Deployment (v7)
- ClusterIP Service
- Internal DNS resolution

## Phase 2 — Backend Layer
- Redis Commander backend
- Env-based DB connection
- Rolling update strategy
- ClusterIP internal service
- NodePort external testing

## Architecture
User → Backend → Redis

## Next Phases
- Phase 3: Redis StatefulSet + Persistent Volume
- Phase 4: Helm Packaging
- Phase 5: Prometheus Monitoring
- Phase 6: Terraform Infra
