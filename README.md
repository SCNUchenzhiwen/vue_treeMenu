# treeMenu

# 基于render函数递归实现树形菜单

# 1、动画通过js动态获取height的值动态修改实现折叠动画
# 2、通过递归函数返回子节点vNode挂在到父节点上

/**
 * 属性菜单结构
 * @prop {Array} - 属性结构数组
 *        example:
 *          treeData: [
                        {
                          txt: '001',
                          child: [
                            {
                              txt: '001-0',
                              child: [
                                {
                                  txt: '001-0-0'
                                }
                              ]
                            }
                          ]
                        }
                      ]
 */
      
使用直接下载components/treeMenu文件即可

# 效果图
![treemenu](https://github.com/SCNUchenzhiwen/vue_treeMenu/blob/master/trreMenu.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue_treeMenu/blob/master/drop.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue_treeMenu/blob/master/undrop.jpg)


> treeMenu

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
