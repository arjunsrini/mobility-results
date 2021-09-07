# US educational mobility

## Results (Normal Fits)

Time series plots — outcome across birth cohorts, by gender:
- [E[Y>=25\|X<50]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_25_0_50_ts.png)
- [E[Y>=80\|X<20]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_80_0_20_ts.png)
- [E[Y\|X<50]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_Y_0_50_ts.png)

Same outcomes across birth cohorts, by gender and race:
- [E[Y>=25\|X<50]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_25_0_50_br_ts.png)
- [E[Y>=80\|X<20]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_80_0_20_br_ts.png)
- [E[Y\|X<50]](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/sim_ts/E_Y_0_50_br_ts.png)

## Robustness Checks

| Parent, Kernel    | Bottom Half Mobility |
|-------------------|:--------------------:|
| Mother, Normal    |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_norm.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_norm_by_race.png)         |
| Mother, Lognormal |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_lnorm.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_lnorm_by_race.png)         |
| Mother, Uniform   |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_unif.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_unif_by_race.png)         |
| Mother, Triangle  |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_tri.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/mom_tri_by_race.png)         |
| Father, Normal    |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_norm.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_norm_by_race.png)         |
| Father, Lognormal |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_lnorm.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_lnorm_by_race.png)         |
| Father, Uniform   |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_unif.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_unif_by_race.png)         |
| Father, Triangle  |         [plot](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_tri.png) [plot_by_race](https://media.githubusercontent.com/media/arjunsrini/mobility-results/main/figs/k/dad_tri_by_race.png)         |

## Confidence Checks by Dataset

Each point in those time series plots is associated with a dataset/birth cohort. 
Below are pages with confidence checks that show how we went from the raw dataset to the estimated point.
To go from point to page, find the year associated with the point, then click the link below that start's with that year.

- [Year: 1920, Data: 1940 Census, Birth Cohort: 1920-25](./c1940.md)
- [Year: 1947, Data: NLS66, Birth Cohort: 1942-52](./nls66.md)
- [Year: 1960, Data: NLSY79, Birth Cohort: 1957-64](./nlsy79.md)
- [Year: 1965, Data: PSID (2015), Birth Cohort: 1960-69](./psid15_60.md)
- [Year: 1975, Data: PSID (2015), Birth Cohort: 1970-79](./psid15_70.md)
- [Year: 1980, Data: 2000 Census, Birth Cohort: 1978-83](./c2000.md)
- [Year: 1982, Data: NLSY97, Birth Cohort: 1980-84](./nlsy97.md)
- [Year: 1985, Data: PSID (2015), Birth Cohort: 1980-89](./psid15_70.md)

## [Old](./old)
