sequenceDiagram
  autonumber
  TSKG->>+TIS: 1次問い合わせ
  Server--)SWX: AWSサポートへの問い合わせ
  Server-->>-Client: アプリケーション関係ならTISで回答
  社内処理
    Server2-->Server2: なにかしら
    Note right of Server2: #techで<br/>確認する
  end
