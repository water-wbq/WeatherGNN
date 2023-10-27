# WeatherGNN
WeatherGNN: Exploiting Complicated Relationships in Numerical Weather Prediction Bias Correction
[[paper]](https://arxiv.org/abs/2310.05517) [[code]](https://anonymous.4open.science/r/WeatherGNN-D6DB)

## Abstract
Numerical weather prediction (NWP) may be inaccurate or biased due to incomplete atmospheric physical processes, insufficient spatial-temporal resolution, and inherent uncertainty of weather. Previous studies have attempted to correct biases by using handcrafted features and domain knowledge, or by applying general machine learning models naively. They do not fully explore the complicated meteorologic interactions and spatial dependencies in the atmosphere dynamically, which limits their applicability in NWP bias-correction. Specifically, weather factors interact with each other in complex ways, and these interactions can vary regionally. In addition, the interactions between weather factors are further complicated by the spatial dependencies between regions, which are influenced by varied terrain and atmospheric motions. To address these issues, we propose WeatherGNN, an NWP bias-correction method that utilizes Graph Neural Networks (GNN) to learn meteorologic and geographic relationships in a unified framework. Our approach includes a factor-wise GNN that captures meteorological interactions within each grid (a specific location) adaptively, and a fast hierarchical GNN that captures spatial dependencies between grids dynamically. Notably, the fast hierarchical GNN achieves linear complexity with respect to the number of grids, enhancing model efficiency and scalability. Our experimental results on two real-world datasets demonstrate the superiority of WeatherGNN in comparison with other SOTA methods, with an average improvement of 40.50\% on RMSE compared to the original NWP.

## Citation
```
@misc{wu2023weathergnn,
    title={WeatherGNN: Exploiting Complicated Relationships in Numerical Weather Prediction Bias Correction}, 
    author={Binqing Wu and Weiqi Chen and Wengwei Wang and Bingqing Peng and Liang Sun and Ling Chen},
    year={2023},
    eprint={2310.05517},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```
