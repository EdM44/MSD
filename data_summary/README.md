1)	allgcms_historical_ann_avg_1970-1999_annual.csv annual avg. rainfall for each gcm
2)	allgcms_mean_historical_1970-1999_annual.csv annual avg. rainfall for averaged across all gcms
3)	allgcms_historical_\<index\>_1970-1999_stats.csv
  index is one of: duration, intensity, minimum, or the magnitude of onset peak rainfall. Contains index value for each gcm
4)	allgcms_mean_historical_1970-1999_stats.csv
  same as file 3, but averaged across all gcms, and with all indices in one file
5)	allgcms_\<scenario\>\_meanchange\_\<period\>_annual.csv
  mean change, across all gcms, in precipitation for the scenario and period, compared to 1970-1999. Includes Wilcoxon p-value 
  for significance of change. Scenario is either rcp45 or rcp85
6)	allgcms_\<scenario\>\_meanchange\_\<period\>_stats.csv
  mean change, across all gcms, in 4 key statistics for the designated scenario and period compared to 1970-1999. 
  Statistics are: onset day, end day, duration, intensity, min. Each is followed by its associated Wilcoxon p-value
7)	obs_historical_pr_1970-1999_stats.csv mean and standard deviation for observed precipitation for indices: 
  onset max, onset day, end max, end day, min, duration, intensity

Please refer to the paper for additional details
