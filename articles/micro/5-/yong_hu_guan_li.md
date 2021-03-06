# 2.5 用户管理 
用户管理，主要是对用户信息、用户角色信息的管理，从而来控制用户相关操作、服务的权限。

## 2.5.1 用户管理

### 2.5.1.1 功能介绍 

用户管理，主要进行用户基本信息的管理及用户访问服务权限的控制，提供了用户基本信息的增删改查、添加角色、添加服务操作权限等功能。

### 2.5.1.2 界面说明

单击【用户管理】→【用户管理】，进入用户管理页面。界面如下：

![](/assets/5-/6/image138.png)

图2.5‑1用户管理

### 2.5.1.3 操作流程

**新增**

单击〖新增〗按钮，弹出新增用户对话框。需要填写用户名、姓名、手机号、邮箱地址（*为必输项）。单击〖确定〗，完成用户的新增操作。 

![](/assets/5-/6/image139.png)

图2.5‑2新增用户

**设置服务权限**

分配用户的服务权限，包括八个部分：资源管理、应用管理、服务管理、运行监控、用户管理、消息队列、个人信息、个性化。“管理中心”默认内置用户的服务权限不可修改，仅供查看。自定义用户可修改用户的服务权限。

选择一个用户，单击〖设置权限〗按钮，弹出添加服务权限对话框，单击勾选服务，然后单击〖确定〗，完成当前用户对服务的权限分配。

服务权限的勾选框，![](/assets/5-/6/image140.png) 表示取消该服务权限；![](/assets/5-/6/image141.png) 表示选中该服务权限。

![](/assets/5-/6/image142.png)

图2.5‑3 设置服务权限

配置用户可查看管理的环境。

![](/assets/5-/6/image143.png)

图2.5‑4查看环境配置

**修改**

选择一个用户，单击〖修改〗按钮，进入用户编辑界面，可对用户基本信息及描述进行修改操作。


![](/assets/5-/6/image144.png)

图2.5-5修改用户

**重置密码**

选择一个用户，单击〖重置密码〗按钮，可以对密码进行修改。密码的修改提供了单独的功能，和其他基本信息的修改区分开。单击〖确定〗，发送重置密码至注册邮箱。

![](/assets/5-/6/image146.png)

图2.5‑6重置密码

## 2.5.2 用户组管理

### 2.5.2.1 功能介绍

用户组管理，主要进行用户组的管理。通过用户组，分配用户角色，从而方便控制用户权限。

### 2.5.2.2 界面说明

单击【用户管理】→【用户组管理】，进入用户分用户组管理页面。用户组界面如下图所示：

![](/assets/5-/6/image147.png)

图2.5‑7 用户组管理

### 2.5.2.3 操作流程

**新增**

单击〖新增〗按钮，填写分组名称，单击〖确定〗完成用户分组的新建。

![](/assets/5-/6/image148.png)

图2.5‑8 用户组管理—新增用户组

**修改**

选择一个用户组，单击〖修改〗按钮，修改分组名称、内容描述，单击〖确定〗完成该用户组修改。

**成员管理**

选择一个用户组，单击〖成员管理〗按钮，进入成员管理界面，管理该用户组用户成员。

![](/assets/5-/6/image149.png)

图2.5‑9 用户组管理—成员管理

**管理用户**

点击〖管理用户〗，将选择的用户添加到当前用户组中。

![](/assets/5-/6/image150.png)

图2.5‑10 成员管理—添加用户

**组角色**

选择一个用户组，单击〖组角色〗按钮，进入组角色界面，管理该用户组用户成员的角色类型。

![](/assets/5-/6/image151.png)

图2.5‑11 用户组管理—组角色

**添加角色**

单击〖添加角色〗按钮，将选择的角色添加到当前用户组中。

![](/assets/5-/6/image152.png)

图2.5‑12 组角色—添加角色

**删除**

选择一个用户组，单击〖删除〗按钮，根据提示信息，单击〖确定〗按钮，将该用户组删除。

![](/assets/5-/6/image153.png)

图2.5-13删除

## 2.5.3 角色管理

### 2.5.3.1 功能介绍

角色管理主要是用户角色的配置管理。

### 2.5.3.2 界面说明

单击【用户管理】→【角色管理】，进入角色管理页面。角色信息列表如下图所示：

![](/assets/5-/6/image154.png)

图2.5‑14角色管理

### 2.5.3.3 操作流程

**新增**

单击〖新增〗按钮，弹出新增窗口，填写角色名称，选择角色的类型，单击〖保存〗完成角色的新建。

![](/assets/5-/6/image155.png)

图2.5‑15新增角色

**查看**

“管理中心”默认内置角色不可修改，仅供查看。用户自定义角色可修改角色名称及角色类型。

<table>

 <tr>

 <td>角色名称</td>

 <td>角色类型</td>

 <td>系统默认生成</td>

 <td>含义</td>

 </tr>

 <tr>

 <td>Administrator</td>

 <td>Admin</td>

 <td>是</td>

 <td>超级管理员</td>

 </tr>

 <tr>

 <td>ServiceManagement</td>

 <td>Admin</td>

 <td>是</td>

 <td>服务管理角色</td>

 </tr>

 <tr>

 <td>Operational</td>

 <td>Admin</td>

 <td>是</td>

 <td>系统运维角色</td>

 </tr>

 <tr>

 <td>DailyManagement</td>

 <td>Admin</td>

 <td>是</td>

 <td>日常管理角色</td>

 </tr>

</table>

角色类型包括三种：Admin（管理员）、User（普通用户）、PassThrough（特殊通行用户）。

选择一个角色，单击〖修改〗按钮，弹出修改角色对话框。

![](/assets/5-/6/image156.png)

图2.5‑16查看角色

**成员管理**

选择一个角色，单击〖成员管理〗按钮，进入成员管理界面，管理该角色组用户成员。

![](/assets/5-/6/image157.png)

图2.5‑17 角色管理—成员管理

**管理用户**

单击〖管理用户〗，将选择的角色添加到当前角色组中。

![](/assets/5-/6/image158.png)

图2.5‑18成员管理—添加角色

**设置权限**

“管理中心”默认内置角色不可修改，仅供查看。用户自定义角色可设置分配操作权限。

选择一个角色，单击〖设置权限〗按钮，弹出设置权限对话框。

![](/assets/5-/6/image185.png)

图2.5‑19 设置权限

配置用户可查看管理的环境。

![](/assets/5-/6/image159.png)

图2.5‑20 查看/修改环境配置

**删除**

“管理中心”默认内置角色不可删除，仅供查看。用户自定义角色可做删除操作。

选择一个角色，单击〖删除〗按钮，则会在角色列表中删除当前角色。

![](/assets/5-/6/image160.png)

图2.5‑21 删除角色




























































 






















﻿