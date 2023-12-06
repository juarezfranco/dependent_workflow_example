# Sample Project

This is a sample project created to demonstrate GitHub Actions workflows and their interaction.

## Overview

This repository contains example workflows showcasing how workflows in GitHub Actions can be triggered based on events and how one workflow can trigger another upon completion.

## Workflows

### `main_workflow.yml`

The `main_workflow.yml` is triggered on a push event to the `main` branch. It executes a simple job as a demonstration.

### `triggered_workflow.yml`

The `triggered_workflow.yml` is set up to be triggered when the `main_workflow.yml` is completed successfully. It showcases how a workflow can respond to the completion of another workflow.

## Purpose

The primary purpose of this repository is to serve as a learning resource for understanding GitHub Actions and how workflows can be configured and chained together based on events.

## Usage

Feel free to explore the workflows in this repository and use them as a reference for setting up your own workflows in GitHub Actions.

## Contribution

Contributions to enhance or expand the example workflows are welcome. If you have any suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
