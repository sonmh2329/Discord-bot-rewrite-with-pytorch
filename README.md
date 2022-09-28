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


## 4. Libs cần chú ý:

### a) Chatting channel

Để chạy được AI bot với các thư viện NLP support là:

- `nltk`
### b) Music channel

Để chạy được bot music thì cần:

- `ffmpeg` là thư viện để chuyển video, audio thành một dạng mà `discord` có thể hiểu được và tương tác.

- `youtube_dl` là thư viện download youtube video về để thực hiện play music.

## Tài liệu tham khảo:

[Medium](https://medium.com/pythonland/build-a-discord-bot-in-python-that-plays-music-and-send-gifs-856385e605a1)
[Stackoverflow](https://stackoverflow.com/questions/66630409/python-discord-music-bot-creating-a-queue-automatically-playing-the-next-son)
[Stackoverflow voice channel not connect](https://stackoverflow.com/questions/67311924/discord-py-voiceclient-is-connected-not-working)
[Stackoverflow youtube_del forbidden](https://stackoverflow.com/questions/32104702/youtube-dl-library-and-error-403-forbidden-when-using-generated-direct-link-by)
