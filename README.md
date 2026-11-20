## Marc Bartholet

ML engineer on an ML platform team in Switzerland. I work on production LLM systems:
serving and performance tuning with vLLM and Ray Serve, agent systems
(harnesses, agents, workflows), and data pipelines. Before that, I did research at ETH Zurich and KAIST.

**Some things I've worked on:**

- [Ray Serve LLM, PR #63881](https://github.com/ray-project/ray/pull/63881): fix for
  fractional-GPU environment variables not reaching Ray Serve LLM replica actors. Tested
  on an NVIDIA L4. Merged.
- [Ray Serve LLM, PR #65011](https://github.com/ray-project/ray/pull/65011): stops API
  error responses from exposing remote tracebacks to clients. Merged; closes issue
  [#64832](https://github.com/ray-project/ray/issues/64832).
- [Issue #64833](https://github.com/ray-project/ray/issues/64833): Ray Serve LLM error
  responses don't fully match the OpenAI error format. Open.
- Research: [Hypernetwork-Driven Model Fusion for Federated Domain
  Generalization](https://arxiv.org/abs/2402.06974) ([code](https://github.com/mbartholet/hFedF)),
  and two clinical ML papers as co-author ([Frontiers in Medicine 2024](https://doi.org/10.3389/fmed.2024.1439218),
  [ICLR 2024 Workshop TS4H](https://openreview.net/forum?id=Ll9wIIkeEp)).
