# Research Question
基本的主题是探索结构性难题了。问题在于，这是不可操作的。

有的科学家就像一只鸟儿，他们能够将全局知识点串联起来，以整体视角找到关键问题。有的科学家像一头驯鹿，他们能在茂密的树林中注意到任何细节，并且以一往无前的姿态破开前进的荆棘。

由于议题的特殊性，我必须作为一只鸟儿。

----------------------------

作为一个资源密集型产业，太空探索的全过程几乎是这样的(以Apollo计划为例)：
```mermaid
graph LR
    A[政治决策和社会动员] -->|政策制定与资金承诺| B[初步研究和技术评估]
    B -->|需求确认| C[需求分析和概念设计]
    C --> D[详细设计和开发]
    
    D --> E[系统集成和测试]
    E --> F[发射准备和执行]
    E --> G[产品制造和质量控制]
    F --> H[运行和维护]
    G --> H
    H --> I[数据分析和任务评估]
    I --> J[项目反馈和总结]

    style A fill:#f9f,stroke:#333,stroke-width:4px
    style B fill:#bbf,stroke:#f66,stroke-width:2px
    style C fill:#f96,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#f66,stroke-width:2px
    style E fill:#f96,stroke:#333,stroke-width:2px
    style F fill:#9cf,stroke:#333,stroke-width:2px
    style G fill:#9cf,stroke:#333,stroke-width:2px
    style H fill:#bfb,stroke:#333,stroke-width:2px
    style I fill:#ffa,stroke:#333,stroke-width:2px
    style J fill:#f9f,stroke:#333,stroke-width:4px


```
另外，商业性的太空探索是这样的：
```mermaid
graph LR
    A[市场研究和商业模式评估] -->|商业计划和投资吸引| B[技术研发和初步设计]
    B -->|设计审查和迭代| C[详细设计和开发]
    C --> D[系统集成和测试]
    D -->|如果涉及发射| E[发射许可和合作关系建立]
    E --> F[发射准备和执行]
    D -->|直接产品制造| G[产品制造和市场推广]
    F --> H[运行和维护]
    G --> H
    H --> I[市场反馈和性能评估]
    I --> J[商业模式调整和扩展]

    style A fill:#f9f,stroke:#333,stroke-width:4px
    style B fill:#bbf,stroke:#f66,stroke-width:2px
    style C fill:#f96,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#f66,stroke-width:2px
    style E fill:#9cf,stroke:#333,stroke-width:2px
    style F fill:#9cf,stroke:#333,stroke-width:2px
    style G fill:#f96,stroke:#333,stroke-width:2px
    style H fill:#bfb,stroke:#333,stroke-width:2px
    style I fill:#ffa,stroke:#333,stroke-width:2px
    style J fill:#f9f,stroke:#333,stroke-width:4px

```
那么总而言之，所有的太空探索都可以归纳为：
```mermaid
graph LR
A[预估拉投资]-->B[拉投资]
B-->C[分析资方需求与设计]--->D[设计与开发]--->E[测试与准备]--->F[执行与维护]--->V[检验成果]---->G[准备下一轮拉投资]
```
----------------
那么，我的目标主要会集中在“拉投资”或者“设计”方面，综合“小清新”的原则，拟题为：
“**大型航空航天工程的资金链需求与社会反馈挑战(Challenges of Capital Chain Requirements And Social Feedback For Large-Scale Aerospace Projects)**”
或者
“**航空航天工程的设计流程分析与改进(Analysis And Aproach Of Design Process In Aerospace Engineering)**”