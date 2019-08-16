# xl_pagetransition
#### 用于 react 页面过度动画（左滑，右滑）

# 安装
#### yarn install xl_pagetransition

# 使用例子
```js
import PageTransition, {setDirection, BoxPage} from './pageTransition'

<div style={{position: 'absolute',width: '100%',height: '100%',left: 0,top: 0,}}>
    <PageTransition>
      <BoxPage key={pathname}>
        <Switch location={location}>
          {children}
        </Switch>
      </BoxPage>
    </PageTransition>
</div>
```

##### setDirection : 在路由改变的时候，设置滑动效果(none:无滑动，left:左滑，right:右滑)

###### 有问题可以在 github 上留言哦！！ 

