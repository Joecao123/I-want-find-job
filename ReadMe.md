# 需求分析
![img](/就业信息管理系统需求.png)
---
# 进度管理

时间 | 强哥 | 俊杰 | 科杰 | 志哥 | 备注
---|---|---|---|---|--- 
周一 | 软件需求说明书 | ... | ... | ... |共同完成管理员需求说明书，强哥俊杰负责企业，科杰志哥负责学生
完成度|完成
周二 | 上午数据流图，下午ER图



# 软件需求说明
---
## 管理员功能说明
- 企业模块管理
    - 对企业资质认证及信息修改请求的审核
    - 对企业列表信息进行查改
    - 对企业进行删除
    - 对企业发布招聘信息进行的查看及审核
- 学生模块管理
    - 对学生的信息批量导入
    - 对学生的注册登记信息审核
    - 对学生相关信息进行查看（按照学校专业班级查询）
    - 对学生的就业信息的登记处理
- 管理员自身管理
    - 对自身信息的修改

### 管理员用例图
![img](/管理员用例图.png)
### 管理员用例描述
- 登陆系统


- 审核各类信息用例

用例名称 | 审核各类信息
--- | ---
用例描述 | 管理员完成审核各类信息整个过程
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员以管理员身份登录系统并且有待审核信息
后置条件 | 管理员完成审核信息过程，提交审核结果。
基本操作流程 | 管理员进入信息审核页面<br>管理员查看各类待审核信息<br>管理员提交审核结果<br>系统将审核结果发送给学生，企业用户
可选操作流程 | 无
假设 | 管理员以管理员身份登录系统并且有待审核信息


- 审核各类信息用例

用例名称 | 审核各类信息
--- | ---
用例描述 | 管理员完成审核各类信息整个过程
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员以管理员身份登录系统并且有待审核信息
后置条件 | 管理员完成审核信息过程，提交审核结果。
基本操作流程 | 管理员进入信息审核页面<br>管理员查看各类待审核信息<br>管理员提交审核结果<br>系统将审核结果发送给学生，企业用户
可选操作流程 | 无
假设 | 管理员以管理员身份登录系统并且有待审核信息


- 修改企业信息用例

用例名称 | 修改企业信息
--- | ---
用例描述 | 管理员完成修改企业信息整个过程
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员以管理员身份登录系统并且已有企业信息存在
后置条件 | 无
基本操作流程 | 管理员进入企业信息页面<br>管理员选择待修改企业信息<br>管理员对已选择企业进行修改<br>管理员提交修改
可选操作流程 | 无
假设 | 管理员以管理员身份登录系统并且已有企业信息存在


- 查看企业发布招聘信息用例

用例名称 | 查看企业发布招聘信息
--- | ---
用例描述 | 管理员完成查看企业发布招聘信息整个过程
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员以管理员身份登录系统并且已有企业信息存在
后置条件 | 无
基本操作流程 | 管理员进入企业列表页面<br>管理员进入某企业招聘信息页面<br>管理员查看企业招聘信息
可选操作流程 | 无
假设 | 管理员以管理员身份登录系统并且已有企业信息存在


用例名称 | 登陆系统
---|---
用例描述 | 管理员输入用户名密码进行登陆的整个过程
参与者 | 管理员
状态 | 通过审查
前置条件 | 系统运行正常
后置条件 | 登陆成功可对各个功能模块进行管理，登录不成功则不能进行以上操作
基本操作流程 | 用户输入账户密码，系统验证账户密码合法性，合法则登录系统
可选操作流程 | 账号密码不合法，系统提示错误
假设 | 系统运行正常


- 修改管理员信息

用例名称 | 修改管理员信息
---|---
用例描述 | 管理员修改自身的信息
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员登陆成功，并选择修改个人信息
后置条件 | 管理员的信息成功被修改
基本操作流程 | 管理员选择修改个人信息，修改后，点击保存
可选操作流程 | 无
假设 | 系统运行正常
- 查看管理员信息

