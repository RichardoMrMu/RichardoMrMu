# Hi, I'm Mu Huai

AI Infrastructure & Agent Observability engineer working on telemetry correctness across inference engines and agent runtimes.

My current focus:

- distributed tracing and low-overhead metrics for LLM serving;
- KV-cache and prefill/decode disaggregation observability;
- streaming, cancellation, context propagation, and span-finalization correctness;
- OpenTelemetry instrumentation and semantic conventions for agent systems.

## Selected open-source contributions

- **SGLang:** [speculative decoding tracing](https://github.com/sgl-project/sglang/pull/19545) and [chunked-prefill observability work](https://github.com/sgl-project/sglang/pull/25365).
- **vLLM:** [OpenTelemetry request-attribute propagation](https://github.com/vllm-project/vllm/pull/20372).
- **LoongSuite:** Agent telemetry context-isolation fixes for [Hermes](https://github.com/alibaba/loongsuite-python/pull/184) and [AgentScope ReAct](https://github.com/alibaba/loongsuite-python/pull/187).
- **OpenDerisk:** observability improvements in [#128](https://github.com/derisk-ai/OpenDerisk/pull/128) and [#130](https://github.com/derisk-ai/OpenDerisk/pull/130).

## Current maintenance themes

I am contributing and reviewing around SGLang observability, OpenTelemetry Python GenAI lifecycle correctness, and vLLM metrics/KV telemetry. I prefer scoped changes with reproducible tests, bounded metric cardinality, and clear success/error/cancellation semantics.

You can reach me through GitHub issues and pull requests related to these areas.
