# TorchWeather
A benchmark for large-scale data-driven methods in climate prediction


## Baselines

| Method        | Title                                                                                                   | Year | Institution | Paper                                                  | Code                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------- | ---- | ----------- | ------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| FourCastNet   | FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators | 2022 | Nvidia      | [Arxiv](https://arxiv.org/abs/2202.11214)              | [GitHub](https://github.com/NVlabs/FourCastNet)                                           |
| PanGu Weather | Pangu-Weather: A 3D High-Resolution Model for Fast and Accurate Global Weather Forecast                 | 2022 | Huawei      | [Arxiv](https://arxiv.org/abs/2211.02556)              | [GitHub](https://github.com/198808xc/Pangu-Weather)                                       |
| ClimaX        | ClimaX: A foundation model for weather and climate                                                      | 2023 | Microsoft   | [Arxiv](https://arxiv.org/abs/2301.10343)              | [GitHub](https://github.com/microsoft/ClimaX)                                             |
| ClimODE       | ClimODE: Climate Forecasting With Physics-informed Neural ODEs                                          | 2023 | Unknown     | [OpenReview](https://openreview.net/pdf?id=xuY33XhEGR) | [OpenReview](https://openreview.net/attachment?id=xuY33XhEGR&name=supplementary_material) |


## Bug Fixing

- error: parameter packs not expanded with ‘...’:
    [Solution](https://github.com/NVIDIA/apex/issues/1491)
