# Envoy playground - Basics

A basic demo playground simulating some service-to-service communication scenarios.

```bash
for _ in {1..1000}; do curl --silent localhost:8080; done | sort | uniq -w 8 -c
```
