[General]
# 视频/漫画站点规则
# 生成时间: 2024
# 包含: jable.tv, 18comic.vip, missav, supjav 等域名

[Rule]
# 主域名
DOMAIN-SUFFIX,jable.tv,PROXY
DOMAIN-SUFFIX,18comic.vip,PROXY  
DOMAIN-SUFFIX,missav.com,PROXY
DOMAIN-SUFFIX,supjav.com,PROXY

# 备用域名和关联域名
DOMAIN-SUFFIX,jable.org,PROXY
DOMAIN-SUFFIX,18comic.org,PROXY
DOMAIN-SUFFIX,missav.org,PROXY
DOMAIN-SUFFIX,supjav.org,PROXY

# 关键词匹配（包含子域名）
DOMAIN-KEYWORD,jable,PROXY
DOMAIN-KEYWORD,18comic,PROXY
DOMAIN-KEYWORD,missav,PROXY
DOMAIN-KEYWORD,supjav,PROXY

# CDN和资源域名
DOMAIN-SUFFIX,cloudfront.net,PROXY
DOMAIN-SUFFIX,akamaized.net,PROXY

[Host]
# 本地DNS映射（可选）

[URL Rewrite]
# URL重写规则（可选）

[MITM]
# MITM主机名（可选）