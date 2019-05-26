# springcloud-learning
分布式配置学习
配置文件与URL之间的关系：

/{application}/{profile}[/{label}]

/{application}-{profile}.yml

/{application}-{profile}.properties

/{label}/{application}-{profile}.yml

/{label}/{application}-{profile}.properties

label:对应git上不同的分支，默认是master

application：配置文件名称

profile：环境，dev还是prod

