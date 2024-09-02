# @nodecfdi/tsconfig

[![Source Code][badge-source]][source]
[![Discord][badge-discord]][discord]
[![Latest Version][badge-release]][release]
[![Software License][badge-license]][license]
[![Total Downloads][badge-downloads]][downloads]

> La libreria `@nodecfdi/tsconfig` exporta la configuración base para Typescript usada en los proyectos de NodeCfdi.

:us: The documentation of this project is in spanish as this is the natural language for intended audience.

:mexico: La documentación del proyecto está en español porque ese es el lenguaje principal de los usuarios.

## Instalación

### NPM

```shell
npm i -D typescript @nodecfdi/tsconfig
```

### Yarn

```shell
yarn add -D typescript @nodecfdi/tsconfig
```

### PNPM

```shell
pnpm add -D typescript @nodecfdi/tsconfig
```

## Uso básico

Para libs de NodeCfdi, deberás de extender del archivo `tsconfig.package.json`:

```json
{
  "extends": "@nodecfdi/tsconfig/tsconfig.package.json"
}
```

Si tu estás creando un proyecto NodeCfdi web backend, deberás de extender del archivo `tsconfig.app.json`:

```json
{
  "extends": "@nodecfdi/tsconfig/tsconfig.app.json"
}
```

Si estás creando un proyecto NodeCfdi web frontend o con algún bundler resolver, deberás de extender del archivo `tsconfig.client.json`:

```json
{
  "extends": "@nodecfdi/tsconfig/tsconfig.client.json"
}
```

## Soporte

Puedes obtener soporte abriendo un ticket en Github.

Adicionalmente, esta librería pertenece a la comunidad [OcelotlStudio](https://ocelotlstudio.com), así que puedes usar los mismos canales de comunicación para obtener ayuda de algún miembro de la comunidad.

## Compatibilidad

Esta librería se mantendrá compatible con al menos la versión con
[soporte activo de Node](https://nodejs.org/es/about/releases/) más reciente y [soporte activo de Typescript](https://www.typescriptlang.org/) más reciente.

También utilizamos [Versionado Semántico 2.0.0](https://semver.org/lang/es/) por lo que puedes usar esta librería sin temor a romper tu aplicación.

## Contribuciones

Las contribuciones con bienvenidas. Por favor lee [CONTRIBUTING][] para más detalles y recuerda revisar el archivo [CHANGELOG][].

## Copyright and License

The `@nodecfdi/tsconfig` library is copyright © [NodeCfdi](https://github.com/nodecfdi) - [OcelotlStudio](https://ocelotlstudio.com) and licensed for use under the MIT License (MIT). Please see [LICENSE][] for more information.

[contributing]: https://github.com/nodecfdi/.github/blob/main/docs/CONTRIBUTING.md
[changelog]: https://github.com/nodecfdi/tsconfig/blob/main/CHANGELOG.md
[source]: https://github.com/nodecfdi/tsconfig
[discord]: https://discord.gg/AsqX8fkW2k
[release]: https://www.npmjs.com/package/@nodecfdi/tsconfig
[license]: https://github.com/nodecfdi/tsconfig/blob/main/LICENSE.md
[downloads]: https://www.npmjs.com/package/@nodecfdi/tsconfig
[badge-source]: https://img.shields.io/badge/source-nodecfdi/tsconfig-blue.svg?logo=github
[badge-node-version]: https://img.shields.io/node/v/@nodecfdi/tsconfig.svg?logo=nodedotjs
[badge-discord]: https://img.shields.io/discord/459860554090283019?logo=discord
[badge-release]: https://img.shields.io/npm/v/@nodecfdi/tsconfig.svg?logo=npm
[badge-license]: https://img.shields.io/github/license/nodecfdi/tsconfig.svg?logo=open-source-initiative
[badge-downloads]: https://img.shields.io/npm/dm/@nodecfdi/cfdi-to-pdf.svg?logo=npm
