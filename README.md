# Gestor de Voces — descargas

Archivos de descarga de **Gestor de Voces** (app de Windows para clonar tu voz en tu PC):
https://gestor-voces.mmasedafreire.workers.dev

- **Instalador**: en *Releases*, la versión más reciente (`GestorVoces-Setup.exe`).
- **Modelos de traducción** (release `traduccion-1`): los descarga la propia app si eliges la traducción automática.
  Cada archivo se verifica con SHA-256 antes de usarse.

## Atribuciones de los modelos de traducción
Modelos convertidos a CTranslate2 (int8) a partir de los originales de Helsinki-NLP (proyecto OPUS-MT):
- `opus-mt-es-en`, `opus-mt-es-fr`, `opus-mt-es-de`, `opus-mt-es-it` — Apache-2.0.
- `opus-mt-tc-big-en-pt` — CC BY 4.0. Autoría: Helsinki-NLP / Language Technology Research Group (Universidad de Helsinki).
  Modificado: convertido a formato CTranslate2 con cuantización int8.
