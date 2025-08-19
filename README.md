# Zero Trust Security Policies for Cilium with eBPF

## CiliumNetworkPolicy

A 3-policy setup for an app namespace that locks down INGRESS traffic, but allows Prometheus scraping and an ALLOW ALL rule for EGRESS traffic