# action-ReactDemo
test gitaction
阮一峰  2019 
https://www.ruanyifeng.com/blog/2019/09/getting-started-with-github-actions.html


## 测试git action 自动上传编译是否有用    随便创建的一个reactDemo   
## action编译 成功  但无法访问 资源被限制访问 Content-Security-Policy（CSP）

https://applestven.github.io/action-ReactDemo/

## 修改了 多了一个 gh-pages  但依然不能访问
- name: Deploy
        uses: peaceiris/actions-gh-pages@v3
        with:
          personal_token: ${{ secrets.ACCESS_TOKEN }}
          publish_dir: ./dist

## 修改打包文件夹路径（dist -build） 就 以及可以访问了            

https://applestven.github.io/action-ReactDemo/ 

## 修改网页文件  测试更新  


