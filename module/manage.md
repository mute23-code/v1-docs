<link rel="stylesheet" href="/asset/style.css" />


# 群管
<p><span class="span-admin">群管理员</span>  <span class="span-group">群主</span>  <span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

> 此功能需要 林汐 拥有 **管理员权限**

## 禁言
----
### 禁言
```
.禁 <时间> <at> | .禁 <at> <时间>
```
随机禁言
```
.禁 <at>
```
解禁
```
.禁 0 <at> | .禁 <at> 0 | .解 <at>
```

### 全员禁言
```
.全员禁言
```
解禁
```
.全员禁言 解
```

<details>
<summary>指令别名</summary>
<pre><code>
.禁 = .ban
.解 = .unban
.全员禁言 = .全禁 = .all
</code></pre>
</details>

## 踢出
---
### 普通
```
.踢 <at>
```
### 踢出并拉黑
```
.黑 <at>
```

<details>
<summary>指令别名</summary>
<pre><code>
.踢 = .kick
</code></pre>
</details>

## 撤回
---
```
.撤回 （回复某条消息即可撤回对应消息）
```

## 名片
---
### 改名片
```
.改 <at> 名片
```

## 头衔
---
> 该功能需要 林汐 拥有 **群主权限**
### 自助领取
```
.头衔 <头衔名>
```
```
.删头衔
```

### 更改他人头衔
```
.头衔 <at> <头衔名>
```
```
.删头衔 <at>
```

## 管理员
---
> 该功能需要 林汐 拥有 **群主权限**
### 设置管理员
```
.管理员+ <at>
```
### 取消管理员
```
.管理员- <at>
```

### 分群管理员

> 分群管理员指：可以接受加群处理结果消息的用户  
#### 增加分管
可用@或qq号添加分群管理员
```
.分管+ <at|qq>      
```
#### 删除分管
可用@或qq号删除分群管理员
```
.分管- <at|qq>
```
#### 查看分管
```
.查看分管
```

<details>
<summary>指令别名</summary>
<pre><code>
.管理员+ = .增加管理 = .增加管理员
.管理员- = .取消管理 = .取消管理员
.分管+ = .gad+ = .增加分群管理
.分管- = .gad- = .取消分群管理
</code></pre>
</details>

## 加群自动审批
---
### 查看审批词条
```
.查看词条
```
### 增加审批词条
```
.词条+ <词条>
```
### 删除审批词条
```
.词条- <词条>
```

### 查看所有审批词条
<p><span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

```
.所有词条
```
### 增加指定群审批词条
<p><span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

```
.指定词条+ <群号> <词条>
```
### 删除指定群审批词条
<p><span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

```
.指定词条- <群号> <词条>
```

## 群词云图

<p><span class="span-group">群聊</span></p>

---
### 记录本群
```
.开始记录
```

### 停止记录
```
.停止记录
```

### 发送词云图
```
.群词云
```

### 更新mask图片
```
.更新mask
```

### 增加停用词
```
.增加停用词 <停用词1> [停用词2] [停用词n]
```

### 删除停用词
```
.删除停用词 <停用词1> [停用词2] [停用词n]
```

### 停用词列表
```
.停用词列表
```

<details>
<summary>指令别名</summary>
<pre><code>
.开始记录 = .记录本群
.停止记录 = .停止记录本群
.增加停用词 = .添加停用词 = .新增停用词
.删除停用词 = .移除停用词 = .去除停用词
.停用词列表 = .查看停用词 =.查询停用词
</code></pre>
</details>

## 群发言排行
<p><span class="span-group">群聊</span></p>
---
### 日排行

#### 日榜首
```
.今日榜首
```
#### 日排行
```
.今日排行
```

#### 昨日排行
```
.昨日排行
```

### 总排行

#### 总排行榜
```
.排行
```

### 个人发言数

#### 日发言数
```
.今日发言 <at>
```

#### 总发言数
```
.发言数 <at>
```

<details>
<summary>指令别名</summary>
<pre><code>
.今日排行 = .今日排行榜
.昨日排行 = .昨日排行榜
.排行 = .总排行 = .排行榜
.今日发言 = .今日发言数 = .今日发言量
.发言数 = .发言量
</code></pre>
</details>

---

## 群管开关
<p><span class="span-admin">群管理员</span>  <span class="span-group">群主</span>  <span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

### 查看群管各功能的状态
```
.开关状态
```

### 对群管各功能进行开/关
```
.开关<功能>
```

---

## 设置

<p><span class="span-admin">群管理员</span>  <span class="span-group">群主</span>  <span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

```
.功能关闭 群管
```
```
.功能开启 群管
```