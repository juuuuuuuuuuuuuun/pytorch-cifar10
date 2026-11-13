# pytorch-cifar10
深層学習の知識習得用


 ## 目的
　NNのデータの準備から結果の出し方まで理解し、実際に実装できるようにする
 　

 ## やり方　
　https://docs.pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html
　
  このサイトを参考にする。具体的な手法は後日追加する

 ## 結果
<img width="584" height="455" alt="train_loss1" src="https://github.com/user-attachments/assets/772af216-2dba-4bb3-954c-394b94bd1bf8" />
<img width="562" height="455" alt="test_Accuracy1" src="https://github.com/user-attachments/assets/ec2a25c4-c1b2-4b2f-b7f1-e38d5b74316f" />


 ## 考察

 エポック数が増えるにつれtrain_lossが低くなっていることがわかる。しかしtest_accuracyは一貫した変化ではなく上下が激しかった。

 # 試してみたもの
 ## 全統合をCNNに変更して試してみた
 11/13　全統合のモデルをCNNにすることによって精度の向上を試みた。
 ### 結果
 <img width="567" height="455" alt="train_loss2" src="https://github.com/user-attachments/assets/26733dd6-cd43-47a6-b319-0423a88fb4f8" />
<img width="563" height="455" alt="test_Accuracy2" src="https://github.com/user-attachments/assets/c4bc5327-8497-43fd-bd76-8631dbfd6fd9" />

 ### 考察
　以前と比べて非常に高い精度を出すことができた

  
