---
layout: docs
title: 状态码
order: 300
---

<a id="codes"></a>
# HTTP状态码

HTTP状态码 | 说明
:--------- | :---------
400	       | 请求报文格式错误
401	       | 认证授权失败，可能是密钥信息不正确、数字签名错误或授权已超时
405	       | 请求方式错误，非预期的请求方式
503        | 服务端不可用
504        | 服务端操作超时
579	       | 资源上传成功，但是回调失败
599	       | 服务端操作失败
608	       | 资源内容被修改
612	       | 指定资源不存在或已被删除
614	       | 目标资源已存在
630	       | 已创建的空间数量达到上限，无法创建新空间
631	       | 指定空间不存在
701	       | 上传数据块校验出错

如遇5xx系列错误，请将完整的错误信息（包括所有的HTTP响应头部）[通过邮件发送](mailto:support@qiniu.com?subject=5xx错误日志)给我们。情况严重时请直接打400-808-9176转2上报给运维部，我们将尽快处理。  
