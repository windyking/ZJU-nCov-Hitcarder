# ZJU-nCov-Hitcarder-Sample

浙大nCov肺炎健康打卡定时自动脚本 

forked from [Tishacy/ZJU-nCov-Hitcarder](https://github.com/Tishacy/ZJU-nCov-Hitcarder)

# Sample .yml

```yml
- name: Working
   uses: Long0x0/zju-ncov-hitcarder@0.0.x
      with:
         # zju account username(student  id).
         username: ${{ secrets.ZJU_USERNAME }}
         # zju account password.
         password: ${{ secrets.ZJU_PASSWORD }}
         # (optional) dingtalk_token.
         dingtalk_token: ${{ secrets.DINGTALK_TOKEN }}
         # (optional) serverchan_key.
         serverchan_key: ${{ secrets.SERVERCHAN_KEY }}
         # (optional) pushplus_token.
         pushplus_token: ${{ secrets.PUSHPLUS_TOKEN }}
```

# Sample Repository

https://github.com/Long0x0/ZJU-nCov-Hitcarder-Sample


这个版本还需要调试修改一下，现在虽然能运行，钉钉上也能发送打卡消息，但是会提示“打卡信息已变，请手动打卡”。

