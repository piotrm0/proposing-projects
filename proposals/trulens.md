# TruLens-Eval Project Proposal

**Name of project**: TruLens-Eval

**Requested project maturity level:** Incubation

**Project description:**

Trulens allows users to create credible and powerful LLM apps, faster. TruLens is a software tool that helps you to objectively measure the quality and effectiveness of your LLM-based applications using feedback functions. Feedback functions help to programmatically evaluate the quality of inputs, outputs, and intermediate results, so that you can expedite and scale up experiment evaluation. Use it for a wide variety of use cases including question answering, summarization, retrieval-augmented generation, and agent-based applications.

**Statement on alignment with LF AI’s mission:**

Trulens allows users to evaluate their LLM applications. LLMs and LLM applications align directly with the mission of the LF AI & Generative AI Commons to foster open collaboration and ecosystem improvements in AI and Generative AI.

**Have you identified possible collaboration opportunities with current LF AI hosted projects (https://lfai.foundation/projects/)?**

- Acumos AI

- Adversarial Robustness Toolbox - Integrate robustness measures into TruLens' evaluation toolbox.

- AI Explainability 360

- AI Fairness 360

- CLAIMED

- IntersectionalFairness (ISF) - Integrate bias measures into TruLens'
  evaluation toolbox.

- Ludwig

- Milvus: Trulens can evaluate LLM context stored on the Milvus vector DB.
  
- ForestFlow: serve LLMs that can be queried by Trulens.
  
- JanusGraph: Trulens can evaluate LLM context store in JanusGraph.

LF Projects outside of LF AI:

- (CNCF) opentelemetry, especially the Semantic Conventions for
  AI (sub)project.

Note. Since the space is evolving fast there will likely be collaborations with other open source projects that are not part of the LF. In the future some of this project could become part of the LF.

**License name**

MIT License

**Source control (GitHub, etc.)**

https://github.com/truera/trulens

**Issue tracker (GitHub, JIRA, etc)**

We use the github issues for checking issues and feature
requests([link](https://github.com/truera/trulens/issues)).

**Collaboration tools (mailing lists, wiki, IRC, Slack, Glitter, etc.)**

Slack: `aiqualityforum.slack.com` channel `#trulens-dev`

**External dependencies including licenses (name and version) of those dependencies**

Several python packages enumerated in `requirements.txt`.

**Initial committers (name, email, organization) and how long have they been working on project**

- Aaron Varghese, Truera, 2 months
- Corey Hu, Truera,, 1.5 years
- Daniel Huang Truera,, 1.5 years
- Garett Tok, Truera,, 1.5 years
- Josh Reini, Truera, 1.5 years
- Piotr Mardziel, Truera, piotrm@truera.com, 1.5 years
- Rick Shih, (then) Truera,, 1.5 years
- Shayak Sen, Truera,, 1.5 years

**Have the project defined the roles of contributor, committer, maintainer, etc**

We don’t have this doc yet, but will add `MAINTAINERS.md` in the future.

**Total number of contributors to the project including their affiliations**

trulens: https://github.com/truera/trulens/graphs/contributors (40)

**Does the project have a release methodology**

Python package on PyPi (Release approximately every week).

Docs on https://www.trulens.org/trulens_eval/getting_started/

Release cadence is described in `RELEASES.md`.

**Does the project have a code of conduct**

No.

**Do you have any specific infrastructure requests needed as part of hosting the project in the LF AI?**

Travis-ci testing (or similar).

**Project website**

- Homepage: https://www.trulens.org

- Documentation: https://www.trulens.org/trulens_eval/getting_started/

**Project governance**

No.

**Social media accounts**

- twitter: `@TruLensML`

**Existing sponsorship**

Truera started the project.