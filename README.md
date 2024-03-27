# 成绩管理系统·题签(03.27)

包含素质类项目对应成果管理的成绩管理系统，能够录入学校所有本科生的成绩和素质类项目对应成果，并进行管理和维护。

**其中：**

- 学生信息管理：包括学生基本信息、班级信息等
- 成绩录入：教师与管理员可以录入学生成绩，包括单科成绩、总评成绩、素质加分绩点等
- 成绩统计：教师与管理员可通过系统查询统计信息
- 成绩查询：学生可通过系统查询成绩与排名
- 学生成绩反馈：系统可向学生提供成绩反馈，包括学科差距、进步空间等
- 教师评价与备注：教师可对学生的学习情况进行评价和备注，便于后续跟踪和记录
- 数据导出与备份：系统支持将成绩数据导出为`TXT`格式，方便学校进行数据备份和管理
- 权限管理：系统可设置不同角色的权限，以确保数据安全性和隐私保护

**为了简化，特做如下约定：**

- 账号： 整数类型
- 密码： 整数类型
- 学生年龄： 整数类型
- 学生性别： 整数类型
- 学生姓名：字符串类型，最大长度为50个字符
- 单科成绩： 浮点数类型，保留1位小数，取值范围为0-100
- 单科学分： 浮点数类型，保留1位小数，取值范围为0-10
- 素质加分绩点：浮点数类型，保留1位小数，取值范围为0-1
- 加权平均绩点： 浮点数类型，保留5位小数，取值范围为0-5
- 加权平均分： 浮点数类型，保留2位小数，取值范围为0-100
- 学科差距： 浮点数类型，保留两位小数，取值范围为0-100
- 班级排名： 整数类型，取值范围为1及以上
- 优缺点分析： 字符串类型，最大长度为100个字符
- 进步空间： 字符串类型，最大长度为100个字符
- 教师评价和备注内容： 字符串类型，最大长度为200个字符

**具体功能要求如下：**

- 录入功能：批量或单条录入学生成绩信息
- 修改功能：修改单条学生成绩记录
- 删除功能：删除单条学生成绩记录
- 查询功能：按照特定规则打印学生成绩信息
- 统计功能：统计全校成绩数据并保存为文件
