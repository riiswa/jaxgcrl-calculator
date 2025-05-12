# JaxGCRL Configuration Calculator

A web-based tool for calculating and validating configuration parameters for the [JaxGCRL framework](https://github.com/MichalBortkiewicz/JaxGCRL).

## About This Tool

This calculator helps users avoid common configuration errors when setting up reinforcement learning experiments with JaxGCRL. It validates that your settings satisfy critical constraints, particularly the divisibility requirements that can cause reshape errors during training.

Features:
- Validates divisibility constraints between `num_envs`, `episode_length`, and `batch_size`
- Calculates total environment steps that will be executed
- Computes the Update-to-Data (UTD) ratio for your configuration
- Shows number of complete episodes per environment
- Warns about potential issues with your configuration

## What is JaxGCRL?

[JaxGCRL](https://github.com/MichalBortkiewicz/JaxGCRL) is a framework for accelerating goal-conditioned reinforcement learning research and experiments. It provides:

- Fast goal-conditioned environments based on MJX and BRAX
- Support for training reinforcement learning algorithms up to 22× faster than prior implementations
- A comprehensive set of environments and pre-implemented baselines

## Development Note

This calculator was created with the assistance of a large language model. It is not an official tool developed by the authors of JaxGCRL.
