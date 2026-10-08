# PReSto HoloceneDA baseline: Temperature 12k v1.0.2

The comparison run for
[presto-HoloceneDA-run-2026-10-08](https://github.com/paleopresto/presto-HoloceneDA-run-2026-10-08):
the same template code and the same Erb et al. (2022) settings, run on the
data Erb et al. (2022) assimilated.

- `query_params.json` (`mode: bundle`): Temperature 12k v1.0.2 exactly as
  LiPDverse released it (698 datasets), re-published as
  [baseline-temp12k-1_0_2](https://github.com/paleopresto/presto-recipes/releases/tag/baseline-temp12k-1_0_2)
  because lipdverse.org's incomplete TLS chain breaks the template's archived
  mode on GitHub runners. The DA's own selection (degC records) applies.
- `config/user_config.yml`: Erb et al. (2022)'s upstream defaults, from
  presto-recipes `runs/presto-HoloceneDA/temp12k-1_0_2/`.
- The workflow: the template's `pool-bundles` branch until merged upstream.
