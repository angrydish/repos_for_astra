# repos_for_astra

## сначала эти репки
```
deb http://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-main/ 1.7_x86-64 main contrib non-free
deb http://archive.debian.org/debian/ stretch main contrib non-free
```
---

затем
```
sudo apt install apt-transport-https ca-certificates
```

## по желанию
```
#deb cdrom:[OS Astra Linux 1.6 smolensk - amd64 DVD ]/ smolensk contrib main non-free
# Основной репозиторий (установочный диск)
deb https://dl.astralinux.ru/astra/stable/1.6_x86-64/repository smolensk main contrib non-free

#deb cdrom:[OS Astra Linux 1.6 smolensk-devel - amd64 DVD]/ smolensk contrib main non-free

#deb http://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-main/ 1.7_x86-64 main contrib non-free 

# Актуальное оперативное обновление основного репозитория
deb https://dl.astralinux.ru/astra/stable/1.6_x86-64/repository-update/ smolensk main contrib non-free

# Диск со средствами разработки
deb https://dl.astralinux.ru/astra/stable/1.6_x86-64/repository-dev/ smolensk main contrib non-free

# Актуальное оперативное обновление диска со средствами разработки
deb https://dl.astralinux.ru/astra/stable/1.6_x86-64/repository-dev-update/ smolensk main contrib non-free
```
