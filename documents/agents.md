```mermaid
graph TD;
    A(Start)-->B[論文収集]
    B-->C[論文要約]
    C-->D[内容チェック]
    D-->E[Slack投稿原稿の作成]
    E-->F[チャンネルで共有]
    F-->G(End)
    D-->|必要に応じて再度収集|B
```
