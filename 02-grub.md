1) Мы изменили параметры GRUB_TIMEOUT=10 и вписали параметр GRUB_TIMEOUT_STYLE=menu.
<img width="1919" height="857" alt="image" src="https://github.com/user-attachments/assets/453d00a6-2c0b-4399-ad01-e545e59e0cb4" />
GRUB_TIMEOUT=10 этот пункт отвечает за то ,сколько меню GRUB весит на экране. В нашем случае это 10 секунд, по окончанию времени при загрузке выбернится пункт по умолчанию или пока вы сами его не выберите.
GRUB_TIMEOUT_STYLE=menu этот параметр отвечает за стиль поведения во время отчета времени. Меню отображается сразу, и идёт отсчёт времени на его экране.
<img width="1919" height="857" alt="image" src="https://github.com/user-attachments/assets/4167d162-bdd6-42ee-a17b-6a2637a056ae" />
<img width="1916" height="824" alt="image" src="https://github.com/user-attachments/assets/d41055c0-94e8-4b48-b9e3-811eb1702994" />
2) Если бы мы забыли выполнить update-grub, то файл изменится, но GRUB его не считает и продолжит загружаться при стандартных значениях.

(Cистема загрузилась полностью исправно, ошибок не было.)
