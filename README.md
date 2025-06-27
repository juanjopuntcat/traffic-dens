# Traffic Density Data

This repository provides estimated traffic density profiles and vehicle speed models for **cities** and their **metropolitan areas**, with a resolution of **30-minute intervals** and differentiated by day type. The aim of this project is to grow on how many cities and regions are available. Contributions from the community are more than welcome, having in mind that every update must be justified by an APA citation, more or less like Wikipedia does.

## Repository Structure

``
    traffic-dens/
        ├── *region*
        │ └── *country*
        │   ├── *city*.traffic_dens.json # JSON dataset with densities and average speeds
        │   └── *city*.traffic_dens.md # APA-sourced documentation in Markdown
        ├── LICENSE
        └── README.md
``

## Dataset Overview

- **Files**: `city.traffic_dens.json`
- **Resolution**: Every 30 minutes, 24h/day
- **Scenarios**: Weekday, Saturday, Sunday, public holiday, holiday eve, bridging workday
- **Data Includes**:
  - Normalized traffic **density**
  - Estimated **average speeds** by road type:
    - `pedestrian_zone` (limit: 10–20 km/h)
    - `urban_street` (30 km/h)
    - `main_road` (50 km/h)
    - `beltway` (60–80 km/h)
    - `highway` (100–120 km/h)


## Documentation

See `city.traffic_dens.md` for full APA 7th edition references used to construct this model. Data is based on:

- Public data from many open data sources, public and private
- Academic literature and traffic simulation models
- Dynamic speed logic based on density for realistic simulation and planning


## Usage Ideas

- Urban mobility simulation
- Transportation infrastructure planning
- Smart city dashboards
- Public policy evaluation

## Disclaimer

This dataset and its accompanying documentation have been developed by the community based on real, up-to-date, and verified data sources (public datasets, academic publications, and official institutions). 

However, **we (the community) do not assume any legal responsibility or liability** for any errors, omissions, or inaccuracies that may exist in the data files, nor for the consequences of their use in simulations, planning, or decision-making processes.

> Always cross-check critical data with official and primary sources.

## License

Distributed under the [GNU General Public License v3.0](LICENSE).
