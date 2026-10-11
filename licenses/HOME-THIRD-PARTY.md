# SegaSonic HOME Setup19 — компоненты

Отдельный установщик распространяется под GPL-3.0-or-later. Полный текст
GPL и соответствующие исходники сохранены в этом комплекте.

- Sphaira native NCA/forwarder backend: ITotalJustice/sphaira commit
  0370e47f7fac0e426675624f363fe50f3b442048, GPL-3.0.
  Оригинал owo.upstream.cpp.txt, лицензия SPHAIRA_LICENSE.
- HomeTile compatibility adapter: Amir-Ehsani/HomeTile-switch commit
  19c429496501e6565489f2790461b794f562f613, GPL-3.0.
  Оригинал hometile_owo.hpp, лицензия HOMETILE_LICENSE.
- Forwarder NSO/NPDM: Nathan Rajlich, switch-nsp-forwarder0.0.8,
  commit61edd504e57c6007f23a3a242b386ac0372c0cee. MIT указан в исходном
  FORWARDER_PACKAGE.json; attribution из HomeTile сохранён UPSTREAM_NOTICES.md.
- devkitA64/libnx: используются установленные локальные SDK/libnx.
  Их copyright/license notices сохраняются из установленного SDK в архиве.
- Иконка SegaSonic: оригинальный игровой арт SEGA, provenance проекта
  assets/ui/PROVENANCE.json. Нет NintendoLogo/StartupMovie assets.

Изменения относительно источников: отдельный SegaSonic frontend;
адаптер поля export_nsp; получениеPFS0NSP из тех же3NCA перед установкой,
проверка полных байт/rename commit. Полные исходники и генератор
home-forwarder/source/main.cpp и tools/build_home_forwarder.py прилагаются.
Игра поставляется отдельным NRO с прежним игровым кодом, ROM не встраивается
в установщик или его NSP. Никакие ключи консоли не экспортируются.

Все URL, ревизии и SHA — PROVENANCE.json.
