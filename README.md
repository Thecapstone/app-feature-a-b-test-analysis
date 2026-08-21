# App Feature A/B Test Analysis
## Final capstone project submission for the 3mtt Data Science Track. 
- The project focuses on elucidating the effect of modifying an app feature on user behaviour and engagement.
- The analysis is based on an a/b style deployment of the app.

## 📖📝Project breakdown and Analysis conclusion

The objective of this analysis was to determine whether moving the *Cookie Cats* progression gate from level 30 to level 40 improved player engagement and retention.

Overall, the two experimental groups displayed broadly similar engagement behaviour, suggesting that changing the position of the gate did not produce a substantial overall change in the number of game rounds played.

A much clearer result emerged for longer-term retention. Day-7 retention was approximately **19.02% for `gate_30` compared with 18.20% for `gate_40`**, representing a treatment effect of approximately **-0.82 percentage points**.

The two-proportion z-test produced a **p-value of 0.00159**, below the selected significance level of 0.05. The null hypothesis of equal Day-7 retention rates was therefore rejected. The experiment provides statistically significant evidence that moving the gate to level 40 was associated with lower Day-7 retention.

The exploratory analysis also revealed a strong relationship between player engagement and retention. Players retained after one and seven days played substantially more game rounds than non-retained players. Day-7 retained users recorded a median of **108 rounds**, compared with only **11 rounds** among users who were not retained.

When players were divided into engagement groups, retention increased substantially with engagement under both experiment variants. The overall pattern remained broadly similar between `gate_30` and `gate_40`, indicating that engagement level was more strongly associated with retention than gate placement itself. However, the highest-engagement groups showed somewhat larger reductions in Day-7 retention under `gate_40`; this observation requires additional statistical testing before it can be considered a confirmed treatment interaction.

### 🙏🙂Recommendation based on analysis

Based on the available evidence, the analysis does **not support moving the progression gate from level 30 to level 40**.

The treatment failed to demonstrate a clear improvement in overall engagement and produced a statistically significant reduction in Day-7 retention. Therefore, if retention is the primary product objective, **`gate_30` should be retained**.

Future experiments could investigate alternative gate positions or gate mechanics and collect more detailed behavioural data, such as session frequency, level progression, time spent in the game, purchases, and events immediately before and after encountering the gate. This would provide greater insight into *why* gate placement influences player retention rather than only identifying whether an effect exists.

