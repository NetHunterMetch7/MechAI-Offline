# MechAI-Offline

**Toolkit open-source para IA offline en reparación automotriz**  
Recolecta manuales, diagramas e imágenes públicas; convierte datos 2D a modelos 3D básicos; chatbot local para mecánicos en talleres sin internet.  
¡Contribuye con datos públicos, scripts y mejoras!

## ¿Por qué este proyecto?
En talleres mecánicos de México y LATAM, el internet falla, es caro o no existe. Los mecánicos pierden tiempo buscando en YouTube o manuales caros.  
MechAI-Offline busca ser una herramienta gratuita y local que:
- Responda dudas técnicas con pasos claros (estructura Diagnóstico → Especificaciones → Procedimiento → Tips → Seguridad).
- Genere diagramas e imágenes 3D de piezas/fallas (zoom, rotar, resaltar en rojo).
- Funcione 100% offline en teléfonos Android viejos o tablets rugged.
- Sea comunitario: cualquiera puede añadir manuales públicos, scripts de conversión, o datasets.

## Características planeadas (MVP)
- Scripts Python para recolectar datos públicos (manuales, diagramas, imágenes de autos comunes en MX).
- Conversión básica 2D → 3D (usando Blender scripts o modelos open-source).
- Chatbot local (basado en modelos GGUF como Qwen2.5 o Llama 3.2) con prompt especializado en mecánica.
- Integración futura: voz hands-free, AR para superponer guías en cámara real, OBD-II básico.

## Cómo contribuir
¡Este proyecto crece con la comunidad!  
1. **Fork** el repositorio.
2. Crea una rama nueva (`git checkout -b feature/nombre-tu-mejora`).
3. Haz cambios (añade datos públicos, scripts, fixes, etc.).
4. Haz commit y push.
5. Abre un **Pull Request** con descripción clara.

**Qué puedes aportar ahora mismo:**
- Enlaces o archivos de manuales públicos/Haynes/Chilton (solo legal y no copyrighted).
- Imágenes/diagramas libres de derechos (Wikimedia, Pixabay, etc.).
- Scripts para descargar o procesar datos.
- Ideas para prompts del chatbot mecánico.

Lee [CONTRIBUTING.md](CONTRIBUTING.md) (lo crearemos pronto) para más detalles.

## Instalación y uso inicial (próximamente)
- Descarga modelos GGUF de Hugging Face.
- Corre scripts locales en Android (PocketPal AI, SDAI, etc.).
- Más detalles en la carpeta `/docs`.

## Licencia
MIT License – puedes usar, modificar y distribuir libremente.  
Copyright © 2026 Ander (NetHunterMetch7) – Todos los derechos reservados sobre la visión y dirección del proyecto.

## Contacto / Soporte
- Issues del repo para bugs/ideas.
- Twitter/X: @NetHunterMetch7 (si lo tienes, agrégalo).
- Email: 23ang.ang@gmail.com
¡Gracias por visitar! Si eres mecánico, dev o apasionado de autos, ¡únete y hagamos esto grande!
