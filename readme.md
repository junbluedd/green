# github每天自动点亮小绿框

使用方法：
修改/workflows/main.yml的内容：

    - cron: '3,17,35 8-18 * * *'  //引号内修改每天刷绿的时间段和次数，默认是每天20次左右可以不用改
    
    git config --local user.email "3115014909@qq.com"  //这里配置你的github邮箱
    
    git config --local user.name "junbluedd"  //这里配置你的github用户名
    
   配置完成保存点击actions开启自动任务，点击star触发启动一次，然后每天会自动启动。
   
这是个绿油油的项目，点亮小绿框，从我做起
