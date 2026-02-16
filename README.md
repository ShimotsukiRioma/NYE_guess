# 25:00 // Terminal_Project: Collapse

> 「你所看到的真实，只是因为我允许你看到它。」

这是一个关于【观测】的取证实验。真相被拆解并缝合在不同的维度中。
非开发者请止步。

---

### 📡 观测坐标 (The Coordinates)

#### 0x01 | Fragment_1: The Marrow (骨髓)
* **载体**: `./clue.png`
* **线索**: 可以问问打过CTF的人，你应该找到啥？

#### 0x02 | Fragment_2: The Residual (残骸)
* **载体**: `在repo中探索`
* **方式**: 或许看看[过去的东西]？
* **提示**: 你也有过曾经。

---

### 🧩 核心协议 (Decryption Protocol)

* **算法**: `AES-256-CBC` / `PKCS7`
* **IV (Hex)**: `3030303030303030303030303030303235`
* **Key 构造逻辑**: 
    1.  `Raw_Key = Fragment_1 + Decoded_Fragment_2`
    2.  `Final_Key = SHA256(Raw_Key)`
* **数据读入**: 请将 `core.bin` 以 Base64 格式输入。

---

### 📑 最终取证说明 (Final Retrieval)

解开 `core.bin` 后，你将获得一份极简索引。
1. **数据源**: 你可能需要Project SEKAI的wiki帮忙。
2. **偏移量**: 字符计数包含所有符号（标点、空格、汉字位），以原始标题为准。
3. **格式**: 请将提取出的字符转化为 **长得像汉字的假名** 进行最后告解。

---

### 🏮 提交报告 (Verification)

如果你穿透了所有伪装，请在此处提交你的【观测报告】：
[👉 提交至邮箱 ](rioma_shimotsuki@foxmail.com)
(你必须描述一些解开的过程)

> 真相不在此处。它在你的考据里。
