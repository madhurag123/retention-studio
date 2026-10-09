# Publication record

Copied into `madhurag123/retention-studio` on 2026-10-09 at the owner's request. Original source repositories and remotes were not changed. Existing commit authors, copyright notices, data provenance and third-party licenses are retained; a repository copy does not transfer authorship.

- Source: https://github.com/abhijith-abhii/retention-studio
- Source revision: `6b9b448486f2127cd0be219e2f1486108b3cc806`
- Implementation status: implemented; recorded checks passed.
- Publication checks: Local automated checks passed on 2026-10-09. Scope: see the recorded check command and output below.
- This upload does not deploy cloud infrastructure or enable paid integrations.

## Evidence and limitations

Existing screenshots, sample outputs and test reports describe the original implementation and the dates recorded in those files. Links to original CI runs deliberately retain their original account because those runs happened there. They are not claims of new destination-account CI results. Follow the README for installation, dependencies, sample data and limitations. Any new CI results are available in this repository's Actions tab.

Development used substantial AI assistance. Present the work as a project you can run and explain, with its retained provenance, rather than employment experience or verified production adoption.

## Publication check record

```text
.......................                                              [100%]
=============================== warnings summary ===============================
tests/test_data_model.py::test_invalid_inputs_rejected[<lambda>7]
  <workspace>/outputs/madhurag123-projects/retention-studio/src/retention/data.py:50: FutureWarning: Downcasting behavior in `replace` is deprecated and will be removed in a future version. To retain the old behavior, explicitly call `result.infer_objects(copy=False)`. To opt-in to the future behavior, set `pd.set_option('future.no_silent_downcasting', True)`
    df[col] = df[col].replace("", np.nan)

tests/test_data_model.py: 6 warnings
tests/test_web.py: 3 warnings
tests/test_workflow.py: 30 warnings
  <workspace>/work/clean-envs/retention-studio/lib/python3.12/site-packages/sklearn/utils/extmath.py:203: RuntimeWarning: divide by zero encountered in matmul
    ret = a @ b

tests/test_data_model.py: 6 warnings
tests/test_web.py: 3 warnings
tests/test_workflow.py: 30 warnings
  <workspace>/work/clean-envs/retention-studio/lib/python3.12/site-packages/sklearn/utils/extmath.py:203: RuntimeWarning: overflow encountered in matmul
    ret = a @ b

tests/test_data_model.py: 6 warnings
tests/test_web.py: 3 warnings
tests/test_workflow.py: 30 warnings
  <workspace>/work/clean-envs/retention-studio/lib/python3.12/site-packages/sklearn/utils/extmath.py:203: RuntimeWarning: invalid value encountered in matmul
    ret = a @ b

-- Docs: https://docs.pytest.org/en/stable/how-to/capture-warnings.html
27 passed, 118 warnings in 1.75s


```
