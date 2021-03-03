# ip_amazon
curl -Ss https://ip-ranges.amazonaws.com/ip-ranges.json | jq -r '.prefixes [] .ip_prefix'
