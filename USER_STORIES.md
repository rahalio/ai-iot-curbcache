# CurbCache — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Perception engineer

- As a perception engineer, I want ≤100 ms offload of vision features to roadside EIS, so we meet safety timing without 250 TOPS in-car.
- As a perception engineer, I want cooperative fusion policies, so we share detections without dumping raw video by default.

### Map ops

- As map ops, I want crowdsourced tile contributions with quality scores, so HD maps stay fresh without only survey fleets.
- As map ops, I want freshness SLAs on cached tiles, so vehicles do not localize on stale geometry.

### MEC planner

- As MEC planner, I want VaaC/VaaS session metrics, so we size RAP compute for peak corridors.

### Safety assurance

- As safety, I want mandatory fallback profiles when RAP disconnects, so autonomy does not wait on the network.

### Exception

- As a vehicle agent, I want to reject a cooperative share request that violates policy, so compromised neighbors cannot siphon features.

### Admin

- As an admin, I want fleet and city tenant isolation on the same RAP, so multi-OEM EIS coexists.
