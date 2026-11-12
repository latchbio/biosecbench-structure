# BioSecBench-Structure

**Benchmarking the structural reasoning of AI agents for pathogen risk assessment and countermeasure design**

BioSecBench-Structure tests whether AI agents can correctly reason about 3D structures of pathogen proteins that guide the design of vaccines, antibodies and antiviral drugs. Tasks include identifying the metal ions in a viral enzyme before antiviral design, finding which parts of a viral surface protein an antibody can reach, and confirming whether a candidate drug is really bound. Each pairs real structural data with a specific analysis question and a verifiable answer. Scores show the share of attempts that reach the correct answer, counting refusals and errors as failures. A higher score means the model is more accurate at these tasks.

In this repo, there are 3 public tasks that DO NOT APPEAR in the benchmark, but mimic benchmark like questions.

## License

Apache 2.0 - see [LICENSE](LICENSE).
