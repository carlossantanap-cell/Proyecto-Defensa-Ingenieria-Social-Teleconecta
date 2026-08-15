# 🛡️ Programa Integral de Defensa contra Ingeniería Social

> ⚠️ **Nota importante:** Este es un trabajo **académico individual** del curso *Ingeniería Social* (UNI, 2026). La empresa **"TeleConecta Perú S.A.C."**, sus empleados, incidentes y comunicaciones son **completamente ficticios**, creados únicamente con fines educativos. Cualquier parecido con personas, empresas o eventos reales es coincidencia. Ninguna evidencia aquí representa un ataque real ni fue ejecutada contra terceros sin autorización.

Diseño de un programa integral de defensa contra ataques de ingeniería social, con énfasis en **phishing**, para una empresa ficticia de telecomunicaciones (TeleConecta Perú S.A.C.).

## 🎯 Alcance del trabajo

1. **Reconocimiento OSINT** simulado: técnicas y herramientas usadas para el reconocimiento de información pública (DNSDumpster, LinkedIn/Google Dorking, Hunter.io, HaveIBeenPwned, Shodan, Maltego)
2. **Modelado y simulación de 3 escenarios de ataque:**
   - 📧 Phishing masivo (campaña simulada con GoPhish)
   - ☎️ Vishing / Pretexting (llamada simulada)
   - 🎙️ Deepfake de voz / CEO Fraud (audio sintético generado con IA, simulando al "CEO" ficticio de la empresa)
3. **Análisis de riesgos** de los escenarios simulados
4. **Diseño de un programa de defensa**, mapeado a los frameworks:
   - NIST CSF
   - ISO/IEC 27001
   - MITRE ATT&CK

## 📁 Contenido del repositorio

```
├── informe/
│   └── Informe_Defensa_IngenieriaSocial_TeleConecta.pdf
├── presentacion/
│   └── Presentacion_TeleConecta.pdf
├── data/
│   ├── grupo_administrativo_comercial.csv   # Nombres, correos y roles ficticios
│   ├── grupo_ejecutivo_mando_medio.csv
│   └── grupo_tecnico_noc.csv
└── evidencias/
    ├── gophish/
    │   └── *.csv                # Resultados descargados de las campañas simuladas
    └── vishing/
        └── escenario2.mp3       # Audio con voz robótica (TTS genérico), sin clonar voces reales
```

> Las capturas de pantalla (reales y simuladas en HTML) se mantienen fuera del repositorio para evitar confusión entre evidencia simulada y real; están incluidas dentro del informe PDF.

## 🧰 Herramientas y técnicas empleadas

- **OSINT:** DNSDumpster, Google/LinkedIn Dorking, Hunter.io, HaveIBeenPwned, Shodan, Maltego
- **Simulación de phishing:** GoPhish
- **Síntesis de voz (IA):** generación de audio para el escenario de CEO Fraud
- **Frameworks de referencia:** NIST CSF, ISO/IEC 27001, MITRE ATT&CK

## 📄 Documentos

- [`informe/`](./informe) — Informe técnico completo con metodología, hallazgos y programa de defensa propuesto
- [`presentacion/`](./presentacion) — Presentación resumen del trabajo

## 👤 Autor

Carlos Henry Santana Palomino
Curso: Ingeniería Social — UNI, 2026
