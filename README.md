#mongodb配置
mongodb:
  primary:
    host: 10.144.15.206
    port: 27017
    username: dnzl
    password: dnzl
    database: dnzl
    #与数据库建立连接的超时时间20mins 20*60*1000
    maxTimeOut: 1200000
    #数据库可以建立的最大连接数
    maxConnect: 50
    #一个线程获取到数据库连接的最大阻塞时间 5mins 5*60*1000
    maxWaitTime: 300000
    #线程队列最大值 注：该值和最大连接数的乘积为线程队列最大值
    maxWaitThread: 50
