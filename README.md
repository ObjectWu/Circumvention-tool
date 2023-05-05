<p>
<b>finashell下载地址:</b>http://www.hostbuf.com/downloads/finalshell_install.exe
<br><br>
<b>搭建指令:</b><code>wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh</code>
<br><br>
  <b>V2ray下载地址:</b>https://github.com/v2fly/v2ray-core/releases/download/v4.31.0/v2ray-windows-arm32-v7a.zip
  <br><br>
  搭建docker容器环境
curl -fsSL https://get.docker.com -o get-docker.sh 
sh get-docker.sh
  <br><br>
  安装gpt容器
docker run \
  --name chatgpt-web \
  -p 3002:3002 \
  --env OPENAI_API_KEY=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 \
  --restart always \
  -d chenzhaoyu94/chatgpt-web:latest
</p>
