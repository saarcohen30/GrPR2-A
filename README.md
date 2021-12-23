# Attentive Graph Probabilistic Reasoning (GrPR2-A)
Code for implementation of Attentive Graph Probabilistic Recursive Reasoning (**<em>GrPR2-A</em>**). Specifically, GrPR2-A constitutes an extension of [FlowComm](https://www.ifaamas.org/Proceedings/aamas2021/pdfs/p456.pdf), supporting level-1 recursive reasoning <em>with communication</em>. FlowComm embeds a graph reasoning policy into [MAAC](http://proceedings.mlr.press/v97/iqbal19a.html), which trains decentralized policies in multiagent settings, using <em>centrally</em> computed critics that share an attention mechanism, selecting relevant information for each agent.
If any part of this code is used, the following paper must be cited: 

**Saar Cohen and Noa Agmon. Optimizing Multi-Agent Coordination via Hierarchical Graph Probabilistic Recursive Reasoning. <em>In AAMAS'22: Proceedings of the 21th International Conference on Autonomous Agents and Multiagent Systems, 2022</em> (to appear).**

## Dependencies
Evaluations were conducted using a 12GB NVIDIA Tesla K80 GPU, and implemented in Python3 with:
- PyTorch v2.6.0 (The implementation appears [here](https://github.com/saarcohen30/GrPR2-A/tree/main/grpr2-a-colab)).
- PyTorch v1.12.0, which is suitable for environment without support of higher versions of PyTorch (The implementation appears [here](https://github.com/saarcohen30/GrPR2-A/tree/main/grpr2-a)).

## Concept


## Execution

