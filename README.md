# qgis_demo_map.py

Демо-скрипт **PyQGIS**, який:
- генерує 50 випадкових точок у районі Львова (EPSG:3857),
- будує буфери 500 м та їх розчинення,
- зберігає результат у **GeoPackage**,
- створює простий макет карти та експортує **PNG**.

Репозиторій призначений для швидкого старту з GitHub + QGIS і отримання «зелених квадратиків» у contribution graph.

## Вимоги
- **QGIS 3.22+** (з Python та Processing)
- **Git**
- (Опційно) системний Python, якщо запускаєте поза QGIS

Перевірка:

## Клонування
```powershell
cd $env:USERPROFILE\Documents
git clone https://github.com/andreewandrei08-cyber/qgis_demo_map.py.git
cd qgis_demo_map.py
qgis_demo_map.py/
├─ qgis_demo_map.py
├─ README.md
└─ outputs/         # з'явиться автоматично (результати .gpkg, .png)
