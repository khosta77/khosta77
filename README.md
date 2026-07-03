<h1 align="center">Stepan Filimonov</h1>

<p align="center">
  <b>Senior C++ Engineer</b> · Embedded &amp; Systems · Москва
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-17%2F20-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/STM32-bare--metal-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32"/>
  <img src="https://img.shields.io/badge/CMSIS-only-005A9C?style=flat-square" alt="CMSIS"/>
  <img src="https://img.shields.io/badge/BLE-nRF5340-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white" alt="nRF5340"/>
  <img src="https://img.shields.io/badge/KasperskyOS-internals-006D5B?style=flat-square" alt="KasperskyOS"/>
</p>

---

## О себе

Senior C++ инженер в Сбере, работаю на стыке embedded и системного программирования.
Специализируюсь на bare-metal прошивках для STM32 (чистый CMSIS, без HAL/LL), носимой
электронике на nRF5340 с BLE и внутренностях KasperskyOS. Автор [stm32-sdk](https://github.com/khosta77/stm32-sdk) —
bare-metal C++20 SDK со своим генератором проектов и CI.

---

## Ключевые проекты

### Embedded / bare-metal

- **[stm32-sdk](https://github.com/khosta77/stm32-sdk)** — bare-metal C++20 SDK для микроконтроллеров STM32: только CMSIS (без HAL/LL), опциональный FreeRTOS, драйверы и шаблоны проектов. Свой CLI `stmtool` (Python) для генерации, сборки и прошивки. Сборка под `-Werror -Wall -Wextra -Wpedantic -Wshadow`, документация на EN/RU через MkDocs.

### Экосистема ЧПУ

- **[project_Squid](https://github.com/khosta77/project_Squid)** — система управления до 10 шаговыми двигателями для ЧПУ-станков: центральный STM32F407VG (Cortex-M4) и 10 драйверов STM32G031F8P6 (Cortex-M0+) через мультиплексор, синхронный и асинхронный режимы, единый Python CLI, unit- и интеграционные тесты. Прошивка на чистом CMSIS.
- **[OctopusNode](https://github.com/khosta77/OctopusNode)** — модульная система ЧПУ-контроля.
- **[MotorManagerService](https://github.com/khosta77/MotorManagerService)** — микросервис управления шаговыми двигателями через TCP-сокеты: RESTful API и веб-интерфейс, подключение к MCU через мост FT232RL.

### Приборы и сервисы

- **[ServerForOscilloscope](https://github.com/khosta77/ServerForOscilloscope)** — сервер для удалённого доступа к осциллографам с расширяемой архитектурой (общий базовый класс `Oscilloscope`).
- **[HT6022_lib_cpp](https://github.com/khosta77/HT6022_lib_cpp)** — C++ библиотека для осциллографа Hantek HT6022BE.

### Библиотеки и алгоритмы

- **[MOEX_Cpp_API](https://github.com/khosta77/MOEX_Cpp_API)** — C++ библиотека для работы с API Московской биржи (котировки и свечи инструментов).
- **[SSort](https://github.com/khosta77/SSort)** — header-only реализация 13 алгоритмов сортировки с инструментом для их сравнительного анализа.

---

## Стек

**Языки**

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
</p>

**Embedded**

<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32"/>
  <img src="https://img.shields.io/badge/CMSIS-005A9C?style=flat-square" alt="CMSIS"/>
  <img src="https://img.shields.io/badge/nRF5340-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white" alt="nRF5340"/>
  <img src="https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white" alt="BLE"/>
  <img src="https://img.shields.io/badge/FreeRTOS-008000?style=flat-square&logo=freertos&logoColor=white" alt="FreeRTOS"/>
  <img src="https://img.shields.io/badge/KasperskyOS-006D5B?style=flat-square" alt="KasperskyOS"/>
</p>

**Инструменты**

<p>
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="CI"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

## Контакты

- GitHub: [@khosta77](https://github.com/khosta77)

---

<!-- Внешний сервис github-readme-stats (сторонний хостинг, не под контролем автора). -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=khosta77&show_icons=true&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=khosta77&layout=compact&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
</p>
