# Forge Development Repository

> 🚧 **Development Branch** - main development repository for Forge

## About Forge

Forge builds projects incrementally using a content-addressed cache.

## 🔧 Development Status

This repository is under active development. Many features are TODO.

### 🔴 High Priority TODOs

- Core functionality is still being implemented across modules.

### 📝 Complete TODO List

- [ ] **forge/cache/store.py:2** - garbage-collect unreferenced blobs
- [ ] **forge/cache/store.py:6** - verify content hash on read
- [ ] **forge/cli/main.py:2** - add a --dry-run flag
- [ ] **forge/cli/main.py:3** - print a build summary at the end
- [ ] **forge/graph/dag.py:3** - detect and report cycles eagerly
- [ ] **forge/graph/dag.py:7** - make ordering deterministic across runs
- [ ] **forge/graph/dag.py:8** - parallelize independent build nodes

## 🤝 Contributing

1. Pick a TODO item from the list above
2. Implement the functionality
3. Update this README when TODOs are completed
