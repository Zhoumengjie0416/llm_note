# llm_note
BPE分词算法理解：https://zhuanlan.zhihu.com/p/424631681




RLHF  DPO、PPO、GRPO、DAPO
DPO相对于PPO优点：数据格式（一个问题两个回答，一个choice，应该reject）使得其是SFT简单易于训练，不需要reward和critic模型
DPO相对于PPO缺点：容易过拟合
<img width="1117" height="315" alt="image" src="https://github.com/user-attachments/assets/eeab8982-3af9-4304-8f99-b1819d85056f" />

https://zhuanlan.zhihu.com/p/1910019667268986241
链接1：https://blog.csdn.net/Antai_ZHU/article/details/140326151
链接2：https://github.com/wdndev/llm_interview_note/blob/main/07.%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0/%E5%A4%A7%E6%A8%A1%E5%9E%8BRLHF%EF%BC%9APPO%E5%8E%9F%E7%90%86%E4%B8%8E%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB/%E5%A4%A7%E6%A8%A1%E5%9E%8BRLHF%EF%BC%9APPO%E5%8E%9F%E7%90%86%E4%B8%8E%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB.md



![image](https://github.com/user-attachments/assets/5f687d95-114f-4655-aceb-83946eabd451)
<img width="1174" height="412" alt="89fad35736003f611df7688e712ccc28" src="https://github.com/user-attachments/assets/f513a2a1-c410-4a2e-a1f4-634ae7be692a" />



actor model

![image](https://github.com/user-attachments/assets/c9511d6a-182a-4de5-869f-84e658fc5960)

ref model、reward model、critic model

![image](https://github.com/user-attachments/assets/78861185-50ca-4baa-8bc3-0205eb9c7f9d)



rsync -avP folder1/ folder2/
