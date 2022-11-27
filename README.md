#vue - This is about my vue learning process

vue:
    读音: view
    渐进式框架: core+vue-router+vuex可以满足大部分需求
    vue和vuejs是无差别的

vue的特点:
    1、接耦视图和数据
    2、可复用的组建
    3、前端路由技术
    4、状态管理
    5、虚拟DOM

响应式: 当数据发生改变时，界面也跟着其改变

vuejs安装方式
    1、cdn引入
        1)开发环境: <script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"><script>
        2)生产环境: <script src="https://cdn.jsdelivr.net/npm/vue@2"></script>
    2、下载和引入
        1)开发环境: vue.js
        2)生产环境: vue.min.js
    3、NPM安装管理

vue中的MVVM: 
    MVVM: Model View ViewModel
    Model ViewModel View  ViewModel是Model和View之间的一个通信的桥梁
    View层:
        视图层
        在前端开发中，通常就是DOM层
        主要作用是给用户展示各种信息
    Model层: 
        数据层
        数据可能是数据库中不变的数据，更多的来自服务器，简单说通过网络请求过来的数据
    ViewModel层: 
        视图模型层
        ViewModel的作用:
            1、数据绑定(Data Bindings)
            2、DOM监听(DOM Listeners)
hello world
