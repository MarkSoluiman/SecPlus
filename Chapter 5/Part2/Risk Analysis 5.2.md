
---

## Qualitative Risk Assessment

This is used by identifying significant risk factors and display visually with traffic light grid or similar method.

For example:

| Risk Description                 | Likelihood | Impact | Risk Rating | Status   |
| -------------------------------- | ---------- | ------ | ----------- | -------- |
| Phishing email attack            | High       | High   | 🔴 Critical | Mitigate |
| Unpatched software vulnerability | Medium     | High   | 🟠 Major    | Monitor  |
| Accidental data deletion         | Medium     | Medium | 🟠 Moderate | Mitigate |
| Power outage in office           | Low        | High   | 🟠 Moderate | Accept   |
| Staff forgetting passwords       | High       | Low    | 🟢 Minor    | Accept   |

It is designed to give organizations a high level view of where they might focus their efforts to resolve these problems. 

## Quantitative Risk Assessment  

There are certain risks where organizations can calculate a specific value.  This type of risk assessment starts with **Annualized Rate of Occurrence (ARO)** which calculates how likely an event will happen in a single year. 

After that comes the **Asset Value (AV)** which calculates the value of the asset affected by that risk for the organization. 

After that comes the **Exposure Factor (EF)** which calculates the percentage of the value lost due to an incident. For example, losing a quarter of the value is 0.25. Losing the entire asset is 1.0. 

Organizations can calculate a quantitative risk assessment based on some of the previous variables mentioned.  One way to do it is called **Single Loss Expectancy (SLE)**=**AVx EF** . For example, what is the monetary loss if a single event occurs (laptop stolen): $1000 (AV) x 1.0 (EF)= $1000 (SLE).

To get the bigger picture, organizations can then calculate the **Annualized Loss Expectancy (ALE)**=**AROxSLE**. For example, seven laptops are stolen each year: 7(ARO) x $1000 (SLE)= $7000.

## Impact

Organizations have to consider these areas when it comes to what will be impacted by a risk.

1. Life. (most important aspect)
2. Property: the risk to buildings and assets.
3. Safety.
4. Finance: the resulting finance result.

## Risk Appetite and Tolerance 

Risk appetite is a broad description of risk-taking deemed acceptable. The amount of accepted risk before taking any action to reduce that risk.

Some organizations will set a qualitative value on this appetite. This is refereed to as a risk appetite posture. The posture can be conservative, neutral, and expansionary. 

Risk tolerance is an acceptable variance  from the risk appetite and is usually larger.

## Risk Register

Every project has a plan, but also has risk. Risk register identifies and documents the risk associated with each step. Applies possible solutions to the identified risks and monitors the results. 

Risk registers have **key risk indicators** to identify risks that could impact the organization. Each key risk indicator has a **risk owner** to manage the risk.

**Risk threshold** is the cost of mitigation which is at least equal to the value gained by mitigation. (The amount spent to mitigate the risk vs the amount the company will endure if that risk happened).

