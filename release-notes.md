:robot: I have created a release *beep* *boop*
---


<details><summary>python-openinference-semantic-conventions: 0.1.18</summary>

## [0.1.18](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-semantic-conventions-v0.1.17...python-openinference-semantic-conventions-v0.1.18) (2025-06-09)


### Features

* Add prompt-related semantic conventions ([#1244](https://github.com/igor-gorohovsky/openinference/issues/1244)) ([4f2f842](https://github.com/igor-gorohovsky/openinference/commit/4f2f842f3c23f3269ea902054b0c9d9d23928285))
* add tool call id ([#1085](https://github.com/igor-gorohovsky/openinference/issues/1085)) ([4813de5](https://github.com/igor-gorohovsky/openinference/commit/4813de5e8f9e7a22e27e6c20353a529a7fd640b6))
* **semcov:** add audio token counts to semantic convention  ([#1453](https://github.com/igor-gorohovsky/openinference/issues/1453)) ([ae5cd15](https://github.com/igor-gorohovsky/openinference/commit/ae5cd15d0a702f976908d84a6d87847859c4685a))
* **semcov:** audio conventions ([#1153](https://github.com/igor-gorohovsky/openinference/issues/1153)) ([1188c6d](https://github.com/igor-gorohovsky/openinference/commit/1188c6d3363a388f3eacf35c8a8669084fdefd5b))
* **semcov:** llm system and llm provicer conventions ([#1071](https://github.com/igor-gorohovsky/openinference/issues/1071)) ([d200d85](https://github.com/igor-gorohovsky/openinference/commit/d200d8509c28407c6b68426b579fd8a547f13579))
* **semcov:** token counts for cached prompts and reasoning steps in the completion ([#1393](https://github.com/igor-gorohovsky/openinference/issues/1393)) ([c4e2252](https://github.com/igor-gorohovsky/openinference/commit/c4e225244adc287b9b011972bc980550939e126a))


### Bug Fixes

* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation: 0.1.33</summary>

## [0.1.33](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-v0.1.32...python-openinference-instrumentation-v0.1.33) (2025-06-09)


### Features

* add ability to hide LLM invocation paramaters for OITracer ([#1171](https://github.com/igor-gorohovsky/openinference/issues/1171)) ([f7e94c7](https://github.com/igor-gorohovsky/openinference/commit/f7e94c7f658570169c564f11663fc9eeaee05f46))
* add manual instrumentation helpers for llm spans ([#1424](https://github.com/igor-gorohovsky/openinference/issues/1424)) ([ee79fa3](https://github.com/igor-gorohovsky/openinference/commit/ee79fa35c247608f21b902b84443427ddf643314))
* Agno instrumentor ([#1603](https://github.com/igor-gorohovsky/openinference/issues/1603)) ([50f30e2](https://github.com/igor-gorohovsky/openinference/commit/50f30e26b5fcc074cc8a7dbbc34e9c11b7af0e41))
* attribute prioritization ([#906](https://github.com/igor-gorohovsky/openinference/issues/906)) ([0add042](https://github.com/igor-gorohovsky/openinference/commit/0add0421b5f0d9b64c579027c469513359863a68))
* id generator with separate source of randomness ([#1010](https://github.com/igor-gorohovsky/openinference/issues/1010)) ([ac8cce1](https://github.com/igor-gorohovsky/openinference/commit/ac8cce112341bb31a575cb1e61a55acb196fc600))
* **instrumentation:** add helpers for remaining semantic conventions ([#1606](https://github.com/igor-gorohovsky/openinference/issues/1606)) ([cb3d4fa](https://github.com/igor-gorohovsky/openinference/commit/cb3d4fa5f0b5d3281c60fa02fa9219813218e815))
* openai-agents instrumentation ([#1350](https://github.com/igor-gorohovsky/openinference/issues/1350)) ([9afbad3](https://github.com/igor-gorohovsky/openinference/commit/9afbad3100d68601a2f9265fe20985a34f80e04b))
* openinference tracer ([#1147](https://github.com/igor-gorohovsky/openinference/issues/1147)) ([22d80ca](https://github.com/igor-gorohovsky/openinference/commit/22d80ca066a8d29e9b9ef08ce581b4a7ad4eb08b))
* pydanticai instrumentation ([#1639](https://github.com/igor-gorohovsky/openinference/issues/1639)) ([d8c5b9c](https://github.com/igor-gorohovsky/openinference/commit/d8c5b9cdf793dcce247b2ea852c28eba3a1989bc))


### Bug Fixes

* add missing dependency opentelemetry-sdk ([#1026](https://github.com/igor-gorohovsky/openinference/issues/1026)) ([11e6cb9](https://github.com/igor-gorohovsky/openinference/commit/11e6cb98cf2efe73fd3b3972869d8527db67cc72))
* add type stubs for openinference span ([#1415](https://github.com/igor-gorohovsky/openinference/issues/1415)) ([2170977](https://github.com/igor-gorohovsky/openinference/commit/21709778f59c2fd31b1c14ee1bfb465e48771d5b))
* allow user override of id generator ([#1315](https://github.com/igor-gorohovsky/openinference/issues/1315)) ([1916749](https://github.com/igor-gorohovsky/openinference/commit/19167498fd74f2e93481bd63b5636e264af1eaab))
* ensure `OpenInferenceSpan` is an instance of `opentelemetry.trace.Span` for type checks ([#1441](https://github.com/igor-gorohovsky/openinference/issues/1441)) ([b2c8959](https://github.com/igor-gorohovsky/openinference/commit/b2c895967e881444ff339d28b440375f6edaec74))
* ensure io attributes output by manual instrumentation helpers are always strings ([#1502](https://github.com/igor-gorohovsky/openinference/issues/1502)) ([43c7f4a](https://github.com/igor-gorohovsky/openinference/commit/43c7f4a41d9d36828d0f45907e7a580ce97dd68e))
* increase python upperbound to include 3.13 for openinference-instrumentation ([#1137](https://github.com/igor-gorohovsky/openinference/issues/1137)) ([0c2f297](https://github.com/igor-gorohovsky/openinference/commit/0c2f297bb479b6cd4a70c7e0b28d6578e0abc6e3))
* remove setting the global logger level ([#1001](https://github.com/igor-gorohovsky/openinference/issues/1001)) ([5c0f83c](https://github.com/igor-gorohovsky/openinference/commit/5c0f83c355304da289ae1c849b9d315990281184))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
* update readmes for development setup and fixes ([#1629](https://github.com/igor-gorohovsky/openinference/issues/1629)) ([7b211b3](https://github.com/igor-gorohovsky/openinference/commit/7b211b3b1624ab433ba35568112f0a1d8964456f))
</details>

<details><summary>python-openinference-instrumentation-agno: 0.1.7</summary>

## [0.1.7](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-agno-v0.1.6...python-openinference-instrumentation-agno-v0.1.7) (2025-06-09)


### Features

* Agno instrumentor ([#1603](https://github.com/igor-gorohovsky/openinference/issues/1603)) ([50f30e2](https://github.com/igor-gorohovsky/openinference/commit/50f30e26b5fcc074cc8a7dbbc34e9c11b7af0e41))
* Updates for new Agno verison ([#1647](https://github.com/igor-gorohovsky/openinference/issues/1647)) ([8292d0d](https://github.com/igor-gorohovsky/openinference/commit/8292d0d5620a9c58c4646e553704a31fd3f8cba3))


### Bug Fixes

* Agno duplicate model invoke ([#1614](https://github.com/igor-gorohovsky/openinference/issues/1614)) ([919e776](https://github.com/igor-gorohovsky/openinference/commit/919e776c41fc902f76e8da495c7618ae0ad84292))
* **agno:** Allow agent.name to be `None` in `arun`. ([#1621](https://github.com/igor-gorohovsky/openinference/issues/1621)) ([5288979](https://github.com/igor-gorohovsky/openinference/commit/52889796daa5ac221af21b76d77b80e594cdcf89))
* filter sensitive model params ([#1737](https://github.com/igor-gorohovsky/openinference/issues/1737)) ([fe7ebbe](https://github.com/igor-gorohovsky/openinference/commit/fe7ebbe9f7663e39d6f18ee1be9f775f0f6e7fb4))
* handle AgnoInstrumentor failing with OpenAIResponses ([#1701](https://github.com/igor-gorohovsky/openinference/issues/1701)) ([f33fadf](https://github.com/igor-gorohovsky/openinference/commit/f33fadf5a67fd4bce8ba590cdae4c9b7d1133d74))
</details>

<details><summary>python-openinference-instrumentation-mistralai: 2.0.0</summary>

## [2.0.0](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-mistralai-v1.3.3...python-openinference-instrumentation-mistralai-v2.0.0) (2025-06-09)


###   BREAKING CHANGES

* **mistralai:** support v1 ([#947](https://github.com/igor-gorohovsky/openinference/issues/947))

### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **mistral:** add agent support ([#1043](https://github.com/igor-gorohovsky/openinference/issues/1043)) ([d1d6b2f](https://github.com/igor-gorohovsky/openinference/commit/d1d6b2fea6af8352cd5b4b907c0c8622302bd450))
* **mistralai:** support v1 ([#947](https://github.com/igor-gorohovsky/openinference/issues/947)) ([2cb2bf9](https://github.com/igor-gorohovsky/openinference/commit/2cb2bf9a092b7fff9169c08973babbbb473c6ea4))


### Bug Fixes

* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* remove mistralai dependency in mistralai instrumentor ([#1271](https://github.com/igor-gorohovsky/openinference/issues/1271)) ([17c0ce5](https://github.com/igor-gorohovsky/openinference/commit/17c0ce5a1ddc48a5c7a835f09941569232458f76))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-openai: 0.1.31</summary>

## [0.1.31](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-openai-v0.1.30...python-openinference-instrumentation-openai-v0.1.31) (2025-06-09)


### Features

* add cached read semantic conventions to openai sdk ([#1485](https://github.com/igor-gorohovsky/openinference/issues/1485)) ([2db5918](https://github.com/igor-gorohovsky/openinference/commit/2db591850259c1ff1fe606151f7f8be1ec1d63a7))
* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* add tool call id to openai instrumentor ([#1090](https://github.com/igor-gorohovsky/openinference/issues/1090)) ([9bbadd2](https://github.com/igor-gorohovsky/openinference/commit/9bbadd23a371b6adb8378bd6f5cbe1e275241804))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* instrument OpenAI responses API ([#1521](https://github.com/igor-gorohovsky/openinference/issues/1521)) ([64cde2b](https://github.com/igor-gorohovsky/openinference/commit/64cde2b7230bfae3e7f7fb1141708a86ceea6b1a))
* Openai audio + reasoning token counts ([#1547](https://github.com/igor-gorohovsky/openinference/issues/1547)) ([cbae31b](https://github.com/igor-gorohovsky/openinference/commit/cbae31b2838234a3fe388a1501caadd281ac545e))
* **openai:** add llm provider and system attributes ([#1082](https://github.com/igor-gorohovsky/openinference/issues/1082)) ([232c031](https://github.com/igor-gorohovsky/openinference/commit/232c031deea6b81a007447a37db2b0e5eb8ce613))


### Bug Fixes

* add google as provider for openai instrumentor ([#1131](https://github.com/igor-gorohovsky/openinference/issues/1131)) ([3ef4243](https://github.com/igor-gorohovsky/openinference/commit/3ef424304343ede04910512380ef4c0a01638fb0))
* CI Failures For OpenAI & OpenAI Agents ([#1725](https://github.com/igor-gorohovsky/openinference/issues/1725)) ([69576ca](https://github.com/igor-gorohovsky/openinference/commit/69576cac4628f7d3b1b36558ad6cf8e4ae65b2d8))
* CI Failures For OpenAI & OpenAI Agents Follow Up ([#1733](https://github.com/igor-gorohovsky/openinference/issues/1733)) ([ec1e855](https://github.com/igor-gorohovsky/openinference/commit/ec1e8552b40c8a04ee2b3b92073e41e405b95293))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* remove httpx dependency ([#1093](https://github.com/igor-gorohovsky/openinference/issues/1093)) ([41c6557](https://github.com/igor-gorohovsky/openinference/commit/41c655708e954aa362adc7f62f1b98324fb30ce9))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/igor-gorohovsky/openinference/issues/1600)) ([076bb79](https://github.com/igor-gorohovsky/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
* **openai:** simplify tool calling example ([#1069](https://github.com/igor-gorohovsky/openinference/issues/1069)) ([67da961](https://github.com/igor-gorohovsky/openinference/commit/67da961147ff6ac6892bd6683e4048cad35906a5))
</details>

<details><summary>python-openinference-instrumentation-openai-agents: 0.1.15</summary>

## [0.1.15](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-openai-agents-v0.1.14...python-openinference-instrumentation-openai-agents-v0.1.15) (2025-06-09)


### Features

* cached and reasoning tokens from response api ([#1461](https://github.com/igor-gorohovsky/openinference/issues/1461)) ([a9f257c](https://github.com/igor-gorohovsky/openinference/commit/a9f257c1dee46eb18ed32f463bdc50cc7cab60fe))
* capture result from MCPListToolsSpanData ([#1458](https://github.com/igor-gorohovsky/openinference/issues/1458)) ([66abe50](https://github.com/igor-gorohovsky/openinference/commit/66abe50f187a45ce11fb64f3399b52a3139fe115))
* openai-agents instrumentation ([#1350](https://github.com/igor-gorohovsky/openinference/issues/1350)) ([9afbad3](https://github.com/igor-gorohovsky/openinference/commit/9afbad3100d68601a2f9265fe20985a34f80e04b))
* **openai-agents:** add support for exclusive processor configuration ([#1586](https://github.com/igor-gorohovsky/openinference/issues/1586)) ([47c2ac3](https://github.com/igor-gorohovsky/openinference/commit/47c2ac350a113bf7df45fbcebdfc19504e73723c))


### Bug Fixes

* add span attributes for FunctionSpanData ([#1408](https://github.com/igor-gorohovsky/openinference/issues/1408)) ([48d1a35](https://github.com/igor-gorohovsky/openinference/commit/48d1a3549eb8dda55e941cab867d9581a96fdf33))
* attach span to otel context on span start ([#1373](https://github.com/igor-gorohovsky/openinference/issues/1373)) ([b44809f](https://github.com/igor-gorohovsky/openinference/commit/b44809f1c460dd3a9bee4a9b068e6c275fecf9b4))
* CI Failures For OpenAI & OpenAI Agents ([#1725](https://github.com/igor-gorohovsky/openinference/issues/1725)) ([69576ca](https://github.com/igor-gorohovsky/openinference/commit/69576cac4628f7d3b1b36558ad6cf8e4ae65b2d8))
* CI Failures For OpenAI & OpenAI Agents Follow Up ([#1733](https://github.com/igor-gorohovsky/openinference/issues/1733)) ([ec1e855](https://github.com/igor-gorohovsky/openinference/commit/ec1e8552b40c8a04ee2b3b92073e41e405b95293))
* classify handoff span as tool span ([#1374](https://github.com/igor-gorohovsky/openinference/issues/1374)) ([e75a444](https://github.com/igor-gorohovsky/openinference/commit/e75a444d766d900ec3bc78b9d257453fb0e586d1))
* get attributes from GenerationSpanData (i.e. chat completions api) ([#1426](https://github.com/igor-gorohovsky/openinference/issues/1426)) ([c0f238d](https://github.com/igor-gorohovsky/openinference/commit/c0f238d36f18bdec0062e84ca4e53a66c63508e0))
* handle error: invalid type dict in attribute 'output.value' value sequence ([#1443](https://github.com/igor-gorohovsky/openinference/issues/1443)) ([34bacfd](https://github.com/igor-gorohovsky/openinference/commit/34bacfd9369dfb098e931cf20982b286fcb7fbea))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* openai agent with int tool return ([#1419](https://github.com/igor-gorohovsky/openinference/issues/1419)) ([1bb75a9](https://github.com/igor-gorohovsky/openinference/commit/1bb75a94999bbe8615cdc7a5490fb2668833742f))
* **openai_agents:** Set status `on_span_end`. ([#1556](https://github.com/igor-gorohovsky/openinference/issues/1556)) ([2b53efa](https://github.com/igor-gorohovsky/openinference/commit/2b53efa491d81ab5852387f5a4d2e87972262616))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/igor-gorohovsky/openinference/issues/1600)) ([076bb79](https://github.com/igor-gorohovsky/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-vertexai: 0.1.12</summary>

## [0.1.12](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-vertexai-v0.1.11...python-openinference-instrumentation-vertexai-v0.1.12) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))


### Bug Fixes

* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* support function call parts when streaming ([#1587](https://github.com/igor-gorohovsky/openinference/issues/1587)) ([43abca2](https://github.com/igor-gorohovsky/openinference/commit/43abca26f75277f1a605389b1e99a19220104820))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-llama-index: 5.0.0</summary>

## [5.0.0](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-llama-index-v4.3.0...python-openinference-instrumentation-llama-index-v5.0.0) (2025-06-09)


###   BREAKING CHANGES

* support chat message content blocks for llama-index >= 0.12.3 ([#1446](https://github.com/igor-gorohovsky/openinference/issues/1446))
* support pydanticV2 for llama-index 0.11 ([#971](https://github.com/igor-gorohovsky/openinference/issues/971))

### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* add get_current_span helper function for llama-index ([#1165](https://github.com/igor-gorohovsky/openinference/issues/1165)) ([b46931c](https://github.com/igor-gorohovsky/openinference/commit/b46931c7cec73f73873a3ae15003f3c6c52173e1))
* add toggle to separate trace from runtime context ([#1464](https://github.com/igor-gorohovsky/openinference/issues/1464)) ([0865a69](https://github.com/igor-gorohovsky/openinference/commit/0865a69904119676703e5ca26600458dd9fb60f2))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **llama-index py:** capture reasoning, cache, and audio tokens ([#1489](https://github.com/igor-gorohovsky/openinference/issues/1489)) ([9d0ec39](https://github.com/igor-gorohovsky/openinference/commit/9d0ec3991a6adf7932b0b2069f38a6e83bb1b752))
* **llama-index:** Add LLM provider detection with lazy imports - res& ([#1710](https://github.com/igor-gorohovsky/openinference/issues/1710)) ([f20ac82](https://github.com/igor-gorohovsky/openinference/commit/f20ac827b1b38fe298e69753f6718b52e0807aa0))
* support chat message content blocks for llama-index &gt;= 0.12.3 ([#1446](https://github.com/igor-gorohovsky/openinference/issues/1446)) ([291dc0a](https://github.com/igor-gorohovsky/openinference/commit/291dc0a8d071f6b3a25b5b5cd8a5fe2d756a3cda))
* support pydanticV2 for llama-index 0.11 ([#971](https://github.com/igor-gorohovsky/openinference/issues/971)) ([ba203b8](https://github.com/igor-gorohovsky/openinference/commit/ba203b8bb16c73113c273516d0a4bf7b0d553bf1))


### Bug Fixes

* capture tools from chat kwargs ([#1509](https://github.com/igor-gorohovsky/openinference/issues/1509)) ([2083836](https://github.com/igor-gorohovsky/openinference/commit/2083836872dd9b3f4c40bcf66a2c3054f30aa59a))
* Don't check length when converting ToolMetadata to OpenAI format ([#1004](https://github.com/igor-gorohovsky/openinference/issues/1004)) ([47e9c77](https://github.com/igor-gorohovsky/openinference/commit/47e9c779c9ccc464faa30c2ad3637028cfe6cc80))
* get_current_span should return None when llama-index is not instrumented ([#1169](https://github.com/igor-gorohovsky/openinference/issues/1169)) ([12d64bc](https://github.com/igor-gorohovsky/openinference/commit/12d64bc489bc1530458f10e815f771ac8a42fd02))
* handle multiple embedding events for llama-index ([#1166](https://github.com/igor-gorohovsky/openinference/issues/1166)) ([0cef233](https://github.com/igor-gorohovsky/openinference/commit/0cef233aa3ad60a17bbc28e4c80d1d1bb859f360))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* **llama-index:** Capture tool call id from additional_kwargs ([#1299](https://github.com/igor-gorohovsky/openinference/issues/1299)) ([14c1c0c](https://github.com/igor-gorohovsky/openinference/commit/14c1c0c8f206a00f6cf67a9c1995c24283687f37))
* **llama-index:** capture tool calls from anthropic chat response ([#1177](https://github.com/igor-gorohovsky/openinference/issues/1177)) ([e1ba6a5](https://github.com/igor-gorohovsky/openinference/commit/e1ba6a5dcfc7f6b43cbe40d62e7bff55d45a3f12))
* **llama-index:** coerce token counts to be integers ([#1183](https://github.com/igor-gorohovsky/openinference/issues/1183)) ([3af6ca6](https://github.com/igor-gorohovsky/openinference/commit/3af6ca626c8f37c931eb51b846b0b3d24afdb615))
* **llama-index:** ensure llamaindex response models are serializable ([#997](https://github.com/igor-gorohovsky/openinference/issues/997)) ([c1cb203](https://github.com/igor-gorohovsky/openinference/commit/c1cb203f1230d9aa3557736deb7b7f6fe310acca))
* **llama-index:** extract token counts for groq when streaming ([#1174](https://github.com/igor-gorohovsky/openinference/issues/1174)) ([0aafe9c](https://github.com/igor-gorohovsky/openinference/commit/0aafe9c78a4455ab2612a34a5c648e1362c338cc))
* **llama-index:** fix typo in llama-index entry point ([#1288](https://github.com/igor-gorohovsky/openinference/issues/1288)) ([15f3b59](https://github.com/igor-gorohovsky/openinference/commit/15f3b5949121ce9c71f5f41d098858e492d4f5dd))
* remove attaching and detaching of opentelemetry contexts ([#1112](https://github.com/igor-gorohovsky/openinference/issues/1112)) ([0f16ffb](https://github.com/igor-gorohovsky/openinference/commit/0f16ffbebb00bb80345fafe03919bb3a5b17d2ae))
* replace logger.exception() with repr() ([#1385](https://github.com/igor-gorohovsky/openinference/issues/1385)) ([3b924da](https://github.com/igor-gorohovsky/openinference/commit/3b924da0b823e23c9170a6dae682bb0488c884cb))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-dspy: 0.1.25</summary>

## [0.1.25](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-dspy-v0.1.24...python-openinference-instrumentation-dspy-v0.1.25) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **dspy:** Add initial support for async tracing ([#1597](https://github.com/igor-gorohovsky/openinference/issues/1597)) ([205bdf0](https://github.com/igor-gorohovsky/openinference/commit/205bdf0e3a8da1c86802735112d9eff9f8dd0c5f))
* **dspy:** add instrumentation for dspy adapters ([#1057](https://github.com/igor-gorohovsky/openinference/issues/1057)) ([66799cc](https://github.com/igor-gorohovsky/openinference/commit/66799ccf88798bf628c316276886e70ef925b9cd))
* **dspy:** Display Module.forward Output in JSON Format ([#1729](https://github.com/igor-gorohovsky/openinference/issues/1729)) ([591a2d9](https://github.com/igor-gorohovsky/openinference/commit/591a2d921d6fa09342059d71d43da46076ba8fad))
* **dspy:** Instrument DSPy.Tool ([#1617](https://github.com/igor-gorohovsky/openinference/issues/1617)) ([e1ee8ff](https://github.com/igor-gorohovsky/openinference/commit/e1ee8ff86148a3fe0a8abf69bde675c8e0491cf5))


### Bug Fixes

* **dspy:** custom LM instrumentation ([#930](https://github.com/igor-gorohovsky/openinference/issues/930)) ([7f91317](https://github.com/igor-gorohovsky/openinference/commit/7f91317631302cb23c4b12701be2ba0b5fa3c3f0))
* **dspy:** dspy 2.6.0 upgrade ([#1249](https://github.com/igor-gorohovsky/openinference/issues/1249)) ([c1ab1d8](https://github.com/igor-gorohovsky/openinference/commit/c1ab1d86783c607c2114c92245a17ed9754ff2f4))
* **dspy:** instrument `dspy` rather than `dspy-ai` ([#1113](https://github.com/igor-gorohovsky/openinference/issues/1113)) ([5f6e149](https://github.com/igor-gorohovsky/openinference/commit/5f6e149d0979a822e07f81af944c22b7530f8fed))
* **dspy:** module resolution for custom LM ([#934](https://github.com/igor-gorohovsky/openinference/issues/934)) ([ef809be](https://github.com/igor-gorohovsky/openinference/commit/ef809bebf4c2a19cc932b3a828cf6137be73148b))
* **dspy:** prevent the creation of duplicate span exception events ([#1058](https://github.com/igor-gorohovsky/openinference/issues/1058)) ([54af1c3](https://github.com/igor-gorohovsky/openinference/commit/54af1c393a03831fc908b51ca7d57ab269b13552))
* **dspy:** support dspy 2.5 and above ([#1055](https://github.com/igor-gorohovsky/openinference/issues/1055)) ([467c8dc](https://github.com/igor-gorohovsky/openinference/commit/467c8dcf3c58f4f443332b2062cabfe7b10de16e))
* **dspy:** upstream max token default value change ([#1718](https://github.com/igor-gorohovsky/openinference/issues/1718)) ([1654bc1](https://github.com/igor-gorohovsky/openinference/commit/1654bc1e0734b0424f67d678ad1e5e4271a9942c))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-bedrock: 0.1.25</summary>

## [0.1.25](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-bedrock-v0.1.24...python-openinference-instrumentation-bedrock-v0.1.25) (2025-06-09)


### Features

* Add bedrock-agent instrumentation ([#1363](https://github.com/igor-gorohovsky/openinference/issues/1363)) ([e174240](https://github.com/igor-gorohovsky/openinference/commit/e174240a09db59c74b816efb3bc3176cc581d31e))
* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* **bedrock:** Multi Agent Support, capturing time metrics from metadata ([#1656](https://github.com/igor-gorohovsky/openinference/issues/1656)) ([ed367a2](https://github.com/igor-gorohovsky/openinference/commit/ed367a2707dd00d1e2fd9b7249deecd08ddd466f))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* support bedrock anthropic messages via invoke_model_with_stream_response ([#1240](https://github.com/igor-gorohovsky/openinference/issues/1240)) ([6047451](https://github.com/igor-gorohovsky/openinference/commit/6047451290578402e3d9c6544067c7845c8ec134))


### Bug Fixes

* Added exception to span when invoke_agent throws an exception  ([#1742](https://github.com/igor-gorohovsky/openinference/issues/1742)) ([1027d18](https://github.com/igor-gorohovsky/openinference/commit/1027d185ed233edacf8cfc76993c761a3b6a8afe))
* **bedrock:** ensure bedrock instrumentation does not break runtime for BedrockEmbeddings model from langchain ([#975](https://github.com/igor-gorohovsky/openinference/issues/975)) ([fbb78cd](https://github.com/igor-gorohovsky/openinference/commit/fbb78cdf13cc895add911575dc7fb400afafff7d))
* image source types for anthropic 0.49 ([#1320](https://github.com/igor-gorohovsky/openinference/issues/1320)) ([f022141](https://github.com/igor-gorohovsky/openinference/commit/f022141b990bfd1de53b4c2e9c3f32d238d27048))
* include cache tokens in prompt tokens for anthropic ([#1429](https://github.com/igor-gorohovsky/openinference/issues/1429)) ([abd36c4](https://github.com/igor-gorohovsky/openinference/commit/abd36c45ea4ff966b58eccee42de252bc876d5ab))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/igor-gorohovsky/openinference/issues/1600)) ([076bb79](https://github.com/igor-gorohovsky/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-langchain: 0.1.44</summary>

## [0.1.44](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-langchain-v0.1.43...python-openinference-instrumentation-langchain-v0.1.44) (2025-06-09)


### Features

* Add `get_chain_root_span` utility for langchain instrumentation ([#1054](https://github.com/igor-gorohovsky/openinference/issues/1054)) ([4337aa1](https://github.com/igor-gorohovsky/openinference/commit/4337aa1674476958bdfcdd3725b0145c37268425))
* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* add toggle to separate trace from runtime context ([#1464](https://github.com/igor-gorohovsky/openinference/issues/1464)) ([0865a69](https://github.com/igor-gorohovsky/openinference/commit/0865a69904119676703e5ca26600458dd9fb60f2))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **langchainpy:** capture reasoning, cache, and audio tokens  ([#1480](https://github.com/igor-gorohovsky/openinference/issues/1480)) ([22d962b](https://github.com/igor-gorohovsky/openinference/commit/22d962b7c07b5293cde02209b6702b77cd8fc0f3))
* **langchain:** track tool schemas from LLM invocation parameters ([#1643](https://github.com/igor-gorohovsky/openinference/issues/1643)) ([65d3a82](https://github.com/igor-gorohovsky/openinference/commit/65d3a8219a1a061a4fdea19b17760096b5aca76a))
* support langchain 0.3 ([#1045](https://github.com/igor-gorohovsky/openinference/issues/1045)) ([ff43e9d](https://github.com/igor-gorohovsky/openinference/commit/ff43e9ddc0a5f683f80d09139247ad194d6c29af))


### Bug Fixes

* Fix missing token counts when using VertexAI with Langchain Instrumentor ([#1234](https://github.com/igor-gorohovsky/openinference/issues/1234)) ([e387573](https://github.com/igor-gorohovsky/openinference/commit/e387573a031bdb40a78c2fe92713f132348865f7))
* handle missing attribute if .instrument() has not been called and tracer has not been initialized ([#1340](https://github.com/igor-gorohovsky/openinference/issues/1340)) ([2582513](https://github.com/igor-gorohovsky/openinference/commit/2582513ef60dc510fc3f63930b9717edfe07b9a2))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* **langchain:** don't treat langgraph agent commands as exceptions ([#1389](https://github.com/igor-gorohovsky/openinference/issues/1389)) ([af48af3](https://github.com/igor-gorohovsky/openinference/commit/af48af39afb002d63e78d77b2d0ec543442410e1))
* merge metadata ([#1497](https://github.com/igor-gorohovsky/openinference/issues/1497)) ([793101a](https://github.com/igor-gorohovsky/openinference/commit/793101a74570c0a4611c751ef518879486fdf852))
* message content when it's list of strings ([#1337](https://github.com/igor-gorohovsky/openinference/issues/1337)) ([d79f90e](https://github.com/igor-gorohovsky/openinference/commit/d79f90e8949da449bc0beef0f6ece75077d57e89))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* tuple message type ([#1488](https://github.com/igor-gorohovsky/openinference/issues/1488)) ([6b65b65](https://github.com/igor-gorohovsky/openinference/commit/6b65b656627d7910a82a0c14c70c916b0b454a3b))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-guardrails: 0.1.10</summary>

## [0.1.10](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-guardrails-v0.1.9...python-openinference-instrumentation-guardrails-v0.1.10) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **guardrails:** limit support to versions &lt;0.5.2 ([#941](https://github.com/igor-gorohovsky/openinference/issues/941)) ([3729e09](https://github.com/igor-gorohovsky/openinference/commit/3729e09ea568b404a331a7f183067052010408ea))


### Bug Fixes

* defer version detection until run time for guardrails-ai ([#1099](https://github.com/igor-gorohovsky/openinference/issues/1099)) ([156b6c1](https://github.com/igor-gorohovsky/openinference/commit/156b6c11b0cbade2b99e37af49a77f4e1af79f84))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-crewai: 0.1.11</summary>

## [0.1.11](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-crewai-v0.1.10...python-openinference-instrumentation-crewai-v0.1.11) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* **crewai:** Add SpanKind and Token Count attributes ([#867](https://github.com/igor-gorohovsky/openinference/issues/867)) ([a61e12a](https://github.com/igor-gorohovsky/openinference/commit/a61e12a43773b933afcce28613db70fcceba43fd))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))


### Bug Fixes

* **crewai:** crewai default empty tasks ([#1682](https://github.com/igor-gorohovsky/openinference/issues/1682)) ([4a47bfc](https://github.com/igor-gorohovsky/openinference/commit/4a47bfc065b88b55bfcb7605abf66ef12a286ec9))
* fix test failures with crew-latest ([#1282](https://github.com/igor-gorohovsky/openinference/issues/1282)) ([e2e3dd1](https://github.com/igor-gorohovsky/openinference/commit/e2e3dd13bf78a3ad4b0d44fc2ae2151127583dce))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* remove token on crewai kickoff chain span ([#1213](https://github.com/igor-gorohovsky/openinference/issues/1213)) ([f015bca](https://github.com/igor-gorohovsky/openinference/commit/f015bca24ce5757e8c7c604487c81889e3e84027))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-haystack: 0.1.25</summary>

## [0.1.25](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-haystack-v0.1.24...python-openinference-instrumentation-haystack-v0.1.25) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))


### Bug Fixes

* CI Failures For Haystack ([#1736](https://github.com/igor-gorohovsky/openinference/issues/1736)) ([673dc40](https://github.com/igor-gorohovsky/openinference/commit/673dc4071845aa3282f9516de6a57d4c92790240))
* **haystack:** ensure compatibility with haystack 2.9 ([#1205](https://github.com/igor-gorohovsky/openinference/issues/1205)) ([6ee2ebf](https://github.com/igor-gorohovsky/openinference/commit/6ee2ebf95c88bf54b2a65dfcc04ab72d8f20a7db))
* **haystack:** ensure haystack is not a runtime dependency ([#959](https://github.com/igor-gorohovsky/openinference/issues/959)) ([c06813c](https://github.com/igor-gorohovsky/openinference/commit/c06813c709331b76b5d65400eca337510d1e7ed3))
* **haystack:** ensure important attributes such as span kind are not lost ([#917](https://github.com/igor-gorohovsky/openinference/issues/917)) ([963ba4a](https://github.com/igor-gorohovsky/openinference/commit/963ba4acf8cc7eaad4a4f780c5e50810fb876c8a))
* **haystack:** fixing ci issues for haystack-ai ([#1623](https://github.com/igor-gorohovsky/openinference/issues/1623)) ([daffa8e](https://github.com/igor-gorohovsky/openinference/commit/daffa8e3fa9825daa76268a91a208b8c77dd1cb1))
* **haystack:** improve heuristic for identifying component type ([#919](https://github.com/igor-gorohovsky/openinference/issues/919)) ([bdfbbdb](https://github.com/igor-gorohovsky/openinference/commit/bdfbbdb9c464ec0c2b730d7d70692ad346ce09f0))
* **haystack:** remove remaining haystack import ([#961](https://github.com/igor-gorohovsky/openinference/issues/961)) ([fe62e3f](https://github.com/igor-gorohovsky/openinference/commit/fe62e3f23c31f88ba99ddab2ca6b453677e7dd31))
* **haystack:** safely get embedding model name ([#965](https://github.com/igor-gorohovsky/openinference/issues/965)) ([3a9286b](https://github.com/igor-gorohovsky/openinference/commit/3a9286b64d62d289d2cbaacb5672e01f4fc6fa3a))
* **haystack:** update haystack for compatibility with 2.10 ([#1295](https://github.com/igor-gorohovsky/openinference/issues/1295)) ([2f6c607](https://github.com/igor-gorohovsky/openinference/commit/2f6c6078e4e1412306bbf954e2f9ad35336f3abc))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/igor-gorohovsky/openinference/issues/1600)) ([076bb79](https://github.com/igor-gorohovsky/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-litellm: 0.1.22</summary>

## [0.1.22](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-litellm-v0.1.21...python-openinference-instrumentation-litellm-v0.1.22) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **liteLLM:** add support for acompletion streaming (resolves [#1224](https://github.com/igor-gorohovsky/openinference/issues/1224)) ([#1246](https://github.com/igor-gorohovsky/openinference/issues/1246)) ([c461b98](https://github.com/igor-gorohovsky/openinference/commit/c461b981da3ad541fcdf991cca01310cc3eab9a8))
* **liteLLM:** Implemented image support and corresponding tests ([#900](https://github.com/igor-gorohovsky/openinference/issues/900)) ([f6d11eb](https://github.com/igor-gorohovsky/openinference/commit/f6d11eb602f37770fbdf7ab144c03980c7f90fb7))
* reasoning, cache, audio token counts litellm ([#1516](https://github.com/igor-gorohovsky/openinference/issues/1516)) ([89fd465](https://github.com/igor-gorohovsky/openinference/commit/89fd465ff432d001fbca9cd3e4cca57bcf476d8a))


### Bug Fixes

* Add support for litellm Message type ([#1308](https://github.com/igor-gorohovsky/openinference/issues/1308)) ([1f2407b](https://github.com/igor-gorohovsky/openinference/commit/1f2407b2047fdf952109520fb010cd6ef6aa96ec))
* Add support for output messages for sync/async ([#1188](https://github.com/igor-gorohovsky/openinference/issues/1188)) ([0bb96b6](https://github.com/igor-gorohovsky/openinference/commit/0bb96b65ebd261445fb63ccc06da49f365dc1fa3))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* **litellm:** display tool_calls from model output ([#1722](https://github.com/igor-gorohovsky/openinference/issues/1722)) ([53c9fa5](https://github.com/igor-gorohovsky/openinference/commit/53c9fa5498135728364d122eefe2bf23ea30b47c))
* **litellm:** full JSON output ([#1735](https://github.com/igor-gorohovsky/openinference/issues/1735)) ([891fc26](https://github.com/igor-gorohovsky/openinference/commit/891fc265cd4a4c5600e7dd261e78ad4ad14e9cc6))
* **litellm:** remove sensitive info from invocation params ([#1571](https://github.com/igor-gorohovsky/openinference/issues/1571)) ([fe4f784](https://github.com/igor-gorohovsky/openinference/commit/fe4f784a020db96f41a2a1f49b1fe8a497369933))
* **liteLLM:** support sync stream ([#1307](https://github.com/igor-gorohovsky/openinference/issues/1307)) ([5c04fa0](https://github.com/igor-gorohovsky/openinference/commit/5c04fa0e10cd95db50e11b1be9afa0f2c3a39aa5))
* Start span before API call ([#1562](https://github.com/igor-gorohovsky/openinference/issues/1562)) ([7d9306b](https://github.com/igor-gorohovsky/openinference/commit/7d9306b2f0654600b0a19c06319895470368fdde))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
* use safe_json_dumps for invocation parameters in litellm instrumentor ([#1269](https://github.com/igor-gorohovsky/openinference/issues/1269)) ([650dbb9](https://github.com/igor-gorohovsky/openinference/commit/650dbb9f83ce7e94329d159819033d8f86e21129))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
* litellm examples ([#681](https://github.com/igor-gorohovsky/openinference/issues/681)) ([b6cfe69](https://github.com/igor-gorohovsky/openinference/commit/b6cfe6933d840b2344b5c132a9d471d239af1c9d))
</details>

<details><summary>python-openinference-instrumentation-groq: 0.1.12</summary>

## [0.1.12](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-groq-v0.1.11...python-openinference-instrumentation-groq-v0.1.12) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* fix groq readme ([#1066](https://github.com/igor-gorohovsky/openinference/issues/1066)) ([5fedc0b](https://github.com/igor-gorohovsky/openinference/commit/5fedc0b451b0da955899a0fcd69ac958cfe38273))
* **groq:** refactor groq, add groq tool call support ([#1133](https://github.com/igor-gorohovsky/openinference/issues/1133)) ([6057418](https://github.com/igor-gorohovsky/openinference/commit/6057418f26ad2cbbb05c122550fcce462c684058))


### Bug Fixes

* groq input messages ([#1053](https://github.com/igor-gorohovsky/openinference/issues/1053)) ([ec7cb4d](https://github.com/igor-gorohovsky/openinference/commit/ec7cb4d01853970a3f604b45b827f37220d70d2e))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-instructor: 0.1.10</summary>

## [0.1.10](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-instructor-v0.1.9...python-openinference-instrumentation-instructor-v0.1.10) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))


### Bug Fixes

* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* instructor output bug fix ([#1549](https://github.com/igor-gorohovsky/openinference/issues/1549)) ([905325f](https://github.com/igor-gorohovsky/openinference/commit/905325f324dd1d8079cebbb169b0b7fc933a8e0c))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-anthropic: 0.1.19</summary>

## [0.1.19](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-anthropic-v0.1.18...python-openinference-instrumentation-anthropic-v0.1.19) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* add README and release please for anthropic instrumentor ([#925](https://github.com/igor-gorohovsky/openinference/issues/925)) ([e8b8973](https://github.com/igor-gorohovsky/openinference/commit/e8b897357d31b2d611c80f4e2d3c5246e87fab1d))
* Anthropic instrumentation ([#878](https://github.com/igor-gorohovsky/openinference/issues/878)) ([895eeee](https://github.com/igor-gorohovsky/openinference/commit/895eeee6c2e7519acf5f0d6e25598d29c4f56925))
* **anthropic:** add llm provider and system attributes to anthropic instrumentation ([#1084](https://github.com/igor-gorohovsky/openinference/issues/1084)) ([32756ed](https://github.com/igor-gorohovsky/openinference/commit/32756ed864849082f9eefc63e7d1fd8ec999d0b3))
* **anthropic:** add stream wrapper and tests ([#1572](https://github.com/igor-gorohovsky/openinference/issues/1572)) ([918aa01](https://github.com/igor-gorohovsky/openinference/commit/918aa017441fd4c8cffdbcaab287913349a41a60))
* **anthropic:** add tool json schema attributes to anthropic instrumentation ([#1087](https://github.com/igor-gorohovsky/openinference/issues/1087)) ([907b6e5](https://github.com/igor-gorohovsky/openinference/commit/907b6e530cb3ded377e99a7cbe7de1f35f55d39f))
* **anthropic:** streaming support ([#990](https://github.com/igor-gorohovsky/openinference/issues/990)) ([f3b7b96](https://github.com/igor-gorohovsky/openinference/commit/f3b7b96b1ddaf7194253e3233b9124c73a19840a))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* instrumentation-anthropic cache token counts ([#1465](https://github.com/igor-gorohovsky/openinference/issues/1465)) ([d6765e0](https://github.com/igor-gorohovsky/openinference/commit/d6765e0edd455fb879ccf0b58ea7d3dfaabeabf0))
* Tool calling for Anthropic instrumentor ([#939](https://github.com/igor-gorohovsky/openinference/issues/939)) ([2566486](https://github.com/igor-gorohovsky/openinference/commit/25664860f6226dcc4a4ef9b19e67fdc79135889b))


### Bug Fixes

* add tool id for anthropic instrumentor and serialize `content` to string if it's not a string ([#1129](https://github.com/igor-gorohovsky/openinference/issues/1129)) ([682724c](https://github.com/igor-gorohovsky/openinference/commit/682724ce436ef8ece5d821073e3845cc3a9d602d))
* **anthropic:** dynamically import anthropic ([#998](https://github.com/igor-gorohovsky/openinference/issues/998)) ([b627f79](https://github.com/igor-gorohovsky/openinference/commit/b627f796afd2d1499c3bcccfbc17567aa7298df8))
* capture anthropic model name from response ([#1124](https://github.com/igor-gorohovsky/openinference/issues/1124)) ([8e915f2](https://github.com/igor-gorohovsky/openinference/commit/8e915f2589764575dea0771284c4ecf3182460ec))
* Fix input message attribute issues + toolcalling from dogfooding ([#948](https://github.com/igor-gorohovsky/openinference/issues/948)) ([dde31f5](https://github.com/igor-gorohovsky/openinference/commit/dde31f51755e5883561d0e9dc195cff13f38f56e))
* include cache tokens in prompt tokens for anthropic ([#1429](https://github.com/igor-gorohovsky/openinference/issues/1429)) ([abd36c4](https://github.com/igor-gorohovsky/openinference/commit/abd36c45ea4ff966b58eccee42de252bc876d5ab))
* increase version lower bound for openinference-instrumentation ([#1012](https://github.com/igor-gorohovsky/openinference/issues/1012)) ([3236d27](https://github.com/igor-gorohovsky/openinference/commit/3236d2733a46b84d693ddb7092209800cde8cc34))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* remove anthropic dependency ([#1094](https://github.com/igor-gorohovsky/openinference/issues/1094)) ([4dd0bba](https://github.com/igor-gorohovsky/openinference/commit/4dd0bba7687f7ab70e0cb973ac588a850a9e99b2))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-smolagents: 0.1.13</summary>

## [0.1.13](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-smolagents-v0.1.12...python-openinference-instrumentation-smolagents-v0.1.13) (2025-06-09)


### Features

* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))
* **smolagents:** add entrypoint for use in opentelemetry-instrument ([#1276](https://github.com/igor-gorohovsky/openinference/issues/1276)) ([7d2af53](https://github.com/igor-gorohovsky/openinference/commit/7d2af53fea2d3b7e03b20cbf056994fddc23d888))
* **smolagents:** support smolagents on python 3.13 ([#1294](https://github.com/igor-gorohovsky/openinference/issues/1294)) ([415f57e](https://github.com/igor-gorohovsky/openinference/commit/415f57e9cdcaf8ad4da8f73043f0fe8e64a7a1e0))
* **smolagents:** updates to latest and makes examples use opentelemetry-instrument ([#1277](https://github.com/igor-gorohovsky/openinference/issues/1277)) ([b151bc9](https://github.com/igor-gorohovsky/openinference/commit/b151bc9a3f8243c846c2981ade94e3d2823602e7))
* working instrumentation with smolagents ([#1184](https://github.com/igor-gorohovsky/openinference/issues/1184)) ([a9b70ed](https://github.com/igor-gorohovsky/openinference/commit/a9b70ed91c21535792202d6a0df4120f6095776d))


### Bug Fixes

* allow prerelease versions of smolagents ([#1416](https://github.com/igor-gorohovsky/openinference/issues/1416)) ([8cd680f](https://github.com/igor-gorohovsky/openinference/commit/8cd680fcb4b7d88a1223f2e07bf1edb038021fac))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* only import exported smolagents models ([#1403](https://github.com/igor-gorohovsky/openinference/issues/1403)) ([e175778](https://github.com/igor-gorohovsky/openinference/commit/e175778252b0cd50d1d1fa20b53547fbf83f74cd))
* **smolagents:** ensure tool attributes are captured successfully on new versions of smolagents ([#1243](https://github.com/igor-gorohovsky/openinference/issues/1243)) ([03f3ceb](https://github.com/igor-gorohovsky/openinference/commit/03f3ceb25a5adfbfc3e1f329782a11ae59fd5b42))
* **smolagents:** include reasoning content ([#1697](https://github.com/igor-gorohovsky/openinference/issues/1697)) ([0c8ea99](https://github.com/igor-gorohovsky/openinference/commit/0c8ea99312874f605e1ab751e38dd13c8b0d4ea0))
* **smolagents:** instrument both __call__ and generate methods for complete model tracing ([8f7049f](https://github.com/igor-gorohovsky/openinference/commit/8f7049ffa9970aede79b6caecbb2ab4e3cf2af8b))
* **smolagents:** instrument both __call__ and generate methods for complete model tracing ([4574383](https://github.com/igor-gorohovsky/openinference/commit/4574383783c58c8c1512e85074864c36fbce90bb))
* **smolagents:** parse string toll call args ([15663c6](https://github.com/igor-gorohovsky/openinference/commit/15663c69501577cbd8fee4b356a9bcd8caea111d))
* **smolagents:** remove redundant smolagents llm output.value causing warning ([#1239](https://github.com/igor-gorohovsky/openinference/issues/1239)) ([23324a4](https://github.com/igor-gorohovsky/openinference/commit/23324a445f7e13c42b0d17bc46c4e7fdd0ed1f55))
* **smolagents:** support new managed agents ([#1274](https://github.com/igor-gorohovsky/openinference/issues/1274)) ([306e1c5](https://github.com/igor-gorohovsky/openinference/commit/306e1c5caf3827433c3a2151b93f7534533bbe94))
* **smolagents:** support only &gt;=1.15.0 version ([8eaecb7](https://github.com/igor-gorohovsky/openinference/commit/8eaecb76598e4ce93c2907dec74466b0ebe2a373))
* **smolagents:** support smolagents nested llm input message contents ([#1238](https://github.com/igor-gorohovsky/openinference/issues/1238)) ([51be5e4](https://github.com/igor-gorohovsky/openinference/commit/51be5e47f4d5ae4ccf43d33a09c3475b56edf784))
* **smolagents:** update internal smolagents import for compatibility with versions post 1.5.0 ([#1229](https://github.com/igor-gorohovsky/openinference/issues/1229)) ([b338113](https://github.com/igor-gorohovsky/openinference/commit/b338113b74433462db6c91d6f96fc8d5b983948d))
* **smolagents:** use correct smolagents tool schema extraction function ([#1236](https://github.com/igor-gorohovsky/openinference/issues/1236)) ([7d764fe](https://github.com/igor-gorohovsky/openinference/commit/7d764fe1aabf1223a177eb60cfde13dec7653417))
* **smolagents:** version-aware method wrapping ([650f4ef](https://github.com/igor-gorohovsky/openinference/commit/650f4ef3322b89576dfbff1ba81241dc96106d53))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-autogen: 0.1.10</summary>

## [0.1.10](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-autogen-v0.1.9...python-openinference-instrumentation-autogen-v0.1.10) (2025-06-09)


### Features

* add entrypoint for use in opentelemetry-instrument ([#1278](https://github.com/igor-gorohovsky/openinference/issues/1278)) ([2106acf](https://github.com/igor-gorohovsky/openinference/commit/2106acfd6648804abe9b95e41a49df26a500435c))
* **autogen2:** basic tool calling ([#1216](https://github.com/igor-gorohovsky/openinference/issues/1216)) ([2a638f7](https://github.com/igor-gorohovsky/openinference/commit/2a638f7ca51a2d77b27a556bed75aa6318aa805b))
* basic instrumentation for autogen (ag2) ([#1211](https://github.com/igor-gorohovsky/openinference/issues/1211)) ([e02a055](https://github.com/igor-gorohovsky/openinference/commit/e02a0553eb84ee253c7931738c5116e0a310194a))
* define openinference_instrumentor entry points for all libraries ([#1290](https://github.com/igor-gorohovsky/openinference/issues/1290)) ([4b69fdc](https://github.com/igor-gorohovsky/openinference/commit/4b69fdc13210048009e51639b01e7c0c9550c9d1))


### Bug Fixes

* **AG2:** CI fix ([#1221](https://github.com/igor-gorohovsky/openinference/issues/1221)) ([db27dfd](https://github.com/igor-gorohovsky/openinference/commit/db27dfd0e9eea601cd7e4b1048fe1d35983de019))
* **autogen2:** tool calling fix ([#1218](https://github.com/igor-gorohovsky/openinference/issues/1218)) ([c8c9ade](https://github.com/igor-gorohovsky/openinference/commit/c8c9ade8267e3ba2fa1e48b2d1d77a42444222e4))
* increased minimum supported version of openinference-instrumentation to 0.1.27 ([#1507](https://github.com/igor-gorohovsky/openinference/issues/1507)) ([a55edfa](https://github.com/igor-gorohovsky/openinference/commit/a55edfa8900c1f36a73385c7d03f91cffadd85c4))
* support python 3.13 and drop python 3.8 ([#1263](https://github.com/igor-gorohovsky/openinference/issues/1263)) ([5bfaa90](https://github.com/igor-gorohovsky/openinference/commit/5bfaa90d800a8f725b3ac7444d16972ed7821738))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))


### Documentation

* fix license to be openinference ([#1353](https://github.com/igor-gorohovsky/openinference/issues/1353)) ([85d435b](https://github.com/igor-gorohovsky/openinference/commit/85d435be3af3de5424494cfbdd654454688b7377))
</details>

<details><summary>python-openinference-instrumentation-beeai: 0.1.7</summary>

## [0.1.7](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-beeai-v0.1.6...python-openinference-instrumentation-beeai-v0.1.7) (2025-06-09)


### Features

* beeai python package ([#1496](https://github.com/igor-gorohovsky/openinference/issues/1496)) ([143b770](https://github.com/igor-gorohovsky/openinference/commit/143b770500e615fb692b3e5f945e8dc22e69c1d1))
* **beeai:** updates so we can run 0.1.19 ([#1576](https://github.com/igor-gorohovsky/openinference/issues/1576)) ([84129f0](https://github.com/igor-gorohovsky/openinference/commit/84129f0212763c96e23961695c4915ec5d14f2f7))
* **python:** update beeai version ([#1552](https://github.com/igor-gorohovsky/openinference/issues/1552)) ([48f04bb](https://github.com/igor-gorohovsky/openinference/commit/48f04bb7fdd03525d7824d9889aebb745d012a5e))
* update beeai framework package ([#1525](https://github.com/igor-gorohovsky/openinference/issues/1525)) ([dc8d128](https://github.com/igor-gorohovsky/openinference/commit/dc8d128042c661babb75b2609bb2f97d155ae9d8))


### Bug Fixes

* beeai python package ([#1522](https://github.com/igor-gorohovsky/openinference/issues/1522)) ([36b50d7](https://github.com/igor-gorohovsky/openinference/commit/36b50d7386f475a13a3665620b95cf4ade4e5ced))
* removes spurious print(2) from python beeai and converts rest to loggers ([#1560](https://github.com/igor-gorohovsky/openinference/issues/1560)) ([038209a](https://github.com/igor-gorohovsky/openinference/commit/038209ab6be0d95181db19c1ae15b244ec7afe0a))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-portkey: 0.1.4</summary>

## [0.1.4](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-portkey-v0.1.3...python-openinference-instrumentation-portkey-v0.1.4) (2025-06-09)


### Features

* portkey chat completions ([#1495](https://github.com/igor-gorohovsky/openinference/issues/1495)) ([0866af3](https://github.com/igor-gorohovsky/openinference/commit/0866af3e9428f59c67704899da37a63cfbef453c))
* **portkey:** Add support for propmt template calls ([#1663](https://github.com/igor-gorohovsky/openinference/issues/1663)) ([c1e813e](https://github.com/igor-gorohovsky/openinference/commit/c1e813e26c62713229958c625c088ffe46ea1608))


### Bug Fixes

* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/igor-gorohovsky/openinference/issues/1567)) ([c2f428c](https://github.com/igor-gorohovsky/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-mcp: 1.4.0</summary>

## [1.4.0](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-mcp-v1.3.0...python-openinference-instrumentation-mcp-v1.4.0) (2025-06-09)


### Features

* **mcp-python:** move instrumentation to transport layer ([#1563](https://github.com/igor-gorohovsky/openinference/issues/1563)) ([2ef9208](https://github.com/igor-gorohovsky/openinference/commit/2ef9208ecdf51e5cf5fba87da20f052ddb198668))
* **mcp:** add instrumentation support for Streamable-HTTP transport and bump mcp dependency to e1.8.1 ([#1640](https://github.com/igor-gorohovsky/openinference/issues/1640)) ([4df8976](https://github.com/igor-gorohovsky/openinference/commit/4df8976066f1911321ee31f7732854787079e981))
* **mcp:** mcp python context propagation ([#1524](https://github.com/igor-gorohovsky/openinference/issues/1524)) ([1af5f7d](https://github.com/igor-gorohovsky/openinference/commit/1af5f7d2e7c78e8fdebf9aaf2e50ccaa74eb6f9a))


### Bug Fixes

* **mcp:** support mcp&gt;=1.8.0 with new SessionMessage structure ([#1634](https://github.com/igor-gorohovsky/openinference/issues/1634)) ([ba6af47](https://github.com/igor-gorohovsky/openinference/commit/ba6af477e97585a41f4a58efcb45890e9bb6c89c))
</details>

<details><summary>python-openinference-instrumentation-google-genai: 0.1.3</summary>

## [0.1.3](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-google-genai-v0.1.2...python-openinference-instrumentation-google-genai-v0.1.3) (2025-06-09)


### Features

* add Google GenAI instrumentation ([#1500](https://github.com/igor-gorohovsky/openinference/issues/1500)) ([1e669a8](https://github.com/igor-gorohovsky/openinference/commit/1e669a8af18bdfd8a0f92f716b49a7f6c105952a))


### Bug Fixes

* google genai with pydantic ([#1724](https://github.com/igor-gorohovsky/openinference/issues/1724)) ([e2ea09a](https://github.com/igor-gorohovsky/openinference/commit/e2ea09a5395f47a5b60ec7961d22114293ebb4f1))


### Documentation

* fix google genai import in README ([#1605](https://github.com/igor-gorohovsky/openinference/issues/1605)) ([60ee275](https://github.com/igor-gorohovsky/openinference/commit/60ee2755fa99a68debbe5e9d84c25b92e99c5e31))
</details>

<details><summary>python-openinference-instrumentation-autogen-agentchat: 0.1.1</summary>

## [0.1.1](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-autogen-agentchat-v0.1.0...python-openinference-instrumentation-autogen-agentchat-v0.1.1) (2025-06-09)


### Features

* **autogen-agentchat:** auto instrumentation ([#1611](https://github.com/igor-gorohovsky/openinference/issues/1611)) ([3c5857c](https://github.com/igor-gorohovsky/openinference/commit/3c5857c2864c3b367888683d1fd470ec631c389f))
</details>

<details><summary>python-openinference-instrumentation-pydantic-ai: 0.1.4</summary>

## [0.1.4](https://github.com/igor-gorohovsky/openinference/compare/python-openinference-instrumentation-pydantic-ai-v0.1.3...python-openinference-instrumentation-pydantic-ai-v0.1.4) (2025-06-09)


### Features

* pydanticai instrumentation ([#1639](https://github.com/igor-gorohovsky/openinference/issues/1639)) ([d8c5b9c](https://github.com/igor-gorohovsky/openinference/commit/d8c5b9cdf793dcce247b2ea852c28eba3a1989bc))


### Bug Fixes

* rename pydantic ai test dir ([#1706](https://github.com/igor-gorohovsky/openinference/issues/1706)) ([d45b00c](https://github.com/igor-gorohovsky/openinference/commit/d45b00cce1d5960e090dac3801a914523fb0355c))


### Documentation

* fix pip install in readme ([#1705](https://github.com/igor-gorohovsky/openinference/issues/1705)) ([4fbad21](https://github.com/igor-gorohovsky/openinference/commit/4fbad21f700325af4cd5d314881ec004a859bdf8))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).