- 学生用户
- 教师用户
- 管理员用户
- 课程
- 试卷
- 评论
- 文件
- 教师执照

页面详情
- 通用
  - 首页
    - 展示视频
    - 导航（登录、注册、消息[包括点赞和留言]、vip入口[充值]、试卷详解、）
    - 分类显示
  - 注册
    - 选择角色（教师、学生、）
    - 相应角色的注册表单（表单验证）
    - 注册成功后跳转到登录页面
  - 登录
    - 登录表单（验证）、
    - 登录成功后跳转到首页
- 学生
  - 个人信息
  - 修改信息
  - 查看考试（待考、已考的显示成绩）、进入考试
- 个人信息展示页面
  - 个人信息（不可编辑）
  - 留言功能
- vip页面
  - 充值、续费
  - vip等级
- 老师
  - 设计试卷
  - 上传视频、课件pdf
  - 提交试卷
  - 修改试卷
  - 发布作业
- 管理员
  - 审核视频
  - 冻结学生用户和教师用户
- 课程
  - 展示目录信息（章节评分）、
  - 显示课程平均分、
- 看视频界面
  - vip一对一教学、评论置顶、上传作业（md）
  - 评论
  - 评分、显示平均分
  - 热门评论、
  - 下载课件pdf
- 考试页面
  - 显示考试时间倒计时、
  - 超时自动提交
  - 显示信息
  - 提交试卷
- 文件
  - 查看pdf
  - 下载

试卷
```json
{
  "title": 'paper title',
  "time": 100, //分钟
  "questions": {
    "choice": [
      {
        "topic": '',
        "options": [],
        "right_answer": 0,
        "full_score": 5 
      }
    ],
    "essay": [
      {
        "topic": '',
        "full_score": 5
      }
    ]
  }
}
```