# Contributing Guidelines

Thank you for your interest in contributing to this project! Contributions from the community are more than welcome.

## Contribution Principles

We follow a model inspired by Wikipedia: all contributions must be **based on verifiable sources**.

### What’s accepted:

- Improvements or additions to the traffic density model
- New datasets or day types (e.g., school holidays, strikes)
- Corrections or refinements to speed estimation logic
- Documentation enhancements

## File Structure and Naming

All files must follow the structure:

```
<region>/<country>/<city>.traffic_dens.json
<region>/<country>/<city>.traffic_dens.md
```

### ISO Code Rules

- Use **ISO 3166-1 alpha-2** country codes and region tags:
  - Region: e.g., `eu` for Europe
  - Country: e.g., `es` for Spain
  - City: use **English name** (e.g., `barcelona`)

### Required Files

Every JSON file must be accompanied by a corresponding `.md` file with the **same path and filename**, containing all **APA 7th edition citations** used.

Example:

```
eu/es/barcelona.traffic_dens.json # Traffic density and speed data
eu/es/barcelona.traffic_dens.md # APA-formatted source documentation
```

> Contributions that do not follow this structure may be rejected or requested to be revised.

## Citation Requirement

Every update must be **justified by an APA 7th edition citation**, either:

- A **reliable public dataset**
- An **academic publication** or transportation study
- A **government or city council source**

> Contributions **without a source will not be merged**.

## How to Contribute

1. Fork this repository
2. Create a branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new traffic profile [source: ...]'`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a pull request, clearly describing the reasoning and source for the change

Thank you for helping improve the quality and reliability of open mobility data in Barcelona and beyond!

## Disclaimer

This dataset and its accompanying documentation have been developed by the community based on real, up-to-date, and verified data sources (public datasets, academic publications, and official institutions). 

However, **we (the community) do not assume any legal responsibility or liability** for any errors, omissions, or inaccuracies that may exist in the data files, nor for the consequences of their use in simulations, planning, or decision-making processes.

> Always cross-check critical data with official and primary sources.
