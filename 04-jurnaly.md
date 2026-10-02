1) У нас обнаружилось 2 ошибки gnome-keyring(Он отвечает за безопасное хранение паролей к Wi-Fi и приложениям, а также SSH-ключей.) и xdg-user-dirs (Эта служба создаёт и поддерживает стандартные папки в домашнем каталоге).
<img width="1917" height="932" alt="image" src="https://github.com/user-attachments/assets/8f036395-a5fd-43b2-9997-5cf76c6f1697" />
2) Plymouth - это графическая заставка, которую мы видем при загрузке Debian.
<img width="1919" height="246" alt="image" src="https://github.com/user-attachments/assets/c3e6d94c-8e89-4ca8-9325-6fe8b14da324" />
3) Последние 30 сообщений ядра.
<img width="1918" height="749" alt="image" src="https://github.com/user-attachments/assets/de07df6a-3790-4854-800c-d6da03be77a0" />
4) journalctl -b показывает логи текущей загрузки, а journalctl -b -1 показывает логи предыдущей загрузки. Второй случай нам нужен при происхождении каких либо ошибок при загрузки системы, для того , что бы понять что с системой пошло не так.
