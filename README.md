# Understanding-and-Enhancing-NAIRR-Utilization
Understanding and Enhancing NAIRR Utilization: Allocation, Usage Patterns, and Data-Informed Resource Management

## Waste Coefficent Analysis

### Job Based Analysis
<img width="552" height="357" alt="Waste Coefficient Per Job" src="https://github.com/user-attachments/assets/f9dea5fa-67c0-486d-b9c6-1bf03500c712" />

By looking at our total resource capacity wasted we see that waste is not a linear function of job count. Instead, the "steps" in the early stages of the curve indicate that a minority of massive projects are responsible for the vast majority of the downward trend.

<img width="638" height="496" alt="Concentration of Resource Waste on ACCESS" src="https://github.com/user-attachments/assets/9030014c-c24a-4bc5-82f0-84437bbc74ed" />

By applying a Pareto analysis (80/20 rule) to ACCESS job data, we indentified that a small fraction of projects drive the majority of system waste.

<img width="638" height="379" alt="Project Allocation Pareto Review" src="https://github.com/user-attachments/assets/9aa18978-8aa7-4e58-a2ce-8f675431cf0c" />

Results: 8.29% of projects are responsible for 80% of the system waste


### Project Based Analysis

<img width="638" height="395" alt="Project-Level Allocation Waste Coefficient" src="https://github.com/user-attachments/assets/ed452a88-d24a-4acd-9dbe-9dcd60079c1b" />

This Used vs. Blocked SU analysis reveals the 'Allocation Gap'—identifying specific projects that over-reserve capacity and contribute disproportionately to system-wide idle time.

## GPU Utilization Audit

<img width="638" height="420" alt="GPU Utilization Audit" src="https://github.com/user-attachments/assets/9297db54-b7ec-4f8e-9caf-78f19058bcc1" />

The data is dominated by a sharp density spike at 0% GPU activity. This “Zero-Spike” indicates that a significant portion of the hardware allocation is consumed by jobs that are active in the scheduler but idle on the silicon.

## Systematic Institutional Analysis and Tiered Recovery Policies

<img width="657" height="395" alt="System-Wide Efficiency Crisis 2" src="https://github.com/user-attachments/assets/65eec4a4-42a0-4a44-9022-26a5f2c43a93" />

A negligible percentage of jobs meet or exceed a 40% efficiency threshold. This data reinforces the “Request-Reality Gap,” demonstrating that the current allocation culture lacks any significant incentive for accuracy.
