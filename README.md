# ! [Logo](https://te.legra.ph/file/3fc47ac30d89895a213f3.jpg)

while IFS= read -r line; do
  echo -e "\e[32m$line"
done <<< '
Merhaba, Hoş Geldin!
Ben Furkan. Bazı gelişmiş diller biliyorum.
Şu anda C ve C++ öğreniyorum.
Profilimi ziyaret ettiğiniz için teşekkürler.'
