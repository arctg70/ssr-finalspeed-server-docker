# ssr-finalspeed-server-docker
# usage:
docker run -d -p 150:150/udp -p 8388:8388 arctg70/ssr-finalspeed-server-docker

# shadowsocksr config file /shadowsocksr/user-config.json

{

    "server": "0.0.0.0",
    "server_ipv6": "::",
    "server_port": 8388,
    "local_address": "127.0.0.1",
    "local_port": 1080,

    "password": "m",
    "timeout": 120,
    "udp_timeout": 60,
    "method": "aes-128-ctr",
    "protocol": "auth_aes128_md5",
    "protocol_param": "",
    "obfs": "tls1.2_ticket_auth_compatible",
    "obfs_param": "",
    "speed_limit_per_con": 0,
    "speed_limit_per_user": 0,

    "dns_ipv6": false,
    "connect_verbose_info": 0,
    "redirect": "",
    "fast_open": false
}
# edit this file to change shadowsocksr config
