## Basic version (required): 4 figures


### Train CQL
- Pick (any) one environment/dataset in d3rlpy (https://github.com/takuseno/d3rlpy)
- Average reward vs training steps (may include different dataset sizes, task difficulties) (10 points)
- True Q vs training steps (may include different dataset sizes, task difficulties) (10 points)
- Estimated Q vs training steps (may include different dataset sizes, task difficulties) (10 points)

### Train OPE (FQE) to evaluate the trained policies
- Estimated Q vs training steps (may include different trained policies, put the true Q in the same figure)

---

- Readme (including installation, get started instructions, citation (d3rlpy)
- Clean source code repository (include colab examples)

```
@InProceedings{seno2021d3rlpy,
  author = {Takuma Seno, Michita Imai},
  title = {d3rlpy: An Offline Deep Reinforcement Library},
  booktitle = {NeurIPS 2021 Offline Reinforcement Learning Workshop},
  month = {December},
  year = {2021}
}
```

## Getting Started
---
#### d3rlpy is an offline deep reinforcement learning library for practitioners and researchers.d3rlpy supports Linux, macOS and Windows (https://github.com/takuseno/d3rlpy)


- PyPI (recommended): `$ pip install d3rlpy`
- Anaconda `$conda install -c conda-forge d3rlpy`