用例名称 | 查看管理员信息
---|---
用例描述 | 管理员查看自身的信息
参与者 | 管理员
状态 | 通过审查
前置条件 | 管理员登陆成功，并选择修查看个人信息
后置条件 | 管理员的信息在表单中显示
基本操作流程 | 管理员选择查看个人信息
可选操作流程 | 无
假设 | 系统运行正常
- 批量导入学生信息

用例名称 | 批量导入学生信息    
--- | ---        
用例描述 | 管理员通过批量导入学生信息，完成批量注册    
参与者 | 管理员    
状态 | 无    
前置条件 | 管理员本地有学生信息    
后置条件 | 学生招聘信息填写    
基本操作流程 | 在“招聘网站”网址内，点击按钮实现本地学生信息的导入，完成批量注册   
可选操作流程 | 关闭网页    
假设 | 管理员本地有学生信息   
- 审核学生注册信息

用例名称 | 审核学生注册信息    
--- | ---       
用例描述 | 管理员审核学生自己注册的信息    
参与者 | 管理员    
状态 | 无    
前置条件 | 学生完成注册    
后置条件 | 学生招聘信息填写    
基本操作流程 | 在“招聘网站”网址内，点击按钮审核学生信息   
可选操作流程 | 审核成功或审核失败    
假设 | 学生完成注册息 
- 查询学生相关信息

用例名称 | 查询学生相关信息    
--- | ---       
用例描述 | 管理员按照关键词查询学生信息    
参与者 | 管理员    
状态 | 无    
前置条件 | 学生信息已经录入    
后置条件 | 无    
基本操作流程 | 在“招聘网站”网址内， 管理员按照关键词查询学生信息   
可选操作流程 | 重新查询    
假设 | 学生信息已经录入 
- 审核处理学生就业信息

用例名称 | 审核处理学生就业信息    
--- | ---        
用例描述 | 管理员审核处理学生就业信息    
参与者 | 管理员    
状态 | 无    
前置条件 | 学生已经找到就业单位，信息已经录入    
后置条件 | 无    
基本操作流程 | 在“招聘网站”网址内， 管理员点击按钮审核学生就业信息   
可选操作流程 | 审核成功或审核失败    
假设 | 学生已经找到就业单位，信息已经录入 

## 学生功能说明
- 注册功能
- 申请修改自身个人信息，包括提交个人认证
- 填写求职意向并发放自身求职简历
- 查询企业招聘信息
- 向对应企业发送求职简历
- 登记就业信息

### 学生用例图
![学生用例图](/学生用例图.png)

### 学生用例描述
- 注册用户用例

用例名称 | 注册
--- | ---
用例描述 | 用户完成该平台的注册，进行招聘岗位的查看
参与者 | 学生
状态 | 进行注册
前置条件 | 进入该网站
后置条件 | 进入网站主界面
基本操作流程 | 用户可以用自己的手机号，输入密码进行注册操作
可选操作 | 无
假设 | 无

- 认证个人身份信息

用例名称 | 认证个人身份信息
--- | ---
用例描述 | 学生用户完成对自身个人信息的认证
参与者 | 学生
状态 | 进行认证状态
前置条件 | 申请进行学生
后置条件 | 进入网站主界面
基本操作流程 | 用户可以用自己的手机号，输入密码进行注册操作
可选操作 | 无
假设 | 无

- 修改个人信息

用例名称 | 修改个人
--- | ---
用例描述 | 学生请求申请修改个人信息
参与者 | 学生
状态 | 请求申请修改个人信息
前置条件 | 申请进行学生
后置条件 | 传达信息给管理员进行审核
基本操作流程 | 对自身信息进行相应的修改
可选操作 | 无
假设 | 无

- 发布个人求职信息

用例名称 | 学生发布个人求职信息
--- | ---
用例描述 | 发布个人求职信息
参与者 | 学生
状态 | 发布个人求职信息
前置条件 | 申请发布个人求职信息
后置条件 | 发布信息完毕
基本操作流程 | 填写个人求职兴趣，发布个人简历
可选操作 | 无
假设 | 无

- 查询招聘企业信息

