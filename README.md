# Grabador OBD Outlander

Herramienta web para diagnosticar una Mitsubishi Outlander 2007 (motor 2.4 L 4G69) con un adaptador ELM327 Bluetooth y un teléfono Android.

- **index.html**: grabador. Se conecta al adaptador por Bluetooth (Web Serial, Chrome 137+ en Android), lee códigos de falla, monitores y freeze frame, y graba recorridos.
- **analizador.html**: analizador. Revisa la grabación (mezcla, sondas O2, catalizador, temperatura, ralentí, carga, consumo) y explica los códigos en español.

Uso: empareja el adaptador en Ajustes → Bluetooth (clave 1234 o 0000), abre la página en Chrome, pon la llave en ON y toca Conectar. Hay un modo prueba con un carro simulado.

Los diagnósticos son orientativos y se basan en datos OBD genéricos.
