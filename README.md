# ASPNETCore7-REST_API-PublishImages_ContagemAcessos
Exemplo de API REST para contagem de acessos criada com .NET 7 ASP.NET Core. Inclui para a geração de imagens baseadas em Linux com o comando dotnet publish.

Comando para a geração das imagens:

```bash
dotnet publish --os linux --arch x64 /t:PublishContainer -c Release
```