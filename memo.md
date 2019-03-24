
- Autoscalerは実際の負荷を見ていない
-> RequestsとLimitsを適切に設定しないといけない
-> GKEはdefaultRequestが用意されている

- HorizontalPodAutoscalerはコンテナをスケール（アウト）させる -> Podのレプリカ数増減
- VerticalPodAutoscalerはPodをスケールアップ -> Podに割り当てられるリソースの増減
  