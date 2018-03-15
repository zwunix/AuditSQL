# AuditSQL

AuditSQL是基于Inception开发的一款web审核平台，旨在降低DBA的工作成本

## 组件
- Python 3.6
- Django 2.0 
- django-celery
- django-channels
- AdminLTE

## 功能：
- 线上审核
    - 数据变更提交
    - 工单记录
       - 审批 （Leader角色有权限操作）
       - 执行（DBA角色有权限操作）
       - 关闭（告知DBA不执行） 
    - 工单详情（显示当前工单的详情记录）

- 线下审核
    - SQL审核
    - 生成执行任务
    - 执行任务
       - 显示当前任务SQL列表
       - 执行，实时显示当前执行的OSC任务进度
       - 停止，关闭当前正在执行的OSC任务
       - 结果，显示回滚SQL，执行的日志（来自inception输出）
       
- SQL审核
   - 流程化
   - SQL美化
   - SQL检测
   - 审核历史记录
   - 语法高亮
   - 注释识别

- 进度推送：
   - 线上审核的每一步E-Mail实时推送
   - 线下执行任务进度的实时推送
  
- 其他：
   - 支持LDAP认证登陆
   - 项目权限控制
   - 角色权限控制
  
- 扩展功能：
   - 支持数据库表结构变更自动E-Mail通知，并生成变更结果


## 联系方式
   
   QQ: 1126227133
   
   E-mail: 1126227133@qq.com