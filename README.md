## Multimode Power Oscillation Damping Controller Synthesis using Vector Fitting

[![DOI](https://zenodo.org/badge/626350503.svg)](https://zenodo.org/badge/latestdoi/626350503)

This repository contains the files used for the work presented in the IEEE PowerTech 2023 conference. It includes files used for designing the power oscillation damping controller using vector fitting method.

### Project Structure

The repository is structured as follows:

- [`results/`](./results) This folder contains the results presented in the paper, organized into five subfolders:
  - [`controller_active_power/`](./results/controller_active_power) Frequency response of $C_P(s)$
  - [`controller_reactive_power/`](./results/controller_reactive_power) Frequency response of $C_Q(s)$
  - [`plant_active_power/`](./results/plant_active_power) Frequency response of $P_P(s)$
  - [`plant_reactive_power/`](./results/plant_reactive_power) Frequency response of $P_Q(s)$
  - [`system_closed_loop/`](./results/system_closed_loop) System transient response without and with POD controller.

Each folder for frequency response includes the transfer function frequency response in the range from 10<sup>-4</sup> to 10<sup>4</sup> Hz. The most relevant points in the frequency response are saved in *_points* file.

### Citing the Paper

If you use these results in your own research or publication, please cite our paper.

### Contributors

- [Njegos Jankovic](https://orcid.org/0000-0003-3358-069X)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
- [Javier Roldan Perez](https://orcid.org/0000-0002-9759-4006)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
- [Milan Prodanovic](https://orcid.org/0000-0001-5500-9799)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
- [Jon Are Suul](https://orcid.org/0000-0003-3491-636X)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
- [Salvatore D'Arco](https://orcid.org/0000-0002-9313-8230)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
- [Luis Rouco Rodrigez](https://orcid.org/0000-0002-2670-7464)<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />

### License

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
