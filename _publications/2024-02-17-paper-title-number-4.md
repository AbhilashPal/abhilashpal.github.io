---
title: "ConciseNet: An End To End Abstractive Model For Topic Generation"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'A Novel Topic Generation Model.'
date: 2019-10-01
venue: 'IJEAST'
paperurl: 'https://d1wqtxts1xzle7.cloudfront.net/71740505/ijeast.2019.v04i04-libre.pdf?1633609630=&response-content-disposition=inline%3B+filename%3DConcisenet_An_End_to_End_Abstractive_Mod.pdf&Expires=1715354240&Signature=II01tsF4YALax6ZZppqCXlTDtKEa~uEUKRb86A~GmE-GNONPTbnOG92VcuNwtOTLJIhQBO3c9aTqgDFw98C1m5SD233Jz8Xvc~U51RaQIec~44H9wbZBJVJtcf6-P96pH8lH-S0cLyAwwGt4QTC9burFgmbWIz4hJ3Qr14JEJ~t~lC4xQCQgSjZvonQjvzL0QFcYTfZ~WPCGdZZGB7aHCbtE8tflHruTYwcVbu~ssaBVW0cn2Q46rCz61-geEBXNradXsG3-MPwdJc7m1XG1imaK1SWlvdRPPwylcsHVbQ1BbnoA3HhLQO80SkbNHkFXO1~oTzSc4tIXZY-AMjrbVA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA'
citation: # 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Recent approaches in Title generation using neural approaches have relied on an end to end deep learning system based on the sequence to sequence model. Such approaches have yielded good results but remain constricted in use due to a fixed size input which is often very small compared to the text being used or might take huge compute power to train and use if input size is increased. Our approach amalgamates an extractive and abstractive approach to get the best of both worlds using a textrank algorithm for the extractive part and a reasonably small seq2seq architecture as the abstractive part. Testing on the Amazon Fine Food Review dataset, our approach gives good results using less compute power. We utilize the prevailing metrics of ROUGE and Cosine Similarity. Manual checking shows that the majority of our generated topics are grammatically correct.