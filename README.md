# sd-turbo-genai

**Autor:** Eduard Ávila

Programa para crear una imagen a partir de una descripción.

## Cómo ejecutarlo

Abre PowerShell en la carpeta del proyecto y ejecuta:

```powershell
uv sync
$env:HF_HUB_DISABLE_XET = "1"
uv run python src/sd_turbo_genai/__init__.py
```

Escribe la descripción cuando el programa la pida y pulsa Enter. El resultado se guarda como `imagen.png`.

## Imagen del ejemplo

![Imagen del ejemplo](imagen.png)

La imagen incluida es la del ejemplo de clase. Si vuelves a ejecutar el programa, se generará una nueva imagen.

Ejemplo de referencia: [repositorio original](https://github.com/fabianrodriguevara61-spec/sd-turbo-genai).

Powered by Stability AI. [Licencia del modelo](LICENSE-MODEL.txt).
