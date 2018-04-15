# ActionCable例子
# 后台采用redis,启动rails前先`redis-server`
# 后台通过Channel名称.broadcast_to 或者ActionCable.server.broadcast "Channel名称", message 即可发送消息到浏览器
