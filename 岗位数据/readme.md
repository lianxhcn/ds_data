
### 描述

1\. 岗位数据 (jobs.csv) 5000条记录 包含以下字段： 基本信息 ：job\_id, job\_title, job\_category（技术/产品/运营/市场/设计/职能） 公司信息 ：company\_name, company\_size, company\_type 岗位要求 ：city（15个城市）, education（5个学历等级）, experience（6个经验等级） 薪资信息 ：salary\_min, salary\_max, salary\_avg 技能标签 ：skills（逗号分隔的技能列表，如"Java,Spring Boot,MySQL"） 非结构化文本 ：job\_description, requirements 其他信息 ：publish\_date, views, applications 2. 求职者数据 (candidates.csv) 1000条记录 包含以下字段： 基本信息 ：candidate\_id, name, age, gender 教育和经验 ：education, experience 地域偏好 ：current\_city, preferred\_cities 职业偏好 ：preferred\_categories 技能和薪资 ：skills, expected\_salary\_min/max/avg 非结构化文本 ：self\_introduction 注册时间 ：registration\_date 3. 应聘数据 (applications.csv) 3000条记录 包含以下字段： 关联信息 ：application\_id, job\_id, candidate\_id 匹配度评分 ：skill\_match\_score, salary\_match\_score, education\_match\_score, experience\_match\_score, total\_match\_score 匹配结果 ：is\_matched（0/1，用于分类预测） 应聘状态 ：status（待处理/已查看/面试中/已录用/已拒绝）

### 数据列表

-   数据名称上传日期大小下载
-   岗位数据.zip2026-03-06402.81KB