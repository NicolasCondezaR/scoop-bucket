# scoop-bucket

Bucket de Scoop de [Nicolás Condeza](https://github.com/NicolasCondezaR).

```powershell
scoop bucket add nicolascondezar https://github.com/NicolasCondezaR/scoop-bucket
scoop install <app>
```

## Aplicaciones

| App | Qué es |
|---|---|
| [`sonda`](https://github.com/NicolasCondezaR/sonda) | Proxy depurador de tráfico de desarrollo: HTTP y gRPC, con protobuf decodificado y los trailers preservados |

## Cómo se mantiene esto

Los manifiestos los genera y los escribe [GoReleaser](https://goreleaser.com)
cuando el proyecto de origen publica un tag. **No los edites a mano aquí**: el
cambio se perdería en la siguiente publicación. Lo que hay que corregir vive en
el `.goreleaser.yaml` del proyecto correspondiente.
