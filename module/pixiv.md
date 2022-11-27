<link rel="stylesheet" href="/v1-docs/asset/style.css" />

# 插画
<p><span class="span-friend">私聊</span>  <span class="span-group">群聊</span></p>


## 获取插画
```
.pixiv [张数] [r18] [关键字]
```

### 参考
```
.pixiv 10张 r18 白丝
```

```
.pixiv 10张 白丝
```

```
.pixiv r18 白丝
```

```
.pixiv 白丝
```

```
.pixiv
```

## 设置
<p><span class="span-bot-admin">Bot 管理员</span>  <span class="span-bot-helper">Bot 协助者</span></p>

> 此部分的事件响应器均为 `on_command` 生成的, 触发时需要带有命令头( . | /w)  

白名单管理：
```
.pixiv_wl add  添加会话至白名单
.pixiv_wl del  移出会话自白名单
```

黑名单管理：
```
.pixiv_ban add  添加会话至黑名单
.pixiv_ban del  移出会话自黑名单
```

r18模式管理：
```
.pixiv_r18 on  开启会话的r18模式
.pixiv_r18 off 关闭会话的r18模式
```

cd时间更新:
```
.pixiv_cd xxx  更新会话的冷却时间, xxx 为 int 类型的参数
```

撤回时间更新:
```
.pixiv_wd xxx  撤回前等待的时间, xxx 为 int 类型的参数
```

最大张数更新:
```
.pixiv_mn xxx  单次发送的最大图片数, xxx 为 int 类型的参数
```
