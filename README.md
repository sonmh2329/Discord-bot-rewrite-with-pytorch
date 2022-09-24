# Discord-bot-rewrite-with-pytorch

## 1. Create conda environment

```shell
conda create -n discord python=3.10.4
```

## 2. Activate enviroment

```shell
conda activate discord
```

## 3. Tạo server, bot, 

Đọc thêm Oath2 for bot [tại đây](https://discord.com/developers/docs/topics/oauth2#bot-authorization-flow)

Link: `https://discord.com/oauth2/authorize?client_id=1023271088987308102&scope=bot&permissions=0`

`permissons` ở đây là `permissions intergers` calculate từ `https://discord.com/developers/applications/<client_id>/bot`