# BeibuGulf-Pilotage-Dataset
Anonymized operational dataset from Beibu Gulf Port (Qinzhou, Fangcheng, Beihai) for multi-port pilotage scheduling research
# Beibu Gulf Port Pilotage Scheduling Instances

This repository contains all synthetic test instances used in the paper:

**"A Hybrid Reinforcement Learning and NSGA-II Approach for Multi-Port Pilotage Allocation and Scheduling"**

### Dataset Description

All instances in this repository are **synthetically generated** based on:
- Publicly available statistical information of Beibu Gulf Port (Guangxi, China)
- Official port regulations (e.g., pilot work-number limits at Qinzhou Port, working-hour limits at Fangcheng and Beihai Ports)
- Realistic vessel arrival patterns and pilotage operational characteristics

**Note**: These are **not raw operational data**. No real vessel names, pilot identities, or sensitive commercial information are included.

### Repository Structure

- `/instances/` — All test instances used in the case study  
- `/generation_code/` — Python scripts used to generate the instances (optional)  
- `/docs/` — Data dictionary and generation method

### Instance Naming Convention

Instances are named in the format:  
`{total_tasks}_{total_pilots}_{instance_id}.txt`

Examples:
- `20_20_1.txt` : 20 tasks, 20 pilots, instance 1
- `60_40_1.txt` : 60 tasks, 40 pilots, instance 1
- `90_55_1.txt` : 90 tasks, 55 pilots, instance 1
