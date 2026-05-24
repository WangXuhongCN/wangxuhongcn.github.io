graph TD
    subgraph "知识推理树（示意图）"

    %% 根节点 - 问题
    Q["亚硝酸盐致癌吗？(9)"];

    %% --- 主路径1: 低质量信源 ---
    Q --> N1["隔夜菜致癌[朋友圈](3)"];
    N1 --> N1_1["亚硝酸盐是剧毒[传言](2)"];
    N1_1 --> A1["<font color=red>结论:剧毒致癌物(1)</font>"];

    %% --- 主路径2: 中等质量信源与分叉 ---
    Q --> N2["过量摄入有风险[科普](6)"];
    
    %% --- 分叉 2.1 (正确推理)---
    N2 --> N2_1["与蛋白质反应[化学](7)"];
    N2_1 --> N2_1_1["生成亚硝胺[术语](8)"];
    N2_1_1 --> A2_1["<font color=darkorange>结论:间接致癌(7)</font>"];
    
    %% --- 分叉 2.2 (错误推理) ---
    N2 --> N2_2["剂量决定毒性[常识](5)"];
    N2_2 --> N2_2_1["混淆工业盐[误解](2)"];
    N2_2_1 --> A2_2["<font color=red>结论:工业盐中毒(2)</font>"];

    %% --- 主路径3: 权威信源与深度挖掘 ---
    Q --> N3["合法食品添加剂[国标](10)"];
    
    %% --- 分叉 3.1: 机理探究 ---
    N3 --> N3_1["护色防腐作用[手册](9)"];
    N3_1 --> N3_1_1["亚硝胺致癌[IARC](10)"];
    N3_1_1 --> N3_1_2["VC可阻断合成[论文](9)"];
    N3_1_2 --> A3_1["<font color=green>结论:条件致癌可阻断(10)</font>"];
    
    end

    %% 样式定义
    style Q fill:#f9f,stroke:#333,stroke-width:2px;
    style N1 fill:#FFC4C4,stroke:#D20000;
    style N1_1 fill:#FFC4C4,stroke:#D20000;
    style A1 fill:#FFC4C4,stroke:#D20000,stroke-width:2px,font-weight:bold;
    style N2_2_1 fill:#FFC4C4,stroke:#D20000;
    style A2_2 fill:#FFC4C4,stroke:#D20000,stroke-width:2px,font-weight:bold;
    style N2 fill:#FFDBA4,stroke:#FFA500;
    style N2_1 fill:#FFF5B1,stroke:#FFD700;
    style N2_1_1 fill:#FFF5B1,stroke:#FFD700;
    style A2_1 fill:#FFDBA4,stroke:#FFA500,stroke-width:2px,font-weight:bold;
    style N3 fill:#C1FFC1,stroke:#008000;
    style N3_1 fill:#D8FFD8,stroke:#006400;
    style N3_1_1 fill:#D8FFD8,stroke:#006400;
    style N3_1_2 fill:#D8FFD8,stroke:#006400;
    style A3_1 fill:#C1FFC1,stroke:#008000,stroke-width:2px,font-weight:bold;
    
 