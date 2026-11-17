# atlaspop-models

Modelos 3D de aviones, cabinas y pinturas (liveries) para [Atlas Pop](https://map.angeldev.fr.eu.org), convertidos a glTF (.glb) y WebP.

## Origen y licencia
Licencia: **GNU GPL v2 o posterior** (ver `LICENSE`). Los modelos se han simplificado (menos polígonos), sus texturas comprimidas y las animaciones de FlightGear (tren, flaps, spoilers, mandos, instrumentos) se guardan como metadatos en cada nodo. Autores y enlaces: `CREDITS.json`.

Fuentes de los modelos:
- Aeronaves de FGAddon: <https://svn.code.sf.net/p/flightgear/fgaddon/trunk/Aircraft/>
- Embraer E-Jet family: <https://github.com/YV3399/E-jet-family-YV>
- Airbus A330: <https://github.com/JMaverick16/Airbus_A330>
- Boeing 787 family: <https://github.com/IskenderWang/787-family>
- Pinturas adicionales: A320-family-liveries, Animuuu-FG-Liveries, IW-liveries, Pilot2938-FG-liveries y naviat-dev-FG-Liveries (colecciones para FlightGear).

## Estructura
`index.json` (catálogo), `<modelo>/model.glb`, `<modelo>/cockpit.glb` (cabina de mando, si existe), `<modelo>/tex/*.webp`, `<modelo>/liv/<ICAO>-N.webp` (pinturas por aerolínea).
