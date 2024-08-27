## Azure Virtual Desktop の監視のためのカスタム KQL
Azure Virtual Desktop において ユーザーごとの任意のセッションホストに対する稼働時間かつセッションホストのある時間幅の起動時間を可視化
* ユーザーのあるセッションホスト上での稼働時間の割合を ユーザー稼働時間/セッションホスト稼働時間で導出
* ユーザーごとのコストの詳細な配賦も割合によって導出可能

**getRatioUserTimeOnVMs.kql:**
![image](https://github.com/user-attachments/assets/f01e0176-e15b-4137-8433-aeefc9931ba5)
セッションホストごとにユーザーがマッピングされる

**getUsersWorkingTime.kql:**
![image](https://github.com/user-attachments/assets/10d7add3-63a0-4e31-9fae-c6fab5e0e796)
