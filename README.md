# 4Peas Research Benchmark Datasets

This repository contains synthetic benchmark datasets prepared for Software Engineering title proposals by the 4Peas group.

## Projects

### TestGuard

A controlled continuous-integration dataset containing 100 synthetic builds and 2,400 test-execution records for evaluating regression-test prioritization methods.

Files are located in `/testguard/`.

### SprintMatch

A synthetic benchmark containing 200 sprint task-assignment scenarios with members, skills, tasks, capacities, priorities, and task-member constraints.

Files are located in `/sprintmatch/`.

### BillSync

A synthetic benchmark containing 200 shared-expense settlement scenarios. Monetary values use integer centavos, expense shares reconcile with their corresponding expenses, and member balances sum to zero within every scenario.

Files are located in `/billsync/`.

## Intended Use

The datasets are intended for software testing and algorithm benchmarking. They are not training datasets for machine-learning models.

## Privacy and Ethics

All records are synthetic. They contain no real names, student numbers, employee records, repository credentials, bank-account numbers, payment credentials, addresses, or personal financial information.

## Data Provenance

The dataset schemas and initial synthetic records were generated with assistance from OpenAI Codex under the direction of the 4Peas group. The group is responsible for reviewing the data, validating the constraints, documenting any modifications, and verifying the results before using them in the study.

## Limitations

The datasets represent controlled benchmark scenarios and must not be described as real company, student, continuous-integration, or household data. Findings should be limited to the evaluated scenarios.

## Group

4Peas  
FEU Institute of Technology  
Software Engineering 1