用例名称 | 查询招聘企业信息
--- | ---
用例描述 | 学生对招聘企业信息情况及岗位需求进行查看
参与者 | 学生
状态 | 查询招聘企业信息查看
前置条件 | 请求查询招聘企业信息
后置条件 | 查询信息完毕
基本操作流程 | 查看招聘企业的信息
可选操作 | 按照薪资对岗位进行排序操作，对岗位的地点进行筛选查询，对对应企业投放简历接口
假设 | 无

- 投放简历

用例名称 | 投放简历
--- | ---
用例描述 | 学生对有兴趣的企业投放自己的简历
参与者 | 学生
状态 | 投放简历状态
前置条件 | 请求发放简历
后置条件 | 投放简历完毕
基本操作流程 | 投放简历
可选操作 | 无
假设 | 无

- 填写就业情况

用例名称 | 填写就业情况
--- | ---
用例描述 | 已经成功就业的同学填写就业情况
参与者 | 学生
状态 | 填写就业情况
前置条件 | 已经完成就业
后置条件 | 完成填写就业情况
基本操作流程 | 填写薪资，公司满意度选择，填写就业心得
可选操作 | 无
假设 | 无





## 企业功能说明
- 可以用手机号进行注册
- 企业基本信息的填写，包括企业名称、企业地址、企业简介、联系方式、企业的资质证明，并等待管理员审核。
- 企业招聘信息的填写，包括具体的岗位以及相关的要求
- 对企业的基本信息、招聘信息的修改，并等待管理员审核。
- 企业可以查看申请岗位人员简历信息

### 企业用例图
![img](/企业用例图.PNG)

### 企业用例描述


- 输入企业基本信息用例

用例名称 | 输入企业基本信息
--- | ---
用例描述 | 企业在就业管理系统完成输入企业基本信息整个过程
参与者 | 企业
状态 | 通过审查
前置条件 | 企业成功以企业身份登录系统
后置条件 | 企业输入企业基本信息后可进行后续修改信息操作
基本操作流程 | 企业进入基本信息输入页面<br>企业输入企业基本信息<br>企业输入完毕等待审核<br>审核通过将信息保存到数据库<br>企业可进行后续输入修改企业基本信息
可选操作流程 | 审核不通过，企业重新输入
假设 | 企业成功以企业身份登录系统


- 发布招聘信息用例

用例名称 | 发布招聘信息
--- | ---
用例描述 | 企业在就业管理系统完成发布招聘信息整个过程
参与者 | 企业
状态 | 通过审查
前置条件 | 用户成功以企业角色登录系统
后置条件 | 企业发布招聘信息后可进行后续修改招聘信息操作
基本操作流程 | 企业进入招聘信息发布页面<br>企业输入招聘信息并上传相关文件<br>企业输入信息并上传文件完毕，等待审核<br>审核通过后，系统发布招聘信息<br>企业可进行后续修改操作并重新发布
可选操作流程 | 审核不通过，企业重新输入
假设 | 企业成功以企业身份登录系统


- 查看求职者信息用例

用例名称 | 查看求职者信息
--- | ---
用例描述 | 企业完成查看求职者信息整个过程
参与者 | 企业
状态 | 通过审查
前置条件 | 用户成功以企业角色登录系统
后置条件 | 企业查看求职者信息后决定是否向求职者发送面试通知
基本操作流程 | 企业进入求职者信息查看页面<br>企业查看求职者信息
可选操作流程 | 企业向求职者发送面试通知
假设 | 企业成功以企业身份登录系统



## 游客功能说明
- 浏览企业的招聘信息

### 游客用例图
![游客用例图](/游客浏览网页用例.png)

### 游客用例说明
用例名称 | 浏览网页    
--- | ---       
用例描述 | 游客状态的用户利用浏览器浏览“招聘网站”的信息    
参与者 | 游客    
状态 | 无    
前置条件 | 游客成功加载网页信息    
后置条件 | 无    
基本操作流程 | 在浏览器内输入“招聘网站”网址，即可浏览网页信息    
可选操作流程 | 关闭网页或选择注册    
假设 | 游客成功加载网页信息    

